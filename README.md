# TherapEase.ai


# Mental Health Game Application

This is a mental health game application built with MERN stack and using Transformer model - BART for summarization and Generative Model - Stable Diffusion-XL for pictionary image generation. The application allows users to play games using pictures, and based on the response times for each question, therapists can gain insights into the patient's mental state.

## Features

- Play mental health games using pictures. Similar to Pictionary.
- Pictures for pictionary game are generated using Stable Diffusion-XL on the go.
- Therapist are allowed to add new questions, and their respected scores.
- Track response times for each question.
- Therapists can gain insights into the patient's mental state based on response times.
- Therapist will be provided with the summary and visualization of all the parameters from the Pictionary Game
- We have classified the patients status it based on the parameters and behavioural patterns as stated by WHO.

## Technologies Used

- Node.js
- React
- Express.js
- MongoDB (optional, for storing user data and game results)
- Generative AI - Stable Diffusion-XL
- Transformer - BART


## Installation

1. Clone the repository:

    ```
    git clone https://github.com/your-username/TherapEase.ai.git
    ```

2. Navigate to the project directory:

    ```
    cd TherapEase.ai
    ```

3. Install dependencies for the server:

    ```
    npm install
    ```

4. Navigate to the client directory:

    ```
    cd frontend
    ```

5. Install dependencies for the client:

    ```
    npm install
    ```

## Usage

1. Start the server:

    ```
    cd backend
    node index.js
    ```

2. Start the client:

    ```
    cd frontend
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to access the application.

4. Play mental health game, the rest is taken care by our backend and summary is viewed in doctors/therapist view window.

