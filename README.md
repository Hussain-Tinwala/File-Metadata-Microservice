# 📁 File Metadata Microservice

This is a simple Node.js + Express.js microservice that allows users to upload a file and returns metadata such as the file name, type, and size.

## 🚀 Features

- Upload a file via a form
- Returns:
  - Original file name
  - MIME type
  - File size (in bytes)
- Frontend styled with Tailwind CSS


## 🛠️ Installation & Setup

1. **Clone the repository**
 
2. **Install dependencies**
   ```
   npm install
   ```

3. **Run the server**
   ```
   npm start
   ```

4. **Visit in browser**
   ```
   http://localhost:3000
   ```

## 📤 API Endpoint

### POST `/api/fileanalyse`

**Form Field:**
- `upfile` (type: file)

**Response:**
```json
{
  "name": "example.txt",
  "type": "text/plain",
  "size": 345
}
```

## 📦 Dependencies

- express
- multer
- cors
- dotenv
