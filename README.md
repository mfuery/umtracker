# django-speech-to-text
A small API for speech to text made in Django.

Requirements:
  - SpeechRecognition 3.6.5
  - PocketSphinx
  - Requests
  - Django

## Dev setup

```commandline
brew install swig
mkvirtualenv umtracker
pip install -r requirements.txt

```

Test if it works
```commandline
scripts/auto_transcribe.py
```
