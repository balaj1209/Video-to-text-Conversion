Video to Text Converter
Overview
The Video to Text Converter is a Python application that enables users to convert video and audio files into text. It leverages AssemblyAI for transcription and provides a graphical user interface (GUI) built with Tkinter. Users can convert video files to audio, transcribe the audio to text, and save the text to a Word document.

Features
Convert Video to Audio: Extracts audio from video files and saves it in WAV format.
Convert Audio to Text: Transcribes audio files (WAV and MP3) into text using AssemblyAI.
Save Text to Word: Allows users to save the transcribed text to a Word document (.docx).
User-Friendly Interface: Provides a simple GUI for selecting files, converting them, and saving the output.
Requirements
To run the application, you need the following Python packages:

assemblyai - For transcribing audio using AssemblyAI.
docx - For creating and saving Word documents.
moviepy - For handling video and audio files.
tkinter - For the graphical user interface.
You can install these packages using pip:

bash
Copy code
pip install assemblyai python-docx moviepy
Note: tkinter is included with the standard Python installation, so you likely don't need to install it separately.

Setup
API Key Configuration:

Replace 'd37006136c4b4ed6824f727ae9938020' with your own AssemblyAI API key in the aai.settings.api_key line of the script.
Run the Application:

Save the script to a file, e.g., video_to_text_converter.py.

Run the script using Python:

bash
Copy code
python video_to_text_converter.py
Usage
Open File:

Click on the "Open File" button to select a video file (for video to text conversion) or an audio file (for audio to text conversion).
Convert:

Choose the conversion type from the dropdown menu ("Video to Text" or "Audio to Text").
Click the "Convert" button to start the conversion process. The application will display the transcribed text and the time taken for the conversion.
Save to Word:

Click the "Save to Word" button to save the transcribed text to a Word document. A file dialog will open to choose the location and filename for the saved document.
Exit:

Click the "Exit" button to close the application.
Troubleshooting
No Audio Track: If you receive an error indicating that the video file does not contain an audio track, ensure the video file has an audio component.
File Format Issues: Ensure the selected files are in the correct format (MP4, AVI, MOV for video; WAV, MP3 for audio).
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
AssemblyAI: For providing the transcription service.
MoviePy: For handling video and audio processing.
Python and Tkinter: For the application development framework.
Contact
For any questions or issues, please contact [BALAJI B] at [balaji7102000@gmail.com].

