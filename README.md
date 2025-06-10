Eventro: AI-Powered Event Planning & Organizer Booking

About

Eventro is a comprehensive platform built with HTML, CSS, JavaScript, and Node.js that helps customers book professional Event Organizers for Weddings, Birthdays, and Business Events.

It features an integrated AI Assistant that offers:

* Outfit Suggestions: AI analyzes images to recommend suitable attire.
* AI-Generated Images:Create custom images for events or outfits.
* Event Planning: Get smart assistance for planning and organizing.
* Documentation: Generate `.docx` documents of event plans or chat summaries.

Getting Started

1.  Install dependencies:`npm install express multer openai docx dotenv`
2.  Create a `.env` file in the root directory and add your OpenAI API key:
    ```
    OPENAI_API_KEY=your_openai_api_key_here
    ```
3.  Ensure you have a `public` folder containing your HTML/CSS/JS, an `uploads` folder for temporary image storage, and a `public/downloads`folder where generated `.docx` documents will be saved.
4.  Run the application: `node server.js`

Features

* Book event organizers for various occasions.
* AI-powered outfit recommendations from image analysis.
* Generate creative images with AI.
* Receive AI assistance for event planning.
* Download event summaries and plans as `.docx` documents.

Technologies

* HTML, CSS, JavaScript
* Node.js, Express.js
* OpenAI API (GPT-4o, DALL·E 3)
* Multer, docx, dotenv
