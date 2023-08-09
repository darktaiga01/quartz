#algorithm #dynamic-connectivity

# Khái niệm

![[Pasted image 20230614213148.png]]

Cho N đối tượng (Object):
Ta cần:
- Hợp (union): Kết nối 2 đối tượng
- Tìm (find/connected query): Xác định 2 đối tượng đã được kết nối với nhau chưa, hay kết nối với nhau bằng liên kết đoạn thẳng (path) nào

# Đặc trưng

- **Reflexive** (Phản thân): p kết nối với p - tức nó tự kết nối với chính nó, mặc định là luôn đúng (sẽ kiểm chứng lại sau)
- **Symmetric** (Tương quan): p kết nối với q => q kết nối với p
- **Transitive** (Bắc cầu): p kết nối với q, q kết nối với r => p kết nối với r



