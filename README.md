
## Setup Instructions

### Prerequisites
- Node.js
- Docker
- MongoDB 

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RAWATSANCHIT/Sanchit-Rawat-AnswersAi-Backend.git

2. Install dependencies:
    ```bash
    npm install

3. Run the app:
    ```bash
    npm start

### Running with Docker Compose

1. Use the following command
    ```bash
    docker compose-up --build

2. Change the following env variables in the docker-compose.yaml:
    - MONGO_URI=mongodb://mongodb_new:27017/answers_ai

### Environment Variables
Create a `.env` file in the root directory with the following variables:
 - DATABASE_URL=mongodb://localhost:27017/your_db_name
 - JWT_SECRET=your_jwt_secret
 - API_SECRET=your_anthropic_api_secret
 - PORT=3000
