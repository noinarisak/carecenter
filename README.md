# Care Center Web Application

Care Center goal is to help individual connect with non-profit organizations and communities find services for their needs. This project was develop becase there was no solution for non-profits to collectively see other services in the Chicago metro and suburban areas. By aggergating services offering of non-profit organizations and communities we hope to close the gaps on the needs of the less fortunate. 

## Getting Starteds

These instructions will get you a copy of the project up and running. You have a two options for development and testing purposes.

- Cloud Base: Cloud9.io
- Local Machine: Using Vagrant

### Prerequisites

You need the following dependencies are required to run the project, other project libraries are define in the [requirements.txt](requirements.txt).

- pip
- sqlite3
- python 2.7.x
- flask

Manually
```
pip flask requests flake8
```


### Installing (*WIP*)

A step by step series of examples that tell you how to get a development env running

Once the dependencies have been installed you must then create `.env` base off [.env.sample](.env.sample) and update the file with the appropiate configurtation values.

#### 1. OKTA Setup (*WIP*)

[Setup Okta Developer Account and API Keys](SETUP_OKTA.md)

#### 2.a. Development Option: Cloud9 (*WIP*)

```
pip install -r requirements.txt
...
python main.py (or setup Run Configuration on c9)
```

#### 2.b. Development Option: Local Machine (*WIP*)

```
vagrant up
...
...
...
vagrant ssh
```

## Running the tests (*TODO*)

Explain how to run the automated tests for this system

### Break down into end to end tests (*TODO*)

Explain what these tests test and why

```
Give an example
```

### And coding style tests (*TODO*)

Explain what these tests test and why

```
Give an example
```

## Deployment (*TODO*)

Add additional notes about how to deploy this on a live system

## Built With (*TODO*)

* [Cloud9](https://cloud9.io) - Cloud IDE used for development
* [Vagrant](https://www.vagrantup.com/) - Development environments made easy
* [Python]() - 
* [Okta Developer]() - OAuth, etc.
* [Flask]() - A minimal web framework.

## Contributing

Please read [CONTRIBUTING.md](../.github/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Noi Narisak** - *Co-author* 
* **Shawn Recinto** - *Co-author* 

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments (*TODO*)

* Hat tip to anyone who's code was used
* Inspiration
* etc
