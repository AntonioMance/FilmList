## FilmList
FilmList is a film application for adding,editing,removing and filtering films.
Details of the film will be shown in the project. the table would consist of the name of the film, the director of the film, the year the film came out, the film genre and a brief description of the film.
![image](https://github.com/AntonioMance/FilmList/assets/115353257/59b60bbc-7927-4750-b226-27166aa70416)
![image](https://github.com/AntonioMance/FilmList/assets/115353257/6ab8f038-013f-47b5-9681-7129cf327f70)

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
