# Python Image Streaming

Run server

I'm using [FastAPI](https://fastapi.tiangolo.com/) for app server and [opencv-python](https://pypi.org/project/opencv-python/)

```bash
cd server
mkvirtualenv visual # read more: virtualenvwrapper
pip3 install -r requirements.txt
uvicorn main:app --reload # run in http://localhost:8000
``` 

Run Client

* Open `client/index.html` in your browser
* I use [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) for simple implementation of web server from local folder.

---

cheers,

@tegarimansyah