# Epic Events

Project 12



## Setup

clone the repo:
```sh
git clone https://github.com/BNNJ/Project9 {path/to/project}
```
create a virtual environment:
```sh
python -m venv {path/to/env}
```
enter the virtual environment:
```sh
source {path/to/env}/bin/activate
```
install dependancies:
```sh
pip install -r {path/to/project}/requirements.txt
```

## usage

Some basic users are provided through the `python -m manage.py seed` command,  
but you can chose to make your own instead:

create a superuser:
```sh
{path/to/project}/manage.py createsuperuser
```
and follow the instructions.
You can then add users for the sales and support groups.

run the webserver:
```sh
{path/to/project}/manage.py runserver
```

Then open a web browser and enter the url `localhost:8000`  
or [click here](http:localhost:8000)  
