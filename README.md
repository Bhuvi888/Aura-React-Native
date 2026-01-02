# Aura 🎨

**Where Creativity Meets Innovation.**

Aura is a premier video-sharing platform built with **React Native** and **Expo**, designed to provide a seamless and immersive experience for creators and explorers alike. Whether you're here to discover endless possibilities or share your own journey of limitless exploration, Aura is your canvas.

## 🌟 Features

- **Seamless Authentication**: Secure and easy sign-up/sign-in using email credentials via **Appwrite**.
- **Immersive Video Feed**: Browse a curated stream of high-quality creative content.
- **Create & Share**: Upload your own videos with custom thumbnails and "AI Prompts" to describe your vision.
- **Smart Search**: Quickly find the content you love with robust search functionality.
- **Personalized Profiles**: Manage your uploaded content and view your profile details.
- **Cross-Platform**: Optimized for both **Android** and **iOS** devices.
- **Modern UI/UX**: Built with **NativeWind** (Tailwind CSS) for a sleek, responsive, and beautiful interface.

## 🛠 Tech Stack

- **Frontend**: React Native, Expo Router
- **Styling**: NativeWind (Tailwind CSS)
- **Backend / Database**: Appwrite
- **State Management**: React Context API
- **Assets**: Expo Image Picker, Expo Video

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS recommended)
- [Git](https://git-scm.com/)
- [Expo Go](https://expo.dev/client) app on your mobile device (or an emulator).

### Installation

1.  **Clone the repository**

    ```bash
    git clone <repository-url>
    cd Aura-React-Native
    ```

2.  **Install dependencies**

    ```bash
    npm install
    ```

### Running the App

Start the development server:

```bash
npx expo start
```

In the terminal output, you'll see a QR code.

- **Mobile**: Scan the QR code with the **Expo Go** app (Android) or Camera app (iOS).
- **Emulator**: Press `a` for Android or `i` for iOS simulator.

## ⚙️ Configuration

The project uses **Appwrite** for backend services. The configuration is located in `lib/appwrite.js`.

> **Note**: The current configuration points to a demo/development environment. To use your own backend:

1.  Set up a new project on [Appwrite Cloud](https://cloud.appwrite.io/).
2.  Create the necessary Database, Collections, and Storage Buckets.
3.  Update the `config` object in `lib/appwrite.js` with your own endpoint, project ID, and collection IDs.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is licensed under the MIT License.
