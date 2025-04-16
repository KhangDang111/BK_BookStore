# Software Engineer Project
## Dependencies downloading: npm install
## Run the server: npm start
## Branches
There are 3 branches (main, backend, frontend, version_1), each team (fronted/backend) will work on corresponding branhces and then merge into version_1 branch. Main branch will contain the final version.


📚 BK_BookStore
BK_BookStore là một ứng dụng web quản lý hiệu sách trực tuyến được xây dựng bằng Node.js và tích hợp với Neon (PostgreSQL serverless). Dự án hỗ trợ quản lý sách, người dùng, đơn hàng, giỏ hàng và các chức năng thương mại điện tử cơ bản.

🛠️ Công nghệ sử dụng
Node.js (Express.js) – Backend API

PostgreSQL – Hệ quản trị cơ sở dữ liệu (hosted by Neon)

Sequelize / Prisma – ORM cho Node.js (tuỳ bạn dùng gì)

JWT – Xác thực người dùng

bcrypt – Mã hóa mật khẩu

dotenv – Biến môi trường

⚙️ Cài đặt
Yêu cầu
Node.js >= 16

PostgreSQL database (khuyên dùng Neon)

Bước cài đặt
bash
Sao chép
Chỉnh sửa
# Clone repo
git clone https://github.com/your-username/BK_BookStore.git

# Cài dependencies
cd BK_BookStore
npm install

# Tạo file .env và cập nhật thông tin kết nối DB
cp .env.example .env
.env ví dụ:

env
Sao chép
Chỉnh sửa
PORT=3000
DATABASE_URL=postgresql://username:password@your-neon-host/dbname
JWT_SECRET=your_jwt_secret
Khởi chạy dự án
bash
Sao chép
Chỉnh sửa
npm run dev
Server sẽ chạy tại http://localhost:3000

📦 Tính năng chính
Đăng ký / đăng nhập người dùng (JWT-based)

Quản lý sách (CRUD)

Giỏ hàng và đơn hàng

Tìm kiếm và phân loại sách

Phân quyền người dùng (admin, user)

Kết nối PostgreSQL trên nền tảng Neon

🧪 Test
Tùy bạn dùng framework nào, ví dụ với Jest:

bash
Sao chép
Chỉnh sửa
npm run test
🚀 Triển khai
Bạn có thể triển khai dễ dàng với các nền tảng như:

Vercel (cho frontend)

Railway / Render / Fly.io (cho backend Node.js)

🧑‍💻 Đóng góp
Mọi đóng góp đều được chào đón!

Fork repo

Tạo nhánh mới: git checkout -b feature/tính-năng

Commit: git commit -m "Thêm tính năng"

Push và tạo Pull Request
