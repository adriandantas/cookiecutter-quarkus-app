# cookiecutter-quarkus-app

A Cookiecutter template for Quarkus, a Kubernetes-native Java stack tailored for OpenJDK HotSpot and GraalVM, crafted
from the best of breed Java libraries and standards.

## Requirements

- Cookiecutter >= 1.7.2
- Java JDK 11 or later
- Maven >= 3.6.0

## Usage

First, make sure you have Cookiecutter installed. If not, install it with:

```bash
pip install cookiecutter
```

Next, scaffold your Quarkus application project with:

```bash
cookiecutter gh:your_username/cookiecutter-quarkus-app
```

Follow the prompts to customize your application.

## Generated Project Structure

The generated project will have the following structure:

```
project-name/
│
├── src/
│ ├── main/
│ └── test/
│
├── Dockerfile
├── pom.xml
├── README.md
└── .gitignore
```

## Customization

You can modify the cookiecutter.json file to set default values for the project scaffolding. See the Cookiecutter
documentation for more details on customization.
