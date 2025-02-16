# 🎵 JavaFX Music Player

A feature-rich music player built using **JavaFX**, supporting multiple audio formats, playlist management, and advanced sorting functionalities.

## 🚀 Features

-   🎶 **Multi-format Audio Support** – Supports WAV, MP3, and other common formats.
-   📂 **Playlist Management** – Create, edit, and save playlists with `.m3u` support.
-   🔍 **Advanced Sorting & Filtering** – Sort by title, album, artist, and duration.
-   🎛 **User-friendly UI** – Intuitive JavaFX-based interface for seamless navigation.
-   🔊 **Smooth Playback Control** – Play, pause, stop, and skip tracks effortlessly.

## 📸 Screenshots

![Music Player Screenshot](./Images/ss.png?raw=true)

## 🛠 Installation & Setup

### Prerequisites

-   **Java 11+**
-   **JavaFX SDK**
-   **Eclipse/IntelliJ IDEA** (Recommended)

### Steps to Run

```sh
1. Clone the repository:
   git clone https://github.com/yourusername/JavaFx-Music-Player.git
   cd JavaFx-Music-Player

2. Open the project in your preferred IDE (Eclipse/IntelliJ).

3. Ensure JavaFX libraries are correctly linked:
   - Download JavaFX SDK: https://openjfx.io
   - Configure JavaFX module path and VM options.

4. Run the application:
   - In your IDE, run: src/studiplayer/ui/Player.java
```

### 📂 Project Structure

```bash
JavaFx Music Player
├── audiofiles/             # Sample audio files
├── playlists/              # Saved playlists
├── src/
│   ├── icons/              # UI icons
│   ├── studiplayer/
│   │   ├── audio/          # Core audio handling classes
│   │   ├── ui/             # JavaFX UI components
│   │   ├── Player.java     # Main entry point for the application
│   │   ├── Song.java       # Song class to manage track metadata
│   │   ├── SongTable.java  # UI table for displaying songs
│   ├── test/               # Test files
│── test.m3u                # Sample playlist
```

### 📜 License

This project is open-source under the MIT License.

⭐ If you like this project, give it a star on GitHub!
