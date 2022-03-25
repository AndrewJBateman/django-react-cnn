# :zap: Django React CNN

* **Incomplete** Handwritten digit classification app based on the Mnist dataset with a Python-Django backend with a React frontend and a Convolutional Neural Network (CNN)
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/django-react-cnn?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/django-react-cnn?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/django-react-cnn?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/django-react-cnn?style=plastic)

## :page_facing_up: Table of contents

* [:zap: Django React CNN](#zap-django-react-cnn)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Frontend Setup](#floppy_disk-frontend-setup)
  * [:floppy_disk: Backend Setup](#floppy_disk-backend-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-do list](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* React frontend uses React-draw to draw digits and File-saver to save this digits as jpg files
* Function to interact with the backend
* Python-Django backend

## :camera: Screenshots

![screen print](./img/cnn.png)

## :signal_strength: Technologies

* **Frontend**
* [React v17](https://reactjs.org/) frontend framework
* [React Bootstrap v1](https://react-bootstrap.github.io/) styles & components - does not need jQuery
* [Bootstrap v4](https://getbootstrap.com/)
* [React Sketch v0.5.1][(](https://github.com/tbolis/react-sketch) sketch tool for React based applications, backed-up by FabricJS
* [Filesaver v2](https://www.npmjs.com/package/file-saver) the solution to saving files on the client-side
* [Axios v0.21.1](https://www.npmjs.com/package/axios) promise based HTTP client for the browser and node.js
* **Backend1**
* [Python v3](https://www.python.org/) programming language
* [Django v3](https://www.djangoproject.com/) server-side web framework
* [Django REST Framework v3](https://www.django-rest-framework.org/) powerful and flexible toolkit for building Web APIs.
* [Django CORS Headers](https://pypi.org/project/django-cors-headers/) to add Cross-Origin Resource Sharing (CORS) headers to responses
* [Pillow v2](https://pypi.org/project/Pillow/2.2.1/) Python Imaging Library

## :floppy_disk: Frontend Setup

* Run `npm i` to install dependencies

## :floppy_disk: Backend Setup

* [Install Python](https://docs.python-guide.org/starting/installation/)
* [Install pip](https://docs.python-guide.org/dev/virtualenvs/#installing-pipenv)
* [Install Django](https://docs.djangoproject.com/en/3.1/howto/windows/) by typing `pip install Django`
* Run `django-admin startproject example_proj` to create a new project [ref. docs](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)
* Open `example_proj` in VS Code
* Run `python manage.py startapp new_module` to create Python module
* Add code
* Run `pip freeze` to see list of modules installed. [Ref. Docs](https://pip.pypa.io/en/stable/reference/pip_freeze/)
* Run `python manage.py makemigrations` for changes to models etc.
* Run `python manage.py migrate` to migrate the migration files.
* To add a superuser Run `python manage.py createsuperuser --username=joe --email=joe@example.com` [Ref. Docs](https://docs.djangoproject.com/en/3.1/topics/auth/default/)
* Run `python manage.py runserver` to run server on port 8000 and open /admin console

## :computer: Code Examples

* extract from tba

```python

```

## :cool: Features

* tba

## :clipboard: Status & To-do list

* Status: done up to video 4 5.00 - need to uninstall Python 3.9 and install max v8 or Tensorflow will not install
* To-do: fix error in React file components/Draw.js. Replace Python

## :clap: Inspiration

* Youtube tutorials from 'Pyplane':
* [How to sketch in react | Django with AI | How to create a CNN with Django and React part 1](https://www.youtube.com/watch?v=ePWaHLtsz2U)
* [Django with AI | How to create a CNN with Django & React part 2](https://www.youtube.com/watch?v=3H5-mFf6pJg&t=18s)
* [Django with AI | How to create a CNN with Django & React part 3](https://www.youtube.com/watch?v=30QOoLhb5tY)
* [Django with AI | How to create a CNN with Django & React part 4](https://www.youtube.com/watch?v=wvQ8WVUtVcw)

* [A friendly introduction to Deep Learning and Neural Networks](https://www.youtube.com/watch?v=BR9h47Jtqyw)
* [A friendly introduction to Convolutional Neural Networks and Image Recognition](https://www.youtube.com/watch?v=2-Ol7ZB0MmU)
* [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb) to write and execute Python in your browser
* [virtualenv to path on Windows 10](https://stackoverflow.com/questions/48911582/virtualenv-to-path-on-windows-10)

## :file_folder: License

* This project is licensed under the terms of the MIT license.

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: gomezbateman@yahoo.com
