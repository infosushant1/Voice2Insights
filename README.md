This Flask app allows you to upload an audio file, automatically:

Converts it to .wav (if needed),

Transcribes it to text using OpenAI’s Whisper model,

Extracts structured information (Name, Region, Language, Occupation, Interest) using Mistral AI (a text-generation model),

Displays the transcription and extracted info in a webpage, and

Allows saving the extracted info into a CSV file (customer_data.csv).

So overall, it’s a Voice-to-Insights Pipeline using Speech-to-Text + NLP extraction + Flask Web UI.
