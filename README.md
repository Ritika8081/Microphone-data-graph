![Microphone Data Visualization](https://asset.cloudinary.com/dnmebcuio/2c8b15a7eb63b49ba82c3eb8638fe095)
![Microphone Data Visualization](https://asset.cloudinary.com/dnmebcuio/d0486ce04aeebfc34c69b1c853bd8032)
![Microphone Data Visualization](https://asset.cloudinary.com/dnmebcuio/ecf1f048b2699f2b1c33fc3ce8bdcaf6)



# Microphone Data Visualization

This README.md file provides detailed documentation and working of the HTML file for Microphone Data Visualization.

## Introduction

This HTML file provides a simple interface to visualize microphone input data in real-time using a waveform chart. Users can start and stop recording audio from their microphone, with corresponding buttons provided for control.

## Technologies Used

- HTML
- CSS
- JavaScript
- SmoothieChart
- Web Audio API

## Detailed Documentation

### HTML Structure

The HTML structure defines the layout of the web page, including the title, canvas element for waveform visualization, and buttons for recording control.

### CSS Styling

CSS styles are applied to elements for better presentation, including font family, background color, button styling, and canvas border.

### JavaScript Functionality

1. **SmoothieChart Initialization:** The SmoothieChart library is initialized with specific configurations for data visualization, such as pixel resolution, grid settings, and label styles.

2. **Microphone Data Series:** A TimeSeries object is created to store microphone input data for visualization on the waveform chart.

3. **Real-time Visualization:** The microphone input data is added to the TimeSeries object and visualized in real-time on the canvas element using SmoothieChart.

4. **Recording Control:** Event listeners are added to the "Start Recording" and "Stop Recording" buttons. When the "Start Recording" button is clicked, the browser prompts the user for microphone access. If granted, the audio stream is captured, and an AudioContext is created for processing. The microphone input is connected to a ScriptProcessorNode, which allows for real-time audio processing. The audio data is then appended to the TimeSeries object for visualization. When the "Stop Recording" button is clicked, the recording process is stopped, and the resources are released.

### SmoothieChart Library

SmoothieChart is a JavaScript charting library specifically designed for real-time streaming data visualization. It provides smooth animations and customizable configurations for creating interactive charts.

### Web Audio API

The Web Audio API is a powerful JavaScript API for handling audio in web applications. In this project, it is used to capture audio from the microphone, process it in real-time, and connect it to the visualization component.

## How to Use

1. Open the HTML file in a web browser.
2. Click on the "Start Recording" button to begin recording audio from the microphone.
3. To stop recording, click on the "Stop Recording" button.
4. The waveform chart will visualize the microphone input data in real-time during recording.

## References

- [SmoothieChart Documentation](https://github.com/joewalnes/smoothie)
- [Web Audio API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [HTML Canvas Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [Navigator.mediaDevices.getUserMedia() Documentation](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
