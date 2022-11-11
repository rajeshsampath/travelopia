Running instructions For Backend: 
1. cd backend-api
2. npm i && npm start // Backend application will start and run on Port number 3000
3. Used express framework, mongoose
4. Used own altas cluster account the information of dburi following below
    DB_URI=mongodb+srv://admin:test123@cluster0.aomfjnv.mongodb.net/travelopedia-home-test

Running instructions for Consumer APP:
1. cd consumer-app
2. npm i && npm start // Consumer application will start and run on port 4200
3. Used angular 14, angular material, 
4. The API_URL are configured in consumer-app>src>environtments>environment.ts (API_URL: "http://localhost:3000")


