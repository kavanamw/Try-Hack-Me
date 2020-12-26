What is the port number for the web server?
```
8000
```
Without using enumerations tools such as Dirbuster, what is the directory for the API?  (without the API key)
```
57
```
Where is Santa right now?
```
Winter Wounderland, Hyde Park, London
```
script.py
import requests 

for i in range(1, 100, 2):
	print(f'Api Key: {i}')
	r = requests.get(f'http://10.10.9.105:8000/static/index.html/api/{i}')
	print(r.text)