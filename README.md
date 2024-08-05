# blog
blog project
## Setup

1. Clone the repository

2. Run migrations
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```
3. Run the development server
    ```bash
    python manage.py runserver
    ```

## Using the Admin Site

1. Create a superuser
    ```bash
    python manage.py createsuperuser
    ```
2. Log in to the admin site at `/admin/`
3. Add, edit, and delete blog posts

## Functionality

- The main page displays a list of blog posts.
- Each post links to a detail page that displays the full content of the post.
- Manage posts using the Django admin site.
