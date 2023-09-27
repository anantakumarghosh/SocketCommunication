# SocketCommunication
Bi-directional socket communication between Flask App and Express App

## Usage
Go to socketAppPython (Flask App)

Install python flask

Linux/Mac:   
Run `python3 -m venv .venv`
Run `. .venv/bin/activate`
Run `python3 app.py`

Windows:
run `.venv\Scripts\activate`
Run `py -3 -m venv .venv`

Go to socketAppExpress

Run `npm i`
Run `node app.js`

Open browser, enter below link in URL bar

`http://<ip-address-of-python-flask-server>:<port-of-flask-server>/send?data=<data>`   
`http://<ip-address-of-js-express-server>:<port-of-express-server>/send?data=<data>`
