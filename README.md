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
Installation

**Clone the repository:**

git clone https://github.com/your-username/youtube-transcript-to-detailed-notes.git
cd youtube-transcript-to-detailed-notes
**Install the required packages:**

pip install -r requirements.txt
Create a .env file in the root directory with your Google API key:

GOOGLE_API_KEY=your_google_api_key
Usage
**Run the application:**

streamlit run app.py
Open your browser and navigate to http://localhost:8501.
Enter the YouTube video link and click "Get Detailed Notes" to see the summary.

**Example**
Input: Provide the YouTube video link.
Thumbnail: Confirm by viewing the video thumbnail.
Summary: Click "Get Detailed Notes" to generate and view the summary.
