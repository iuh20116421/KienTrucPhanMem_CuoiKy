
Hướng dẫn sử dụng backend:
Đầu tiên sau khi tải về: ta dùng phần mềm Intelij IDEA để mở lên:
Ta sẽ thấy bố cục chung của project như này:
![h1](./imgs/h1.png)
Sau đó ta vào Student_Service vào file DataSampleConfig:
![h2](./imgs/h2.png)
Ta mở comment @Bean của hàm initDatabase:
![h3](./imgs/h3.png)
![h4](./imgs/h4.png)
Sau đó mở lớp StudentServiceApplication rồi chạy để mapping ra csdl và sau khi chạy xong thì nhớ comment @Bean của hàm initDatabase lại(tránh thêm dữ liệu mỗi lần chạy vào csdl):
![h5](./imgs/h5.png)
Tương tự như vậy với DKHP_Service:
![h6](./imgs/h6.png)
Sau khi thực hiện xong các bước trên thì ta nên start lần lược theo thứ tự như sau(và đảm bảo trong quá trình dùng api thì cả 3 phải đều đang chạy):
![h7](./imgs/h7.png)
