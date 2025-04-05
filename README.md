CRETAE A .env Folder in yout backend and add thse 

MONGODB_URI=Your MongoDB Atlas Dtabase URL
PORT=5001
JWT_SECRET= mySecretKey
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development

Then:

cd frontend 
npm create vite@latest .
react > js
npm install
npm run dev

cd backend
npm init-y
npm i express mongoose dotenv jsonwebtoken bcryptjs cookie-parser cloudinary socket.io
npm install cloudinary multer
cls
npm i nodemon -D
npm run dev
