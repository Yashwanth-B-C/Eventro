# Eventro: Your AI-Powered Event Planning & Organizer Booking Platform

## About the Project

Eventro is a comprehensive and innovative event management platform designed to simplify the entire event planning process. It connects customers with professional Event Organizers for a variety of occasions, including weddings, birthdays, and corporate events.

What sets Eventro apart is its integrated AI Assistant, which provides intelligent support throughout the event journey. This cutting-edge feature transforms the user experience by offering:

  * **Outfit Suggestions:** Get personalized outfit recommendations by analyzing a person's personality and appearance from an uploaded image.
  * **AI-Generated Images:** Generate creative and inspirational images for your event or outfits using DALL·E.
  * **Event Planning Assistance:** Receive smart suggestions and guidance for planning your event efficiently.
  * **Automated Documentation:** Generate organized documents of your planned events or chat summaries in `.docx` format.

Eventro aims to be your one-stop solution for booking organizers and receiving cutting-edge AI assistance, making event planning seamless and enjoyable.

## Features

  * **Organizer Booking:** Easy submission forms for customers to book event organizers.
  * **Contact Form:** A simple contact form for customer inquiries.
  * **AI Chat Assistant:** A powerful assistant providing various services:
      * Outfit Analysis & Suggestions: Upload an image and get AI-powered outfit recommendations.
      * Image Generation: Create visual content based on text prompts.
      * Event Planning & Summarization: Get assistance with planning and generate event summaries or documentation.
  * **Dynamic Content:** Uses Node.js to handle form submissions and serve dynamic AI responses.
  * **Static File Serving:** Serves static HTML, CSS, and JavaScript files for a responsive user interface.

## Technologies Used

  * **Frontend:** HTML, CSS, JavaScript
  * **Backend:** Node.js, Express.js
  * **AI Integration:** OpenAI API (GPT-4o, DALL·E 3)
  * **File Handling:** `multer`, Node.js `fs` module
  * **Document Generation:** `docx`
  * **Environment Variables:** `dotenv`

## Getting Started

To get Eventro up and running on your local machine, follow these simple steps:

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/en/) installed on your system.

### Installation

1.  **Install dependencies:**
    Eventro relies on several Node.js packages. Install them using `npm`:

    ```bash
    npm install express multer openai docx dotenv
    ```

2.  **Create a `.env` file:**
    In the root directory of your project (where `server.js` is located), create a file named `.env`. This file will securely store your OpenAI API Key.

    ```env
    OPENAI_API_KEY=your_openai_api_key_here
    ```

    Replace `your_openai_api_key_here` with your actual API key from the OpenAI Platform.

3.  **Create necessary directories:**
    Ensure you have the following directories in your project root:

      * `public/`: Contains your static HTML, CSS, and JavaScript files.
      * `uploads/`: Used by `multer` to temporarily store uploaded images.
      * `public/downloads/`: Where all the generated `.docx` documents will be stored.

### Running the Application

Once you've completed the installation and setup, you can start the Eventro server:

```bash
node server.js
```

The server will typically run on `http://localhost:3000` (or the port specified in your `.env` file). Open this URL in your web browser to access Eventro.

## AI Features in Action

### 1\. Document Generation

**Prompt:** Create an event plan document for a corporate annual day function including venue, catering, schedule, and theme.

*Example of the generated document content.*

![image](https://github.com/user-attachments/assets/04aea513-9520-402e-95bb-f488a6eebe7d)

![image](https://github.com/user-attachments/assets/9a72f380-3f5d-4878-bbc3-f4cfb871b66a)

### 2\. Image Generation

**Prompt:** Generate an image of Birthday Cake.

*The AI-generated birthday cake image.*

![image](https://github.com/user-attachments/assets/95f9b1b3-6633-453f-bde6-76e0d204aba0)

### 3\. Outfit Suggestions

**Prompt:** The best outfit for a get-together party.

*The AI provides creative outfit recommendations based on a text prompt.*

![image](https://github.com/user-attachments/assets/1daba35d-f9eb-4cb8-851c-0500226776f3)

![image](https://github.com/user-attachments/assets/bc7179b9-cd01-478a-ad23-9afdcf78e757)

![image](https://github.com/user-attachments/assets/a0f41bc1-a354-47dd-8ad7-f868672e826b)

 ![image](https://github.com/user-attachments/assets/a4bd2670-bd67-4a5e-8508-ef46eb88c7df)

### 4\. Application Pages

*The Eventro homepage.*

*An example of the event booking form.*

![image](https://github.com/user-attachments/assets/7cad9654-df4d-4e41-917e-f06768e25a47)

![image](https://github.com/user-attachments/assets/3b15312d-1e52-4342-ade0-931cf2877db4)

![image](https://github.com/user-attachments/assets/31518d54-f4ae-4a6c-a312-4909da4b056f)

### Home Page

![image](https://github.com/user-attachments/assets/60c74355-6b48-4450-99a9-c6bbcfe906ef)

## Contributing

Contributions are welcome\! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.
