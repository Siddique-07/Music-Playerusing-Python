# Music-Playerusing-Python

Music player application built using Python Tkinter library. It allows users to play, pause, stop, rewind music tracks, adjust volume, and manage playlists.

## Python Concepts Used:

- **GUI Development:** Developed a graphical user interface (GUI) using Tkinter library to create interactive elements such as buttons, labels, and scales.

- **File Handling:** Utilized file handling to open, read, and manage music files from the user's system, allowing users to browse and select music files to add to the playlist.

- **Multithreading:** Employed threading to run concurrent tasks, such as updating the current time display while playing music, ensuring smooth performance without freezing the GUI.

- **Exception Handling:** Implemented exception handling to handle potential errors, such as file not found or invalid file format, providing user-friendly error messages for better user experience.

- **Audio Processing:** Used the mutagen and pygame libraries to process audio files (e.g., MP3 files), retrieve metadata, and control playback functions like play, pause, stop, and rewind.

## Features:

- **Play Controls:** Play, pause, stop, and rewind music tracks with intuitive buttons.

- **Volume Control:** Adjust the volume level using a slider scale, with options to mute/unmute the audio.

- **Playlist Management:** Browse and add music files to the playlist, view the total length of each track, and select tracks for playback.

- **Status Bar:** Display real-time status messages, such as current playing track and playback status, in the status bar at the bottom of the window.

## How to Use:

1. **Installation:**
   - Ensure you have Python installed on your system.
   - Install required libraries using `pip install mutagen pygame ttkthemes`.

2. **Running the Music Player:**
   - Execute the `music_player.py` file using Python.
   - Use the "File" menu to open music files and add them to the playlist.
   - Control playback using the buttons provided (play, pause, stop, rewind).
   - Adjust volume using the volume slider scale.

3. **Managing Playlist:**
   - Use the "+ Add" button to browse and add music files to the playlist.
   - Select tracks from the playlist to play, pause, or stop.

## Skills Demonstrated:

- **User Interface Design:** Designed an intuitive user interface with buttons, labels, and scales for seamless interaction with the music player application.

- **Event Handling:** Implemented event handling to capture user actions (e.g., button clicks, menu selections) and trigger appropriate responses (e.g., play music, adjust volume).

- **Concurrent Programming:** Used multithreading to handle concurrent tasks, ensuring responsiveness and smooth playback while performing other operations.

- **Error Handling:** Incorporated error handling mechanisms to gracefully handle exceptions and provide informative error messages to users in case of failures.

## Credits:
- **Developer:** Siddique A
