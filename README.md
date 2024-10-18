# Skyview 🌌

Skyview is an AI-powered photo-sharing platform where users can upload and view beautiful photos of the sky. The application uses Generative AI to automatically generate creative titles and descriptions for each uploaded image, making photo sharing even more engaging! 🚀

## Live Demo 🌐

Check out the live version of the Skyview application [here](https://skyviewfinal-40868696838.us-east1.run.app)!
Sign up using your email and password.

## Features ✨

- 🌠 **Photo Upload**: Users can upload their sky photos, which are stored both locally and in a Google Cloud Storage bucket.
- 🤖 **AI-Generated Titles & Descriptions**: Upon uploading a photo, the Generative AI API generates a creative title and description based on the image.
- 🖼️ **Image Display**: The home page showcases a gallery of uploaded photos. Clicking on any photo opens a detailed view with its title and description.
- 🔐 **Firebase Authentication**: User login and signup functionality powered by Firebase to ensure secure access.
- 🔄 **Syncing with Google Cloud Storage**: The app ensures photos and metadata stay synchronized between local storage and the cloud, including deletions.
- 💻 **Cloud Deployment**: Hosted on Google Cloud Run for scalable access from anywhere!

## How It Works ⚙️

1. **User Authentication**: Users sign up or log in using Firebase Authentication.
2. **Upload Photos**: Photos are uploaded, and titles and descriptions are generated automatically using the Generative AI API.
3. **Cloud Storage**: The photos and their metadata are stored in Google Cloud Storage for easy access.
4. **View Photos**: Users can view their uploaded photos on the home page. Each image is clickable to reveal the title and description on a new page.

## Installation 🛠️

To run the Skyview project locally or in Google Cloud Shell, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/Sushithjhenkar/SKyview.git
   cd Skyview
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
3. Set up Firebase:
- Go to the [Firebase Console](https://firebase.google.com/).
- Set up authentication and get your Firebase config.
- Add your Firebase credentials to the project.

4. Configure Google Cloud Storage:
- Set up a Google Cloud Storage bucket.
- Add the necessary credentials to access the bucket.

5. Run the application:
    ```BASH
    python main.py

## Technologies Used 🛠️
- Python 🐍
- Flask 🌐
- Google Cloud Storage ☁️
- Generative AI API 🤖
- Firebase Authentication 🔐

## Contributing 🤝
We welcome contributions! Feel free to fork the repo and submit pull requests with new features or improvements.

## License 📄
This project is licensed under the MIT License.