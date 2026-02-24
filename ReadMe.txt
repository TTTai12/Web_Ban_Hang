=== THÔNG TIN CÔNG NGHỆ / NGÔN NGỮ ===

FRONTEND (Web_Ban_Hang gốc)
- Ngôn ngữ: JavaScript, JSX.
- Framework: React 18 (Create React App với react-scripts).
- UI: Ant Design (antd, @ant-design/icons), Material UI (@mui/material, @emotion/*), styled-components, react-slick + slick-carousel.
- State/data: Redux Toolkit + React-Redux, Redux Persist, React Query (@tanstack/react-query).
- Routing & API: react-router-dom v6, axios, jwt-decode.

BACKEND (DemoCode-Backend)
- Ngôn ngữ: JavaScript (Node.js).
- Framework: Express.
- Cơ sở dữ liệu: MongoDB (Mongoose).
- Xác thực/bảo mật: bcrypt (hash mật khẩu), jsonwebtoken (JWT).
- Khác: dotenv (env), cors, cookie-parser, body-parser, nodemailer (+ plugin inline-base64), nodemon.

=== CÁCH CHẠY DỰ ÁN ===

1. Cài dependency (chỉ cần làm 1 lần)
   - Frontend (thư mục gốc Web_Ban_Hang):
     npm install

   - Backend (trong DemoCode-Backend):
     cd DemoCode-Backend
     npm install

2. Chạy dự án (mở 2 terminal)

   - Terminal 1: chạy FRONTEND
     (ở thư mục gốc Web_Ban_Hang)
     npm start
     → Mặc định chạy ở http://localhost:3000

   - Terminal 2: chạy BACKEND
     cd DemoCode-Backend
     npm start
     → Chạy server Node/Express (port xem trong src/index.js hoặc biến môi trường).