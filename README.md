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

<img width="1294" height="802" alt="Screenshot 2025-06-10 140916" src="https://github.com/user-attachments/assets/dfd4ba1c-f7e1-4200-907f-5a31b757b1e9" />

<img width="1827" height="929" alt="Screenshot 2025-06-10 141022" src="https://github.com/user-attachments/assets/bb3c4736-5aaa-4d8c-9646-5376e3032a6d" />

<img width="1919" height="988" alt="Screenshot 2025-06-10 141119" src="https://github.com/user-attachments/assets/67d3a92f-a9d1-4c1b-a660-4896b13ed503" />

### 2\. Image Generation

**Prompt:** Generate an image of Birthday Cake.

*The AI-generated birthday cake image.*

<img width="523" height="608" alt="Screenshot 2025-06-10 150643" src="https://github.com/user-attachments/assets/b1147363-1774-464c-8b6f-021aa26cc085" />

### 3\. Outfit Suggestions

**Prompt:** The best outfit for a get-together party.

*The AI provides creative outfit recommendations based on a text prompt.*

<img width="525" height="589" alt="Screenshot 2025-06-10 152106" src="https://github.com/user-attachments/assets/11ee0453-48b4-4a5c-9e18-b1d9e0c82871" />

<img width="515" height="556" alt="Screenshot 2025-06-10 153223" src="https://github.com/user-attachments/assets/fdfd4bd0-5dfd-4851-8c9f-b981cb34546e" />

### 4\. Application Pages

*An example of the event booking form.*

<img width="1190" height="808" alt="Screenshot 2025-06-10 153829" src="https://github.com/user-attachments/assets/ed74b88d-7194-4b64-93ea-13d85b299f3f" />

<img width="1922" height="3947" alt="screencapture-localhost-3000-organizers-html-2025-08-12-17_57_58" src="https://github.com/user-attachments/assets/2115fdbd-9fec-46e5-85fb-23f57f8e50af" />

<img width="1190" height="808" alt="Screenshot 2025-06-10 153829" src="https://github.com/user-attachments/assets/85d19174-a6b4-4fd4-939d-7fc5d9a02a08" />

<img width="1208" height="682" alt="Screenshot 2025-06-10 153853" src="https://github.com/user-attachments/assets/e49ea583-48b6-426b-aa4e-9e7739a3652c" />

### Home Page

<img width="1922" height="5080" alt="screencapture-localhost-3000-2025-08-12-17_59_36" src="https://github.com/user-attachments/assets/9364fa79-bddb-4050-885c-c45b99fc5b2c" />

## Contributing

Contributions are welcome\! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.







