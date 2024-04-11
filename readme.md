## Installation

+ Fork this repository

+ Clone the repository
  ```
  git clone git@github.com:your-username/FriendNet.git

  ```

+ Create a virtual environment
  ```
  python -m venv venv
  ```

+ To activate your environment
  ```
  source venv/bin/activate
  ```
  
+ Install the requirements
  ```
  pip install -r requirements.txt
  ```
  
+ Make the required migrations
  ```
  python manage.py makemigrations
  ```
  ```
  python manage.py migrate
  ```

+ To run the development server
  ```
  python manage.py runserver
  ```

+ Open your web browser and visit http://localhost:8000 to access the application.