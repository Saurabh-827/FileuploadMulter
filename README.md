# 📁 File Upload Project 📁

This project is a simple yet powerful **file upload application** built with **Node.js** and **Express**. Leveraging **Multer**, this app allows users to seamlessly upload images while supporting multiple file uploads with restrictions on file types and sizes.

## 🌟 Features

- **Multiple File Uploads**: Users can effortlessly select and upload multiple image files at once, enhancing user experience.
- **File Size Limit**: To ensure optimal performance, uploaded files are limited to **2MB**.
- **File Type Restriction**: Only **JPEG**, **PNG**, and **GIF** image formats are accepted, ensuring high-quality uploads.
- **Dynamic Filenames**: Uploaded files are saved with a unique timestamp, preventing naming conflicts and organizing files neatly.

## 🚀 How to Use

To get started with this project, follow these easy steps:

1. **Clone the repository to your local machine**:
   ```bash
   git clone https://github.com/Saurabh-827/FileuploadMulter.git
   cd file-upload-project
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Create an uploads directory** (if it doesn't exist):
   ```bash
   mkdir uploads
   ```

4. **Start the server**:
   ```bash
   node index.js
   ```

5. **Open your browser and navigate to** `http://localhost:3000` to access the intuitive file upload form.

## 🎨 Customization

Feel free to customize this project to fit your unique needs:

- **Change Allowed File Types**: Modify the `filetypes` variable in the `fileFilter` function to permit different file types that suit your application.
- **Adjust File Size Limit**: Change the `fileSize` property in the `limits` object to allow larger or smaller files as necessary.
- **Modify the Upload Path**: Adjust the `destination` in the `storage` configuration to choose where uploaded files should be saved.

## 💻 Technologies Used

This project utilizes a combination of powerful technologies:

- **HTML**: For structuring the web application.
- **JavaScript (Node.js)**: For server-side logic and functionality.
- **Express**: A robust web framework for Node.js to handle routing and middleware.
- **Multer**: A middleware for handling `multipart/form-data`, which is primarily used for uploading files.
