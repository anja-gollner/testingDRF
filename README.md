# Testing Project

This project is a Django-based application created for practicing pagination, filtering, testing, and throttling. It serves as a sandbox to experiment with these functionalities and improve backend development skills.

## Features

- **Pagination**: Implemented pagination to manage large datasets efficiently.
- **Filtering**: Added filters to refine query results based on specific criteria.
- **Testing**: Wrote unit and integration tests to ensure application reliability.
- **Throttling**: Applied rate limiting to API views to control request frequency.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/testing-project.git
   cd testing-project
   ```

2. Create and activate a virtual environment:

   ```sh
   python3 -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

4. Apply migrations:

   ```sh
   python manage.py migrate
   ```

5. Create a superuser (optional for admin access):

   ```sh
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```sh
   python manage.py runserver
   ```

## Usage

- Access the API at `http://127.0.0.1:8000/`
- Test pagination by adding `?page=2` to endpoints
- Use filtering parameters to refine query results
- Run tests with:

  ```sh
  python manage.py test
  ```

## License

This project is for educational purposes and is not intended for production use. Feel free to modify and extend it as needed.

---

Happy coding! 🚀
