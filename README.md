# Chat-Application-GUI

### We can chat online/over internet safely without records
>Note: If the server wants to save records it can save

#### The server.py should run only on on device or only one time to connect multiple clients
#### The Client.py is to run for chatting with other clients . It connects to server.py

#

>on server: we can change the host and port, as the host we can use our domain/ip
```python
host = '127.0.0.1'
port = 7976  
```

#

>on client: we must to use the same host domain/ip and port no. as given in server
```python
client.connect(('127.0.0.1', 7976)) 
```
