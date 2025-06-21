# 📝 Blog App

## 📌 Description
**Blog App** is a Django-based web platform that enables users to **view, post, and interact with blogs**. Each blog post includes **images, titles, and rich descriptions** to create an engaging experience. Users can register, comment on posts, update their profiles, and categorize blogs based on subject matter — ensuring a seamless and organized user journey.

## ✨ Features
- 🖼️ Create and browse blog posts with images, titles, and detailed descriptions
- 💬 Comment on blog posts to engage with the community
- 🙍‍♂️ Update user profile information
- 📚 Categorize blogs by subject for better content organization
- 🔐 Secure user authentication with login/register/logout functionality

## 🛠️ Technologies Used
- **Python & Django** – Web framework and backend logic
- **SQLite** – Database management
- **HTML / CSS / Bootstrap** – Frontend design
- **JavaScript** – Interactive UI elements
- **Django Admin Panel** – Backend content management

## ⚙️ Installation

1. **Clone the repository**
    ```
     git clone https://github.com/Maruf-ult/Blog_Project
    
    ```

2. Open the terminal in the project directory:
    ```
     cd Blog-App
    ```

3. Create and activate a virtual environment:
   ```
     python -m venv env
   ```
      Activate the virtual environment:
      On Linux/Mac:
   ```
     source env/bin/activate
   ```
   
      On Windows:
   ```
     env\Scripts\activate
   ```


5. Install dependencies:
    ```
       pip install -r requirements.txt
    ```

6. Configure the database:

- Create a `.env` file or configure your database settings in `settings.py`
- Run the following migrations:

  ```
    python manage.py makemigrations
    python manage.py migrate
  ```

6. Create a superuser for admin access:
   ```
     python manage.py createsuperuser

   ```

7. Start the development server:
    ```
        python manage.py runserver
    
    ```



