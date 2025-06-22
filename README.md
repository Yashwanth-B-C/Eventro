________________________________________
Eventro: Your AI-Powered Event Planning & Organizer Booking Platform
________________________________________
About Eventro

Eventro is a comprehensive and innovative event management platform designed to simplify the entire event planning process for customers. Built with a modern tech stack including HTML, CSS, JavaScript, and Node.js, Eventro connects customers with professional Event Organizers for various occasions, including Weddings, Birthdays, and Business Events.
What sets Eventro apart is its integrated AI Assistant, which provides intelligent support throughout your event journey:
•	Outfit Suggestions: Get personalized outfit recommendations by analyzing a person's personality and appearance from an uploaded image.
•	AI-Generated Images: Generate creative and inspirational images for your event or outfits using DALL·E.
•	Event Planning Assistance: Receive smart suggestions and guidance for planning your event efficiently.
•	Automated Documentation: Generate organized documents of your planned events or chat summaries in .docx format.
Eventro aims to be your one-stop solution for booking organizers and receiving cutting-edge AI assistance, making event planning seamless and enjoyable.
________________________________________
Getting Started
To get Eventro up and running on your local machine, follow these simple steps:
Prerequisites
Make sure you have Node.js installed on your system.
Installation
1.	Install dependencies:
Eventro relies on several Node.js packages. Install them using npm:
Bash
npm install express multer openai docx dotenv
2.	Create a .env file:
In the root directory of your project (where server.js is located), create a file named .env. This file will store your OpenAI API Key securely.
OPENAI_API_KEY=your_openai_api_key_here
Replace your_openai_api_key_here with your actual API key obtained from the OpenAI Platform.
3.	Create necessary directories:
Ensure you have the following directories in your project root:
o	public: This directory should contain your static HTML, CSS, and JavaScript files (index.html, confirmation.html, booking-success.html, chat.html, etc.).
o	uploads: This folder is used by multer to temporarily store uploaded images.
o	public/downloads: This is where all the generated .docx documents will be stored and made available for download. Make sure this directory exists within your public folder. If it doesn't, the server will attempt to create it on startup, but it's good practice to ensure it's there.
Running the Application
Once you've completed the installation and setup, you can start the Eventro server:
Bash
node server.js
The server will typically run on http://localhost:3000 (or the port specified in your .env file or by your environment). Open this URL in your web browser to access Eventro.
________________________________________
Features
•	Organizer Booking: Easy submission forms for customers to book event organizers.
•	Contact Form: A simple contact form for customer inquiries.
•	AI Chat Assistant: 
•	Outfit Analysis & Suggestions: Upload an image and get AI-powered outfit recommendations.
•	Image Generation: Create visual content based on text prompts.
•	Event Planning & Summarization: Get assistance with planning and generate event summaries or documentation.
•	Dynamic Content: Uses Node.js to handle form submissions and serve dynamic AI responses.
•	Static File Serving: Serves static HTML, CSS, and JavaScript files for a responsive user interface.
________________________________________
Technologies Used
•	Frontend: HTML, CSS, JavaScript
•	Backend: Node.js, Express.js
•	AI Integration: OpenAI API (GPT-4o, DALL·E 3)
•	File Handling: Multer, Node.js fs module
•	Document Generation: docx
•	Environment Variables: dotenv
________________________________________
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.
________________________________________

Project Name: Eventro

AI Features 

1.	Document Generation 

Prompt: Create an event plan document for a corporate annual day function including venue, catering, schedule, and theme.
Output: 
![image](https://github.com/user-attachments/assets/04aea513-9520-402e-95bb-f488a6eebe7d)
 
Downloaded Document
![image](https://github.com/user-attachments/assets/9a72f380-3f5d-4878-bbc3-f4cfb871b66a)


2.	Image Generation
Prompt: Generate an image of Birthday Cake
![image](https://github.com/user-attachments/assets/95f9b1b3-6633-453f-bde6-76e0d204aba0)


3.	Get Outfit Suggestions by Uploading an Image
Prompt: Generate outfit image
![image](https://github.com/user-attachments/assets/1daba35d-f9eb-4cb8-851c-0500226776f3)
![image](https://github.com/user-attachments/assets/bc7179b9-cd01-478a-ad23-9afdcf78e757)
![image](https://github.com/user-attachments/assets/a0f41bc1-a354-47dd-8ad7-f868672e826b)

 
4.	Prompt: The best outfit for a get-together party.
 ![image](https://github.com/user-attachments/assets/a4bd2670-bd67-4a5e-8508-ef46eb88c7df)


 Home Page
 ![image](https://github.com/user-attachments/assets/60c74355-6b48-4450-99a9-c6bbcfe906ef)



Events Booking Page
![image](https://github.com/user-attachments/assets/7cad9654-df4d-4e41-917e-f06768e25a47)
![image](https://github.com/user-attachments/assets/3b15312d-1e52-4342-ade0-931cf2877db4)
![image](https://github.com/user-attachments/assets/31518d54-f4ae-4a6c-a312-4909da4b056f)


