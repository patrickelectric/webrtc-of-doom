# webrtc-of-doom
Personal experiment to create a simple and friendly webrtc server and webpage

# How to run:
middleware:
`./simple_server.py --disable-ssl`

frontend:
`python -m http.server`
> Remember to access 127.0.0.1:8080

server:
`cargo run -- --peer-id=WEBPAGE_ID`

# Reference:
Based on: https://github.com/centricular/gstwebrtc-demos
