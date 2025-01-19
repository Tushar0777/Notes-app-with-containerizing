
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
https://github.com/Tushar0777/Notes-app-with-containerizing.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Docker-SET UP
1.clone the repository
```
https://github.com/Tushar0777/Notes-app-with-containerizing.git

```
2.open the folder in your command prompt and compose the app

```
docker compose up -d

```
3. the app will be running on local host of your browzer
 ```
http://localhost:8000/

```
4. compose down the running app 
```
docker compose down

```
