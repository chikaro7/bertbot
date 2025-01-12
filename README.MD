# BertBot - Patient Disease Detection, Analysis, and Recommendation Bot

**BertBot** is a disease detection and recommendation bot for patients, built using **Next.js + Vite** for the frontend and **Django** for the backend, along with **MySQL** and **RabbitMQ** for data storage and messaging.

## Tech Stack

- **Frontend**: Next.js + Vite
- **Backend**: Django
- **Database**: MySQL
- **Message Broker**: RabbitMQ

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/bertbot.git
   cd bertbot
    ```

2. **Install frontend dependencies**
    ```
    cd frontend
    npm install
    ```   

3. **Install backend dependencies**
    ```
    cd backend
    pip install -r requirements.txt
    ```



4. **environmental variables**
    ```
    NEXT_PUBLIC_API_URL=http://localhost:8000
    ```


5. **start up the docker containers**
    ```
    docker-compose up --build
    ```

