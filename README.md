# Experiment 15: File Upload and Rate Limiting

## Objective
- Implement file upload using Multer
- Demonstrate request throttling using express-rate-limit

## Steps
1. Setup Node.js project and install dependencies:
   - express, multer, express-rate-limit, dotenv, body-parser
2. Create .env for PORT and UPLOAD_DIR
3. Configure Multer:
   - Set destination folder and unique filename
4. Configure rate limiting:
   - Limit each IP to 5 requests per minute
5. Implement routes:
   - GET / → Welcome message
   - POST /upload → Upload single file
   - GET /files → List uploaded files
6. Test using Postman:
   - Upload files using form-data
   - Access /files to list uploaded files
   - Test rate limiting by sending multiple requests

## Notes
- Uploaded files are stored in uploads/ folder
- Rate limiting prevents abuse by limiting requests per minute

## Screenshots
*File Upload Response*:

![App Screenshot](public/image.png)
