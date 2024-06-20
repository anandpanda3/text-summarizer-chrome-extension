   
   ![image](https://github.com/ayushichoudhary-19/WebSummarizer/assets/73214455/7387f4d8-cf64-498b-a797-a5cc8bc0cf17) 
   #  Web Summarizer Chrome Extension

A Chrome extension that allows you to summarize the content of web pages using the **Cohere.ai API**.

## 📦 Overview

This Chrome extension enables users to extract and summarize the content of the currently opened web page. It utilizes the Cohere.ai API to generate concise summaries of web page content. The summarized content is then displayed in a popup within the Chrome browser.


## 🦄 Features

- Summarize web page content.
- Display the summary in a popup.
- Simple and user-friendly interface.

## 💻 Technologies Used

- HTML
- CSS
- JavaScript
- Cohere.ai API
- Chrome Extension API


## What I Learned 🧠

Building this Chrome extension enhanced my understanding of:
- Chrome Extension Development.
- Integrating third-party APIs into browser extensions.
- User Interface design for browser-based tools.

## 💭 How can it be Improved? 

- Feedback Loop: Incorporate a feedback mechanism for users to report issues or suggest improvements.
- Customization: Allow users to customize summarization settings.

## 🚦Running the Project

To get started with the Web Summarizer Chrome Extension, follow these steps:

1. Open Google Chrome and navigate to `chrome://extensions/`.

2. Enable "Developer mode" in the top right corner.

3. Click on the "Load unpacked" button.

4. Select the directory where you cloned this repository.

5. The extension should now be installed and visible in your browser.
   

## 🖱️ Usage

1. Browse a web page you want to summarize.

2. Click the extension icon (the puzzle piece) in the top right corner of your Chrome browser.

3. Click on the 'WebSummarizer' extension. 

4. Click the "Summarize" button in the popup.

5. The summary of the web page content will be displayed in the popup.
   

## ⚙️ Configuration

Before using the extension, you must set your Cohere.ai API key in the `background.js` file. Replace `'YOUR_API_KEY'` with your actual API key:

```javascript
const apiKey = 'YOUR_API_KEY';
```

## 🙌 Acknowledgments

- [Cohere.ai](https://cohere.ai/) for providing the summarization API.
- [Chrome Extension Developer Documentation](https://developer.chrome.com/docs/extensions/mv3/getstarted/) for guidance on building Chrome extensions.
```
