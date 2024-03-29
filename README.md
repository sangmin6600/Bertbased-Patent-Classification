# Bert-based Patent Classification

This project aims to output International Patent Classification (IPC) for text input. To extract and classify features of documents, I used an improved multilingual BERT model, xlm-roberta, and tested it in the following environment.

 - python 3.8.10
 - cuda 11.8
 - torch 1.8
 - transformers 4.29.2
 - scikit-learn 1.2.2
 - matplotlib

<!-- gif -->







## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
$python -m venv venv_name
$. ./venv_name/bin/activate
$pip install -r requirements.txt
```

### Installing

A step by step series of examples that tell you how to get a development env running

#### EDA and Data preprocessing

In the EDA_with_preprocess.ipynb file, perform Exploratory Data Analysis (EDA) and data preprocessing step by step, and save the processed data file in "./data/".

#### Train and Validation

All processes related to model training and evaluation are included in the "main.ipynb" file.

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

