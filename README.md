![Image Description](https://res.cloudinary.com/dnmebcuio/image/upload/v1711908214/Screenshot_1173_nt7z4i.png)
![Image Description](https://res.cloudinary.com/dnmebcuio/image/upload/v1711908229/Screenshot_1174_nyb80h.png)
![Image Description](https://res.cloudinary.com/dnmebcuio/image/upload/v1711908249/Screenshot_1175_lvjbep.png)


# Microphone Data Visualization

## Introduction

This README provides detailed documentation for the Microphone Data Visualization project. This project offers a simple interface for real-time visualization of microphone input data using a waveform chart. Users can start and stop recording audio from their microphone, and the captured audio is visualized dynamically.

## Technologies Used

- **HTML:** Defines the structure of the web page.
- **CSS:** Styles the elements for better presentation.
- **JavaScript:** Implements the functionality for recording audio, processing it, and visualizing it in real-time.
- **SmoothieChart:** A JavaScript library for real-time streaming data visualization.
- **Web Audio API:** Provides access to audio-related functionalities like capturing microphone input and audio processing.

## Detailed Documentation

### HTML Structure

The HTML file consists of a title, canvas element for waveform visualization, and buttons for recording control.

### CSS Styling

CSS styles are applied to enhance the presentation of elements on the web page, including font family, background color, button styling, and canvas border.

### JavaScript Functionality

- **SmoothieChart Initialization:** SmoothieChart is configured for data visualization with specific settings like pixel resolution, grid style, and label appearance.
- **Microphone Data Series:** A TimeSeries object stores microphone input data for real-time visualization on the waveform chart.
- **Real-time Visualization:** Microphone input data is continuously added to the TimeSeries object and visualized on the canvas element using SmoothieChart.
- **Recording Control:** Event listeners are added to the "Start Recording" and "Stop Recording" buttons. When "Start Recording" is clicked, microphone access is requested, and upon approval, audio recording begins. The recorded audio is processed in real-time and visualized. Clicking "Stop Recording" ends the recording process.

### SmoothieChart Library

SmoothieChart provides smooth animations and customizable configurations for creating interactive charts. It is used here to visualize the microphone input data in real-time.

### Web Audio API

The Web Audio API allows capturing audio from the microphone, processing it in real-time, and connecting it to the visualization component. It forms the backbone of the recording and visualization process in this project.

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


