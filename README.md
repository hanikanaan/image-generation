# Image Generation Site using OpenAI's DALL-E model

## Running your instance
Simply download the code and run the following:
```shell
npm install
```
Create a .env folder, and add your API keys for MongoDB, Cloudinary, and OpenAI as such:
```javascript
OPENAI_API_KEY="XX-XXXXXXX"
MONGODB_URL="mongodb+srv://<yourusername>:<yourpassword>@<yourcluster>.XXXXXXX.mongodb.net/?retrywrites=true&w=majority
CLOUDINARY_CLOUD_NAME="XXXXXXXX"
CLOUDINARY_API_KEY="XXXXXXXXX"
CLOUDINARY_API_SECRET="XXXXXXXX"
```
Finally, start your application with:
```shell
npm run dev
npm run start-server
```
