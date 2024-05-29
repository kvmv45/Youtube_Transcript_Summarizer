# youtube_transcript_summarizer
YouTube Transcript to Detailed Notes Converter This Streamlit app extracts transcripts from YouTube videos and summarizes them into concise points using Google Gemini Pro. Ideal for quickly understanding key points without watching the full video.

**Features**
Transcript Extraction: Fetches the transcript of a YouTube video.
Summarization: Uses Google Gemini Pro to create a point-form summary.
User Interface: Built with Streamlit for a simple, interactive experience.

**How It Works**
Input YouTube Link: Enter the video URL.
Fetch Transcript: Extracts the video’s transcript using youtube_transcript_api.
Generate Summary: Summarizes the transcript using Google Gemini Pro.
Display Summary: Shows the summary on the app interface.

**Getting Started
Prerequisites**
Python 3.7+
Streamlit
youtube_transcript_api
python-dotenv
google-generativeai


**Example**
Input: Provide the YouTube video link.
Thumbnail: Confirm by viewing the video thumbnail.
Summary: Click "Get Detailed Notes" to generate and view the summary.
