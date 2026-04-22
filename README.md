# PixelPulse

Welcome to **PixelPulse**, a real-time pixel art collaboration platform that empowers creative coders and artists to build pixel masterpieces together, anywhere in the world.

---

## Overview

PixelPulse is designed as an intuitive, live canvas where multiple users can simultaneously draw pixel art, chat, and share creative ideas. Whether you're creating sprites for games, designing icons, or just having fun with pixels, PixelPulse brings your creative community together in real time.

## Features

- 🔴 Real-time multi-user pixel drawing
- 🎨 Color palette customization
- 💬 Integrated chat for instant communication
- 📁 Save and export your pixel art
- 🌐 User profiles with customizable avatars
- 📊 Live activity indicators and user cursors

## Tech Stack

- **Frontend:** React, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js, Socket.IO
- **Database:** MongoDB
- **Authentication:** JWT
- **Deployment:** Docker, Heroku

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/dark-vifv/pixelpulse.git
   cd pixelpulse
   ```

2. Install dependencies for frontend and backend:

   ```bash
   cd client && npm install
   cd ../server && npm install
   ```

3. Create a `.env` file in the `server` directory with the following variables:

   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000
   ```

4. Run the development servers:

   ```bash
   # In one terminal window
   cd server && npm run dev

   # In another terminal window
   cd client && npm start
   ```

## Usage

- Open [http://localhost:3000](http://localhost:3000) in your browser.
- Register or log in to your account.
- Join or create a new pixel canvas.
- Collaborate in real-time with other artists.
- Use the chat to communicate and share ideas.
- Save your artwork or export it as PNG.

## Screenshots

![PixelPulse Screenshot 1](https://via.placeholder.com/800x400?text=PixelPulse+Canvas+View)

![PixelPulse Screenshot 2](https://via.placeholder.com/800x400?text=PixelPulse+Chat+Interface)

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository on GitHub.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request on GitHub.

For any issues, please open an issue on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/dark-vifv/pixelpulse/blob/main/LICENSE) file for details.

---

## Author

Developed and maintained by [dark-vifv](https://github.com/dark-vifv).

---

Thank you for checking out PixelPulse! Let's make pixel art collaborative and fun.
