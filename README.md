# finished-social-app


## Getting Started

Follow all the steps below if you want to get this project up and running on your computer.

### Prerequisites

* [Python](https://www.python.org/downloads/release/python-360/) - version 3.6
* [Git](https://git-scm.com/downloads)

### Setup steps (on Windows operating system)

1. Open cmd
2. Go to the directory you want to clone this repository using <i>cd</i> command
3. Clone this GitHub repository on your computer by using either SSH or HTTPS option:</br>
`git clone git@github.com:AnaMaria2019/finished-social-app.git` (SSH)
4. Change directory to the directory just cloned, <i>finished-social-app</i>
5. Create a python virtual environment and activate it:</br>
`python -m venv <name_of_the_venv>`</br>
`<name_of_the_venv>\Scripts\activate` - this works only for Windows
6. Install the necessary packages mentioned in the <i>requirements.txt</i> file (in this case, only <i>Django</i>):</br>
`pip install -r requirements.txt`
7. Migrate the migrations that are already present in the project:</br>
`python manage.py migrate`
8. Run the Django server:</br>
`python manage.py runserver`
