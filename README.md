# Online Quiz System - H.D. Jain College

A web-based quiz application designed for H.D. Jain College, Ara (Bhojpur) students to test their knowledge of computer applications. This system provides a simple, user-friendly interface for taking online quizzes with instant feedback and scoring.

## Features

- **Secure Login System**: Authentication system with username/password verification
- **Interactive Quiz Interface**: Clean and responsive design for better user experience
- **Real-time Progress Tracking**: Shows current question number and total questions
- **Instant Feedback**: Immediate scoring after each answer
- **Result Summary**: Displays final score upon quiz completion
- **Responsive Design**: Works well on both desktop and mobile devices


## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional)


### Usage

1. Access the application through your web browser
2. Login with the following credentials:
   - Username: Aman
   - Password: 0000
3. Click "Start Quiz" to begin
4. Answer each question by selecting one of the provided options
5. View your final score upon completion
6. Option to restart the quiz or logout

## Project Structure

```
├── index.html          # Main HTML file
├── styles             # Embedded in HTML
│   └── main.css      
└── scripts           # Embedded in HTML
    └── main.js       
```

## Features in Detail

### Quiz System
- 5 multiple-choice questions
- Computer applications focused content
- Automatic progression to next question
- Score tracking and final results display

### User Interface
- Clean, modern design
- Clear navigation
- Progress indicators
- Responsive buttons and inputs
- Error messaging for invalid login attempts

## Customization

The quiz can be easily customized by modifying the `questions` array in the JavaScript code. Each question object should follow this format:

```javascript
{
    question: "Your question text",
    options: ["Option 1", "Option 2", "Option 3", "Option 4"],
    correct: indexOfCorrectAnswer // 0-based index
}
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

##Note

This is in Development. More features like user registration, admin login... will be added later.

##Visit

[Click]
