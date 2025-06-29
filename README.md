## 🌀 MediaMeld - Auto Reel Generator 🎞️

A Flask-based web application that allows users to upload images and a description, automatically converting them into short vertical video reels with background audio generated from the description.

## 🚀 Features

- 🖼️ Upload multiple images
- 📝 Add a textual description
- 🔊 Automatic text-to-speech conversion of the description
- 🎬 Reel creation using images and audio
- 🗂️ Gallery view for all generated reels


## ⚙️ Tech Stack

- Python 🐍
- Flask 🌐
- FFmpeg 🎥
- Text-to-Speech (via `text_to_speech_file`) 🗣️

## 🛠️ Setup Instructions

### Prerequisites

- Python 3.x
- FFmpeg installed and added to PATH
- Install required Python packages (Flask, etc.)

### Installation

```bash
git clone https://github.com/saloniilad/MediaMeld.git
cd MediaMeld
pip install -r requirements.txt
python main.py
python generate_process.py (in different terminal)
```


## 🧪 Usage
- Go to /create
- Upload multiple .jpg, .jpeg, or .png images
- Add a description
- Visit /gallery to see the auto-generated reels

## 📁 File Naming Conventions
- desc.txt: Stores the user-provided description
- input.txt: Generated list of images with timestamps for FFmpeg
- audio.mp3: Output of text-to-speech
- reel.mp4: Final reel stored in static/reels/

## 💡 Future Improvements
- Support for background music
- Voice style selection (male/female)
- Reel customization (transitions, image duration)
- Authentication and user-specific galleries

## 📸 Sample Demo
![index page](static\index.png)
![create page](static\create.png)
![create page](static\gallery.png)




