## FilmList
FilmList is a film application for adding,editing,removing and filtering films.
Details of the film will be shown in the project. the table would consist of the name of the film, the director of the film, the year the film came out, the film genre and a brief description of the film.
![image](https://github.com/AntonioMance/FilmList/assets/115353257/c4f45f26-4f50-4edf-a152-d385da13baee)
![image](https://github.com/AntonioMance/FilmList/assets/115353257/054a3f03-f39f-4bf1-84c8-8e0bce46a80c)
## Features
-Add a new film
-edit film
-Delete film
-Filter films by genre
## Running the Backend
Application is run by docker

#### Creating a docker image
```sh
cd PIS
docker build -t filmlist -f ./Dockerfile .
```

#### Running the docker image
```sh
docker run -p 5000:5000 filmlist
```

## Running the frontend
Open and navigate to the frontend folder and run *index.html* with browser.
