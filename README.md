# Cut Studio

A browser-based match cut editor by GenAI Radar. Create word or logo match cuts,
adjust the pacing and sound, and export a video locally. The interface supports
English and French.

## Run the application

Download this repository and serve its folder over HTTP:

```sh
python3 -m http.server 5173 --bind 127.0.0.1
```

Open http://localhost:5173, or upload the complete folder to a static web host.
No dependency installation or build step is required.

Logos, music and video rendering stay in your browser. Google Fonts requires
network access. Keep the tab visible during real-time video recording. Available
MP4 and WebM codecs depend on the browser.

Repository: https://github.com/genairadar/cut-studio
