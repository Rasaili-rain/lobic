# ![](frontend/public/navbar/LobicLogo.svg) Lobic - Interactive Music Streaming Platform

Lobic is an interactive music streaming application designed to transform how people experience music by combining real-time social engagement with personalized music discovery.

## Features
- **Real-Time Listening Rooms:** Stream music together and chat live.
- **Personalized Recommendations:** Discover music tailored to your taste.
- **Seamless Playback and Search:** Find and play music effortlessly.
- **Playlists:** Create combined and solo playlists.
- **Music Lists:** Access recently played, liked songs, top tracks, trending, and a dummy featured list.
- **Signup with OTP Verification:** Secure signup process with OTP verification via email.

## Tech Stack
- **Frontend:** Node.js, React
- **Backend:** Rust, Axum
- **Database:** SQLite

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lobic.git
   cd lobic
   ```
2. Backend Setup:
   ```bash
   cd backend
   ```
   Ensure Rust ,Cargo and Sqlite are properly installed, then run:
   ```bash
   cargo run
   ```

3. Load Music from your local storage:
   ```bash
    
    #On a seperate terminal
    cd backend
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows
    pip install -r requirements.txt
    python gui_music_saver.py

   ```
   >⚠️**Replace `<otp-provider-email>` and `<otp-provider-email-app,pwd>` in .env with your actual credentials.**

   Ensure Rust ,Cargo and Sqlite are properly installed, then run:
   ```bash
   cargo run
   ```

4. Frontend Setup (in a separate terminal):
   ```bash
   cd ../frontend
   ```
	>⚠️**Replace `server-ip`  in `frontend/src/const.ts` with your actual credentials.
		Make sure Node.js is installed. Then run

	```
	npm i
	npm start
   ```
  Go to the URL with the network tag, and viola!

## Contributing
Contributions are welcome! Feel free to fork the project, open issues, or submit pull requests.


## Acknowledgements
This project is done as a semester project by the following members:
- [Rasaili-rain](https://github.com/Rasaili-rain)  
- [fy-st0rm](https://github.com/fy-st0rm)
- [manishbhattarai8](https://github.com/manishbhattarai8)
- [Samki-bit](https://github.com/Samki-bit)
- [optus-56](https://github.com/optus-56)

This is a cleaned-up fork. Find the original codebases and commits in the respective repositories:
- Frontend: [Frontend Original Repository](https://github.com/fy-st0rm/Lobic)
- Backend: [Backend Original Repository](https://github.com/Rasaili-rain/Lobic-backend)

### License
	MIT