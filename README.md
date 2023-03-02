# gesture-video-controller

## 🖥️ **Preview**

<img width=100% src="./.github/images/preview.gif">

## 🛞 **Dependencies**

- Node.js v19.6.1;
- It's recommended to use Unix environments (Linux). If you are using Windows, it's recommended to use [Windows Subsystem Linux](https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10);
- It's recommended to use Google Chrome Browser;

## 🚀 **Running**

Install Node.js 19.6.1 and restore the dependencies:

```bash
npm ci
```

Start the project:

```bash
npm start
```

Open your browser at [http://localhost:3000](http://localhost:3000).

## ✅ **Features Checklist**

- **Titles List**
  - [X] Should not crash the search field when typing a search term;
  - [X] Should draw hands on screen and make background elements still clickable 🙌;
  - [X] Should trigger scroll up when using open palm 🖐;
  - [X] Should trigger scroll down when using closed palm ✊;
  - [X] Should trigger click on nearest element when using pinch gesture 🤏🏻;
  - [ ] Should trigger **:hover** event on elements in context, when moving elements on screen;
- **Video Player**
  - [X] Should be possible to play or pause videos with the blink of an eye 😉;
  - [X] All machine learning processing must be done through a web worker;


## 🌟 **Credits**

- This project was created in "[Semana JS Expert 7.0](https://semana.javascriptexpert.com.br/)" (JS Expert Week 7.0). Event developed by [Erick Wendel](https://github.com/erickwendel).
- Classes project: https://github.com/ErickWendel/semana-javascript-expert07
- The interface was based on project [Streaming Service](https://codepen.io/Gunnarhawk/pen/vYJEwoM) by [gunnarhawk](https://github.com/Gunnarhawk)

## 📚 **References**

- [Google Machine Learning for Web Developers](https://youtube.com/playlist?list=PLOU2XLYxmsILr3HQpqjLAUkIPa5EaZiui)
- [Training Machine Learning at Google](https://teachablemachine.withgoogle.com/)
- [TensorFlow Projects](https://youtube.com/playlist?list=PLQY2H8rRoyvzSZZuF0qJpoJxZR1NgzcZw)
- [Database Used](https://www.kaggle.com/code/vikassingh1996/netflix-movies-and-shows-plotly-recommender-sys/data)
- [Convert Video to Canvas](https://stackoverflow.com/questions/64249599/how-to-run-handpose-tfjs-model-in-web-worker)
- [Tensorflow Blog](https://blog.tensorflow.org/2020/11/iris-landmark-tracking-in-browser-with-MediaPipe-and-TensorFlowJS.html)
- [Tensorflow Lib: face-landmarks-detection](https://github.com/tensorflow/tfjs-models/blob/master/face-landmarks-detection)
- [Workers Api](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers)
- [Blink Detection Example](https://selvamsubbiah.com/mediapipe-iris-detection-in-tensorflow-js/)
- [Morse Code With Eye Detection](https://medium.com/the-web-tub/recognising-eye-blinking-with-tensorflow-js-3c02b738850d)
- [Why webgl, cpu, webassembly](https://youtu.be/3ive-w7oUis?t=333)