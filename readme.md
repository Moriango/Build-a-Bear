# Build A Bear Application

This is a Flask application used to demonstrate front end work. It temporarily saves user profiles and allows users to customize the clothing on a bear.

## Requirements

The application requires the following Python packages:

- `click==8.1.3`
- `colorama==0.4.6`
- `Flask==2.2.3`
- `itsdangerous==2.1.2`
- `Jinja2==3.1.2`
- `MarkupSafe==2.1.2`
- `Werkzeug==2.2.3`

## Running the Application

1. Ensure you have Python installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

2. Install the required Python packages by running the following command in your terminal:

    ```
    pip install -r requirements.txt
    ```

    Make sure your `requirements.txt` file includes the packages listed in the Requirements section.

3. Set the environment variable `FLASK_APP` to your application. For example, if your application is named `app.py`, you can set the variable in the terminal like this:

    On Windows:

    ```
    set FLASK_APP=app.py
    ```

    On Unix or MacOS:

    ```
    export FLASK_APP=app.py
    ```

4. Run the application using the Flask command:

    ```
    flask run
    ```

    This will start a development web server hosting your application. You can access the application by navigating to `http://localhost:5000` in your web browser.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).