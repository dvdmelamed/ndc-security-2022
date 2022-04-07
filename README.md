# MVS for Modern Tech Stacks 

Example of MVS for a simple python app managing movies and their actors

Companion repository for the talk at NDC Security 2022

Installation
------------
1. Create a virtual environment
2. Install dependencies (`pip install -r requirements.txt`)
3. Run the API (`uvicorn main:app --port 8000`)

There are 4 endpoints:
* `/movies`: list of movies
* `/movies?title=<TITLE>`: to search for a particular movie
* `/movie/<id>`: to get some details about a movie
* `/movie/<id>/stars`: to get the list of the movie actors
