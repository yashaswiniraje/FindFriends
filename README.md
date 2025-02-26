# FindFriends
# FindFriends - Django Project

## Project Overview
FindFriends is a Django-based web application designed to help people connect with event organizers and find companions for social activities. Users can browse posts created by others, filter events by category, and search based on city. Additionally, users can create, edit, and delete their own posts while interacting with organizers.

## Features
- **User Authentication**: Users can register, log in, and log out.
- **Post Management**:
  - Users can create a post for an event.
  - Users can edit or delete only their own posts.
  - Posts include title, image, description, price, date, organizer details, and location.
- **Event Filtering**:
  - Users can filter events by categories (e.g., Sports, Festive, Trips, Camping, Cafes, Adventure).
  - Users can search events by city.
- **User Interaction**:
  - Users can explore events posted by others.
  - Users can contact the organizer and book a slot.
  - Users can leave comments on event posts.

## Technologies Used
- **Django**: Web framework for backend development.
- **SQLite**: Database for storing user data and posts.
- **Django Authentication**: For user login/logout functionality.
- **Django ORM**: For database operations.
- **Bootstrap**: For basic UI components (optional, minimal styling).

## Installation and Setup
### 1. Clone the Repository
```sh
 git clone https://github.com/yashaswiniraje/FindFriends.git
 cd FindFriends
```

### 2. Create a Virtual Environment
```sh
 python -m venv venv
 source venv/bin/activate  # For macOS/Linux
 venv\Scripts\activate  # For Windows
```

### 3. Install Dependencies
```sh
 pip install -r requirements.txt
```

### 4. Apply Migrations
```sh
 python manage.py makemigrations
 python manage.py migrate
```

### 5. Create Superuser (Optional, for Admin Access)
```sh
 python manage.py createsuperuser
```

### 6. Run the Development Server
```sh
 python manage.py runserver
```

The application will be accessible at `http://127.0.0.1:8000/`.


```

## How It Works
1. Users register/login.
2. Users explore event posts created by others.
3. Users can filter events based on categories or search for events by city.
4. Users can create, edit, or delete their own posts.
5. Users can click the "Enquiry" button to connect with event organizers.
6. Users can leave comments on event posts.





