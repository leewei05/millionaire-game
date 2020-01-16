## Millionaire Game

This is a duplicate web application from the TV show "Who want's to be a millionaire".
Built this app just for fun. 

### How to deploy

1. Download from git
2. Run this with python

```
python -m http.Server
```

3. Open the app in your browser, `localhost:8000`

### Deploy with Docker

1. Download from git
2. Build an image with Docker

```
docker build -t [image_name] .
```

3. Run Docker image

```
docker run -d -p  80:80 [image_name]
```

4. Open the app in your browser, `localhost:80`

### Customize your own app

1. `cover.jpg` is the cover page of the app
2. All of the questions are stored in `data.json`, you can change the questions and answers in that json file.

### Contributors

Special thanks to iKala colleagues: Tammy, Momo.

### Other

Enjoy :)

