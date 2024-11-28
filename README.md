1. Install dependencies
    cd social-media-app  
    npm install
    cd client
    npm install

2. Create .env in root directory

3. Configure environment variables in your new .env file.
    MONGO_URI=<YOUR_MONGO_URI> 
    TOKEN_KEY=<YOUR_TOKEN_KEY>
    PORT=4000

4. Run the server
    npm run server

5. Start a new terminal and run react's development server
    cd client
    npm start