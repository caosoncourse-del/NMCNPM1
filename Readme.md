🏦 Software Engineering Project – ATM Mini Project
📌 Giới thiệu

Dự án ATM Mini Project được phát triển trong môn Nhập môn Công nghệ Phần mềm (NMCNPM01).
Mục tiêu của dự án là mô phỏng một hệ thống ATM cơ bản, áp dụng đầy đủ quy trình phát triển phần mềm: phân tích yêu cầu, thiết kế UML, lập trình, kiểm thử và quản lý dự án theo mô hình Agile – Scrum.

👥 Thành viên nhóm
Cao Nguyễn Anh Sơn – Leader / Developer

🎯 Use Case chính
Đăng nhập người dùng (Login)
Rút tiền (Withdraw)
Kiểm tra số dư (Check Balance)
Chuyển khoản (Transfer)
Ghi nhận giao dịch & báo cáo lịch sử

(Hình minh họa Use Case Diagram được đính kèm bên dưới)

📐 Thiết kế hệ thống
Use Case Diagram:
Sequence Diagram:
ERD (Entity Relationship Diagram):
Class Diagram:
Package Diagram:
💻 Công nghệ sử dụng
Ngôn ngữ: Python
IDE: Visual Studio Code
Cơ sở dữ liệu: MySQL
Quản lý phiên bản: Git + GitHub
Mô hình phát triển: Agile – Scrum
Công cụ UML: PlantUML, draw.io
Công cụ quản lý dự án: Jira
🚀 Cài đặt & chạy thử

Clone repo:

git clone https://github.com/vancv43/atm-mini-project.git
cd atm-mini-project


Cài đặt thư viện cần thiết:

pip install mysql-connector-python pytest selenium


Cấu hình cơ sở dữ liệu trong config.py:

DB_USER = "root"
DB_PASSWORD = "123456"
DB_NAME = "atm_demo"


Chạy demo rút tiền:

python labs/lab07-withdraw-module/withdraw.py


Kiểm thử tự động:

pytest labs/lab08-testing/

🧪 Nội dung các Lab
Lab 01 – Thiết lập môi trường & GitHub
Làm quen với Git, GitHub.
Tạo repository, commit, push, pull.
Upload file giới thiệu cá nhân.
Lab 02 – Phân tích yêu cầu & Use Case
Chọn mini project: Hệ thống ATM.
Vẽ Use Case Diagram và mô tả chức năng.
Upload file .drawio hoặc ảnh UML lên repo.
Lab 03 – Thiết kế UML (Sequence Diagram)
Mô tả luồng tương tác cho quy trình Rút tiền.
Giải thích các đối tượng và thông điệp trao đổi.
Lab 04 – Giao diện Form Login
Xây dựng form đăng nhập bằng HTML, CSS, JS.
Có kiểm tra dữ liệu nhập cơ bản (validation).
Lab 05 – Tích hợp & Báo cáo
Gom tất cả artifacts (Use Case, Sequence, Form Login).
Viết báo cáo Markdown mô tả quy trình làm việc.
Lab 06 – Thiết kế Class & Package Diagram
Tạo sơ đồ lớp và sơ đồ gói cho hệ thống ATM.
Đảm bảo đầy đủ quan hệ và thuộc tính.
Lab 07 – Module Rút tiền (Withdraw)
Code Python mô phỏng giao dịch rút tiền.
Kết nối MySQL và log transaction.
Lab 08 – Kiểm thử (Unit & Integration Test)
Viết Unit Test cho hàm verify_pin() và withdraw().
Viết Integration Test cho Form Login bằng Selenium.
Lab 09 – Quản lý dự án trên Jira
Tạo Epic, User Stories, Tasks/Subtasks.
Lập Sprint 1, chụp hình Backlog, Board, Burndown.
Lab 10 – Báo cáo tổng hợp & Demo cuối kỳ
Tích hợp toàn bộ module.
Demo form login → withdraw → báo cáo Jira.
Viết final-report.md mô tả toàn bộ quy trình.
📊 Cấu trúc thư mục dự án
atm-mini-project/
│
├── docs/
│   ├── usecase.png
│   ├── sequence.png
│   └── erd.png
│
├── labs/
│   ├── lab01-setup/
│   ├── lab02-usecase/
│   ├── lab03-sequence/
│   ├── lab04-login-form/
│   ├── lab05-report/
│   ├── lab06-atm-class/
│   ├── lab07-withdraw-module/
│   ├── lab08-testing/
│   ├── lab09-jira/
│   └── lab10-final-demo/
│
├── src/
│   ├── atm.py
│   ├── card.py
│   ├── account.py
│   └── transaction.py
│
├── config.py
├── requirements.txt
└── README.md

🏁 Kết luận

Dự án ATM Mini Project giúp nhóm hiểu rõ quy trình phát triển phần mềm theo mô hình Agile – Scrum, từ giai đoạn phân tích, thiết kế UML, đến triển khai, kiểm thử và báo cáo.
Hệ thống có thể mở rộng thêm các tính năng như: nạp tiền, đổi PIN, quản lý nhiều ATM, và giao diện người dùng nâng cao.

Software Engineering Lab | NMCNPM01 – 2025
📅 Hoàn thành: Tháng 10, 2025
👨‍💻 Trường Học Viện Bưu Chính Viễn Thông
