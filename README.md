# Reverse Classroom for ML 2021

Website for a bi-weekly discussion group between four sophomores and some researchers from IEDC. Does not sound convincing? Checkout the [website](https://iedc-iem.github.io/Reverse-Classroom-ML/)

## Local development

People who developed this website don't care about Jekyll, or Ruby but computer does. There are serious versioning issues if you try to deploy the site without containerizing it. Luckily there is a docker-compose file to help you out with your local installation. Here are the instructions for local setup using docker:
1. Clone the repo.
2. Install docker and docker-compose.
3. `cd` into the repository and run `docker compose up`.
4. Open [localhost:4000/Reverse-Classroom-ML/](http://0.0.0.0:4000/Reverse-Classroom-ML/) in your browser.
