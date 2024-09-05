
# Orgobot: Organ Donation Application with AI-Powered Bot

## Overview
Orgobot is a cutting-edge organ donation platform that integrates an AI-powered chatbot to assist users in learning about organ donation. The chatbot, powered by GPT-3, provides accurate and personalized responses to user queries, making it easier for people to explore donation options, eligibility, and procedures. This project aims to enhance user engagement, simplify organ donation processes, and make critical information more accessible.

Orgobot is built on the MERN stack (MongoDB, Express.js, React.js, Node.js), offering scalability and flexibility for future enhancements. The platform also focuses on user experience by providing real-time form validations and an intuitive, responsive interface.

## Features
- **AI-Powered Chatbot**: Responds intelligently to user questions about organ donation, eligibility, processes, and benefits, powered by GPT-3.
- **Organ Donor Registration**: Allows users to register as organ donors through a streamlined process.
- **Real-time Input Validation**: Ensures data accuracy with immediate validation of user inputs such as email, contact information, and organ type.
- **Interactive Dashboard**: Displays user information and organ donation history.
- **Responsive UI**: Fully optimized for mobile, tablet, and desktop devices.
- **Accessible Design**: Built with accessibility in mind, supporting features like screen readers and keyboard navigation.

## Technologies Used
- **Frontend**: React.js, with modern UI components and responsive design.
- **Backend**: Node.js and Express.js, providing a robust API for handling chatbot interactions and organ donor data.
- **Database**: MongoDB, for efficient and scalable data storage.
- **AI Integration**: GPT-3 (via OpenAI API) for generating dynamic responses to user queries.
- **Real-time Validation**: Using Formik and Yup libraries for client-side form validation.
- **State Management**: Redux for managing the state of the application across multiple components.
- **Deployment**: The app is hosted on cloud platforms like Heroku or AWS for scalable deployment.

## Installation

### Prerequisites
- **Node.js** (v12+)
- **MongoDB** (local or cloud instance)
- **NPM** (Node Package Manager)
- **API Key**: Sign up for the GPT-3 API key from [OpenAI](https://beta.openai.com/signup/).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/orgobot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd orgobot
   ```

3. Install dependencies for both frontend and backend:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

4. Create a `.env` file in the backend folder and add the necessary environment variables:
   ```bash
   PORT=5000
   MONGO_URI=your-mongo-db-uri
   GPT_API_KEY=your-openai-api-key
   ```

5. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

6. Start the frontend development server:
   ```bash
   cd frontend
   npm start
   ```

7. Visit `http://localhost:3000` in your browser to view the application.

## Usage
Orgobot is designed to help users:
- Learn about organ donation.
- Understand eligibility requirements and processes.
- Register as an organ donor through the app.
- Interact with a conversational AI bot for common organ donation-related questions.

## Key Modules
- **Chatbot**: The chatbot interacts with users and answers their queries, providing relevant information based on user input.
- **Donor Registration**: Facilitates user registration with form fields validated in real-time, ensuring data accuracy.
- **Dashboard**: Displays personal donor data, eligibility status, and history of interactions with the chatbot.
- **Accessibility Features**: Built-in support for screen readers and WCAG-compliant design to ensure usability for all.

## Future Enhancements
- **Multilingual Support**: Enable chatbot interactions in multiple languages to cater to a broader audience.
- **Advanced AI Integration**: Fine-tune the AI model with more domain-specific data to improve the chatbot's accuracy and contextual understanding.
- **Data Visualization**: Add visual analytics for registered donors and successful organ donations.
- **Mobile App**: Develop a mobile application for greater accessibility.

## Contributing
We welcome contributions from developers and AI enthusiasts! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit the changes (`git commit -m 'Add feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any queries or issues, please reach out to the project maintainer at samruddhip2010@gmail.com.

