# Installation

## Requirements

  - An up-to-date version of Chrome, or Chrome-like browser :material-information-outline:{ title='Version 116 or newer, your mileage may vary' }
  - A decent graphics card :material-information-outline:{ title='At the very least, 2GB free VRAM depending on model size' }

## Install

### From the Chrome Web Store

  1. [Add the extension here](https://chromewebstore.google.com/detail/subtitle-anything/ipfbhnkkjbafekefiifigffaelgffaed)

  2. [Pin the extension to the toolbar](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#pin_the_extension)

### From the GitHub ZIP release

  1. [Download the release ZIP file](https://github.com/ae9is/subtitle-anything/releases) and unzip it.

  2. [Follow these instructions to load the extension in Chrome](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked)

  3. [Pin the extension to the toolbar](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#pin_the_extension)

On Linux, WebGPU support is experimental. You may need to enable some of these browser flags (at chrome://flags):

  - WebGPU
  - Skia Graphite
  - Vulkan
  - Temporarily unexpire M130 flags (for Vulkan)

## Troubleshooting

  - Enable graphics acceleration under chrome://settings/system
  - Make sure you're using a recent version of Chrome (116+)
  - Check if your graphics card can run [Whisper](https://github.com/openai/whisper/), and that it's powerful enough to transcribe short audio snippets in a couple seconds

  Please understand that the tech behind Subtitle Anything (running machine learning models in the browser) is a work in progress, and your mileage may vary. Good luck, and feel free to share any issues you have!

###
