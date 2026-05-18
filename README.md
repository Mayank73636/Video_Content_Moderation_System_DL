# Video_Content_Moderation_System_DL


## What It Does
Takes a video 
→ Checks each frame for bad content 
→ Checks audio for bad words 
→ Gives you a report

## How It Works
1. Extract frames from video
2. Check each frame using AlexNet (AI model)
3. Extract audio and convert to text using Whisper
4. Check text for bad words
5. Generate report with results
6. Show everything on a web dashboard

## Installation
```bash
pip install -r requirements.txt
```

## Usage
```bash
jupyter notebook VCMS.ipynb
```

## Technologies Used
- Python
- PyTorch (AlexNet)
- OpenCV (video processing)
- Whisper (speech to text)
- Streamlit (web dashboard)
- FFmpeg (audio extraction)

## Output
- CSV file with moderation results
- Text file with transcript
- Web dashboard showing results

## Team Members
- Mayank
- Lalbiakhlua
  
