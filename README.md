# flaskeddit

A simplified Reddit clone built in Flask.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development. See deployment for notes on how to deploy the project.

### Prerequisites

To run this application you need [Python](https://www.python.org/), [pip](https://pip.pypa.io/en/stable/), and [SQLite](https://www.sqlite.org/).

### Local Setup

Clone the project.

```
git clone https://github.com/aqche/flaskeddit.git
```

Use create a `venv` and use `pip` to install the project dependencies.

```
cd flaskeddit
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```

Set the `FLASK_APP` environment variable, create the SQLite database, and start the app.

```
export FLASK_APP=flaskeddit.py
flask cli create_db
flask run
```

Now you can give the application a try at [http://localhost:5000](http://localhost:5000)!

## Built With

* [Flask](http://flask.pocoo.org/) - Python Framework

## Contributing

Feel free to submit a pull request!

## Authors

* **aqche** - *Author* - [aqche](https://github.com/aqche)

See also the list of [contributors](https://github.com/aqche/flaskeddit/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for more details.