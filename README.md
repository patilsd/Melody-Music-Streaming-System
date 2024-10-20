🎵 Melody Music App<br/>
Melody is a simple and interactive music player built using HTML, CSS, and JavaScript. <br/>
The app provides an elegant interface to browse and play your favorite songs. <br/>
Instead of using APIs, the app uses a local JSON file to store and manage song data.<br/>

📝 Features:<br/>
🎶 Play, Pause, and Skip: Users can play, pause, and skip through songs.<br/>
🎵 Song Information Display: Displays song title, artist, and album artwork.<br/>
🔄 Repeat and Shuffle: Options to repeat the current song or shuffle the playlist.<br/>
📜 Dynamic Song List: All song data is stored and loaded from a local songs.json file.<br/>
📊 Progress Bar: Visual representation of the song's progress and time duration.<br/>
🔊 Volume Control: Adjust the volume or mute the sound.<br/>
📱 Responsive Design: The app is fully responsive and looks great on all screen sizes.<br/>

📁 Project Structure:
The project is organized as follows:
Melody/
│
├── index.html            
├── styles.css            
├── script.js             
├── songs.json           
├── songs/               
└── README.md            

📜 Song Data (songs.json)<br/>
The songs.json file contains the list of songs available in the app. Each song object includes the following attributes:<br/>

[
  {
    "title": "Death Bed",
    "artist": "Powfu",
    "artwork": "https://samplesongs.netlify.app/album-arts/death-bed.jpg",
    "url": "https://samplesongs.netlify.app/Death%20Bed.mp3",
    "id": "1",
    "category": "New"
  },
  {
    "title": "Bad Liar",
    
    "artist": "Imagine Dragons",
    "artwork": "https://samplesongs.netlify.app/album-arts/bad-liar.jpg",
    "url": "https://samplesongs.netlify.app/Bad%20Liar.mp3",
    "id": "2",
    "category": "New"
  },
  {
    "title": "Faded",
    "artist": "Alan Walker",
    "artwork": "https://samplesongs.netlify.app/album-arts/faded.jpg",
    "url": "https://samplesongs.netlify.app/Faded.mp3",
    "id": "3",
    "category": "New"
  }
]

🔧 Technologies Used<br/>
HTML: Markup for structuring the app.<br/>
CSS: Styling the app layout and appearance<br/>
JavaScript: Implementing app functionality such as song controls and interactions.<br/>
JSON: Storing and managing song details.<br/>

📚 How It Works<br/>
Loading Songs: The song data is loaded from the songs.json file using JavaScript's fetch method or directly from the file.<br/>
Creating Playlist: Songs are dynamically added to the playlist based on the JSON data.<br/>
Playing Songs: Users can select any song to play, with options to play, pause, and skip.<br/>
Updating UI: The app's interface, including song information and progress bar, is updated in real-time as the song plays.<br/>

💡 Future Enhancements<br/>
🎛️ Add more controls such as an equalizer.<br/>
📝 Allow users to create custom playlists.<br/>
🔄 Implement song search and filter options.<br/>
🌐 Integrate with a backend API for song data (optional).<br/>

🤝 Contributing<br/>
Contributions are welcome! Feel free to open an issue or submit a pull request to improve the app.<br/>

Fork the project.<br/>
Create your feature branch: git checkout -b feature/new-feature<br/>
Commit your changes: git commit -m 'Add new feature'<br/>
Push to the branch: git push origin feature/new-feature<br/>
Open a pull request.

