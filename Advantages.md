Docker là một nền tảng mở (open platform), dùng để phát triển và vận hành ứng dụng.

1. Với sự hỗ trợ của docker, việc coding, testing, deploying trở nên đơn giản hơn.

2. Khả năng di động (portable): môi trường develop được dựng lên bằng docker có thể chuyển từ người này sang người khác mà không làm thay đổi cấu hình ở trong. Trong kỹ thuật, được gọi là provisioning.

3. Application-centric: docker được dùng trên nhiều môi trường, đặc biệt tương thích trên môi trường develop, hướng đến việc coding thuận tiện nhất.

4. Versioning: docker được tích hợp VCS-git, để tracking các dòng lệnh thiết lập, hay đánh dấu version.

5. Component re-use: nghĩa là docker có khả năng sử dụng lại resource trước đó, bằng cách đánh dấu những resources giống nhau bằng một mã ID. Các môi trường được dựng lên sau đó sẽ kiểm tra các mã ID trước đó, nếu trùng docker sẽ sử dụng lại.

6. Sharing: với Docker Hub (public registry), các developer có thể tìm và sử dụng các môi trường được dựng sẵn.