# Signal Generator Web App

[![**Open in Streamlit**](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)]()

This web app is to represent how you can use streamlit to interactively generate signals using Numpy and Scipy packages. Also, you can download the generated signal as a csv file. You can generate sine, cosine, square, chirp, sawtooth, or frequency-swept cosine signals.

There are 6 python files in this repository:
- **app.py**: the main file of the web app.
- **Signal.py**: the class to generate the a specific type of signal at a specific sampling rate, frequency, duration, and amplitude.
- **documentation.py**: the documentation that appears in the web app to explain the aim of this application.
- **download_signal.py**: to specify the way you want to download the generated signals.
- **select_signal.py**: to interactively select the signal you want to generate using the predefined parameters by Signal class.
- **viz_signal.py**: plot the signal using plotly line plot.

___
### Note:
You can combine the whole python files in one, but it'll be too bulky. This way, it's better for re-editing the code blocks and better for understanding the code.
___

https://github.com/OmarAlkousa/Signal-Generator-Web-App/assets/64659365/3a397860-4758-4adc-9a05-b7c88df66841
