# BlogApp

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

BlogApp is a Django-based web application where users can read, create, update, and delete blog posts. The application includes features for user authentication, blog management, and more.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

Follow these steps to install and set up the BlogApp project:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/20481A5450/HealthcareBlog.git
    cd HealthcareBlog
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser**:
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

## Usage

### Views Overview

#### Home
- **URL**: `/`
- **Description**: Displays all blog posts.

#### Login
- **URL**: `/login/`
- **Description**: Renders the login page.

#### Register
- **URL**: `/register/`
- **Description**: Renders the registration page.

#### Logout
- **URL**: `/logout/`
- **Description**: Logs out the current user and redirects to the home page.

#### Blog Detail
- **URL**: `/blog/<slug>/`
- **Description**: Displays the details of a specific blog post identified by a slug.

#### See Blog
- **URL**: `/see-blog/`
- **Description**: Displays the blog posts created by the currently logged-in user.

#### Add Blog
- **URL**: `/add-blog/`
- **Description**: Allows the user to add a new blog post.

#### Update Blog
- **URL**: `/update-blog/<slug>/`
- **Description**: Allows the user to update an existing blog post identified by a slug.

#### Delete Blog
- **URL**: `/delete-blog/<id>/`
- **Description**: Deletes a blog post identified by an ID.

#### Verify
- **URL**: `/verify/<token>/`
- **Description**: Verifies a user profile using a token.

### Example

To add a new blog post:
1. Log in or register for an account.
2. Navigate to the `/add-blog/` URL.
3. Fill out the form with the blog post details and submit.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, feel free to reach out to me at [email@example.com](mailto:email@example.com).
