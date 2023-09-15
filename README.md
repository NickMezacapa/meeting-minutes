# Automated Meeting Minutes Generator

## Description
This project is a powerful tool that harnesses the of OpenAI's Whisper ASR and GPT-4 models to automate the process of generating meeting minutes from audio recordings, as well as text summary and key point extraction.

This Python-based application transcribes audio, provides summaries, extracts key points and action items, and performs sentiment analysis.

## Requirements
You should have a basic understanding of Python and an OpenAI API key. You can get an API key [here](https://platform.openai.com/account/api-keys). This project was built using Python 3.11.5.

Create a virtual environment and install the requirements:

```bash
python -m venv venv
source venv/bin/activate
pip install openai
pip install python-docx
pip install python-dotenv
```

Add your OpenAI API key to the `.env` file.

## Usage
1. Transcribe Audio with Whisper ASR. Refer to `transcription.py`
2. Summarize and Analyze Transcript with GPT-3. Refer to `sentiment_analysis.py`
3. Extract Key Points and Action Items. Refer to `sentiment_analysis.py`
4. Generate Meeting Minutes. Refer to `meeting_minutes.py`
5. Save Meeting Minutes as a Word Document. Refer to `save_as_docx.py`

## Optimization and Further Considerations
- [ ] Improve the accuracy of the Whisper ASR model by training it on a custom dataset.
- [ ] Experiment with prompt engineering to enhance model performance.
- [ ] Customize the system messages to provide more context to the GPT-4 model for better results.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Refereces
- [OpenAI API](https://beta.openai.com/)


