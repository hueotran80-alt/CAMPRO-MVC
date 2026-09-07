# CAMPRO MVC

Website bán camera sử dụng Node.js, Express, EJS và MySQL.

## Chạy local

1. Cài Node.js LTS và MySQL.
2. Tạo database `campro` và import `database.sql`.
3. Copy `.env.example` thành `.env` và điền thông tin MySQL.
4. Cài dependencies:

```bash
npm install
```

5. Chạy:

```bash
npm start
```

Mở `http://localhost:5000`.

## Deploy

Không commit `.env`. Trên hosting, khai báo các biến môi trường tương ứng.

Project hỗ trợ cả nhóm biến `DB_*` và biến MySQL phổ biến `MYSQLHOST`, `MYSQLPORT`, `MYSQLUSER`, `MYSQLPASSWORD`, `MYSQLDATABASE`.

## GitHub

Repository này nên được khởi tạo như một Git repository mới, không giữ lịch sử `.git` cũ.
