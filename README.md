# Titanic Kaggle Competition
This repo contains my solution and any notes to the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites and Installation
All pip requirements are stored in the req.txt file.

The following installation notes also assume use of venv for virtual environments on Linux/Mac OSX . Change as required.

Run the following commands to setup development envirnoment:

```
python3 -m pip install -U pip
python3 -m pip install -U virtualenv
mkdir venv
python3 -m virtualenv venv/titanic
source venv/titanic/bin/activate
python3 -m pip install -r req.txt
python3 -m ipykernel install --name "titanic"
```

## Contributing

Got ideas? Contribute!

## Authors

* **Alastair Hamilton** - *Initial work* - [kr4in](https://github.com/kr4in)

## License

This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details
