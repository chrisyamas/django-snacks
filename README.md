# LAB - Class 26

## Project: Django Snacks

### Author: Christopher Yamas

### Setup

With this repo on your and Python3 on your local machine, while in root directory run terminal command `pip3 install -r requirements.txt`.

To view the Home page, simply run `python manage.py runserver` and go to the path specified in terminal following the words `Starting development server at`

To view the About page, add `/about/` to the end of path in the browser (or click the About button on the site's internal navigation).

### Tests

Tests are contained in the `snacks/tests.py` file.

They can be run in the terminal with command `python manage.py test`.

The first two tests check that `home` and `about` status codes are correct.

The next two tests check that `home` and `about` urls are using their respective templates, as well as the base/ancestor template.
