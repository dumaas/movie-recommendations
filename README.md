# Movie Recommendations

![frontpage](https://github.com/dumaas/movie-recommendations/blob/main/images/frontend-screenshot.png?raw=true)

[View the frontend in your browser](https://movie-recommendations-api.herokuapp.com/)\
[View the api in your browser](https://movie-recommendations-api.netlify.app/)

## Requirements
1. [Docker](https://docs.docker.com/install/)
2. [Docker Compose](https://docs.docker.com/compose/install/)


## How to run it?

1. Clone the repository:

```
$ git clone https://github.com/dumaas/movie-recommendations.git --recursive --jobs 3
```

2. Build the application from either the api or frontend directory:
```
$ docker-compose up -d --build
```


## How to update the subprojects to the newest versions?
In order to update all of them to their newest versions, run:
```
$ git submodule update --remote
```


## Where are the applications running?
- Movie Recommendations API - http://localhost:8000
- Movie Recommendations Frontend - http://localhost:8080


christiangonzalezblack@gmail.com
