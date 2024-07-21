Youtube Video Transcribe Summarizer LLM App With Google Gemini Pro

This Streamlit app allows users to input a YouTube video URL, extract the transcript of the video, and generate a summarized version of the transcript using Google Gemini Pro. The summary is provided 
in a concise format, highlighting the key points within a 250-word limit.

Features
YouTube Transcript Extraction: Utilizes the YouTube Transcript API to fetch the transcript of the video.
Summarization with Google Gemini Pro: Integrates with Google Gemini Pro to generate a detailed summary of the video transcript.
User Interface: A simple and intuitive interface built with Streamlit for easy interaction.

How It Works

Environment Setup:
Load environment variables from a .env file using dotenv.
Configure Google Gemini Pro with an API key.

Transcript Extraction:
The extract_transcript_details function takes a YouTube video URL, extracts the video ID, and retrieves the transcript using the YouTube Transcript API.
The transcript is concatenated into a single string for processing.

Content Summarization:
The generate_gemini_content function sends the transcript text to Google Gemini Pro with a prompt for summarization.
The generated summary is then displayed in the app.

User Interaction:
Users input the YouTube video URL into a text field.
Upon clicking the "Get Detailed Notes" button, the app processes the URL, extracts the transcript, and displays the summary.

                                                                    


