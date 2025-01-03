# IPSAS Article

This repository is dedicated to the IPSAS Article project.

## Project Structure

- `frontend/`: Contains the frontend application built with Angular.
- `backend/`: Contains the backend application built with Django.

## Frontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Backend

This project uses Django for the backend.

### Setup

#### Prerequisites
- Python 3.x
- Django
- Other dependencies listed in `requirements.txt`

#### Installation

2. Clone the repository:
   ```sh
   git clone https://github.com/bacemhlabba/ipsas-article.git
   cd ipsas-article/backend
3. Clone the repository:
   ```sh
   python3 -m venv venv
   source venv/bin/activate
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
 #### Running the Server
1. Apply migrations:
   ```sh
   python manage.py migrate
3. Run the development server:
   ```sh
   python manage.py runserver
#### Contributing
Pull requests and stars are always welcome. For bugs and feature requests, please create an issue.
