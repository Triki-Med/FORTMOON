## FortMoon – space-themed memory card game

### Project motivation and description

FortMoon is a web-based flipping card memory game set in a space theme. It is both a fun interactive game and a demonstration of clean software engineering practices. The project brings together planets, astronauts, and cosmic visuals in an engaging user experience.

This project also serves as a base for applying modern development and DevOps practices, including Git, Docker, CI/CD pipelines, automated testing, and code quality tools.

### Features

* Flip cards to match pairs of planets and astronauts
* Space-themed visuals and layout
* Match counter and game timer
* Fully responsive UI
* Dockerized for deployment
* GitHub Actions pipeline for CI/CD
* Optional unit testing for game logic
* Pre-commit hooks for linting and formatting

### Tech stack

* HTML5
* CSS3
* JavaScript
* Docker
* Git and GitHub
* GitHub Actions
* ESLint and Prettier

### Project structure

```
fortmoon/
├── assets/                  -> Planet and astronaut images
├── css/                    -> Stylesheets
├── js/                     -> Game logic
├── index.html              -> Main game page
├── README.md               -> Project documentation
├── Dockerfile              -> Docker configuration
├── docker-compose.yml      -> Optional multi-service setup
├── .github/workflows/      -> GitHub Actions workflows
├── .pre-commit-config.yaml -> Pre-commit config
├── .eslintrc.json          -> Linter configuration
├── tests/                  -> Unit tests (optional)
└── package.json            -> Scripts and dependencies
```

### Local setup

#### 1. Clone the repository

```bash
git clone https://github.com/your-username/fortmoon.git
cd fortmoon
```

#### 2. Open the project locally

You can open `index.html` directly in a browser, or run a development server:

```bash
python -m http.server 8000
```

Then open: [http://localhost:8000](http://localhost:8000)

### Author

Mohamed Triki
GitHub: [https://github.com/Triki-Med](https://github.com/Triki-Med)

### License

This project is licensed under the MIT License. See the LICENSE file for details.
