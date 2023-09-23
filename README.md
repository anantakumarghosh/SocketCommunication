# SocketCommunication
Bi-directional socket communication between Flask App and Express App

## Usage
Go to socketAppPython (Flask App)

Install python flask
Run `python3 app.py`

Go to socketAppExpress

Run `npm i`
Run `node app.js`

Open browser, enter below link in URL bar

`http://<ip-address-of-python-flask-server>:<port-of-flask-server>/send?data=<data>`   
`http://<ip-address-of-js-express-server>:<port-of-express-server>/send?data=<data>`
