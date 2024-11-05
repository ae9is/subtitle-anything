# Usage

## Run

1. Click the toolbar button to start subtitling a tab that's playing audio.

2. Click the toolbar button again in any tab to stop.

!!! note
    The first time you run the extension at each quality setting, it'll take a few seconds extra to download and load the machine learning model.

!!! warning
    If you're having issues, [follow these instructions to reload the extension](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#reload). It's a quick and easy way to fix Chrome tabs not capturing, AI model errors, etc.

!!! note
    You can also check the extension's logs by clicking on the "service worker" link in the same card that lets you reload the extension.

## Options

- Right click the toolbar button to navigate to the extension Options page.

### Language

If a specific language is selected to transcribe, subtitles will be in that language's native script.

If "automatically detect" is selected, the model will take a little longer to load. It also may struggle with bilingual speakers switching between languages quickly!

### Task

- Transcribe: Live caption the audio in the original language
- Translate: Create English only subtitles for the audio

### Model

The tool uses [Whisper](https://github.com/openai/whisper) to transcribe and translate audio.

For the best results use the biggest model your GPU has memory for, and can run quick enough to keep the live subtitles up to date.

From fastest (worst) to best (slowest): tiny < base < small.

###
