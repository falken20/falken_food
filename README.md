<div align="center">
  
<!-- Para logo se puede usar https://studio.tailorbrands.com/-->
<img src="./static/assets/logo_app.png" alt="drawing" width="400"/>
<a href="https://richionline-portfolio.nw.r.appspot.com"><img src="https://richionline-portfolio.nw.r.appspot.com/static/assets/falken_logo.ico" width=40 alt="Personal Portfolio web"></a>

![Version](https://img.shields.io/badge/version-1.0.0-blue) ![GitHub language count](https://img.shields.io/github/languages/count/falken20/falken_food) ![GitHub Top languaje](https://img.shields.io/github/languages/top/falken20/falken_food) ![Test coverage](https://img.shields.io/badge/test%20coverage-0%25-green) ![GitHub License](https://img.shields.io/github/license/falken20/falken_food)[![Python used version](https://img.shields.io/static/v1?label=python&message=3.8&color=blue&logo=python&logoColor=white)

  
[![Richi web](https://img.shields.io/badge/web-richionline-blue)](https://richionline-portfolio.nw.r.appspot.com) [![Twitter](https://img.shields.io/twitter/follow/richionline?style=social)](https://twitter.com/richionline)
</div>

---
# falken_food
Food app to calculate nutrition information
API: https://www.edamam.com/.

##### Deploy
```bash
gcloud app deploy
```

##### Setup
```bash
pip install -r requirements.txt
```

##### Running the app
```bash
flask run
```

##### Setup tests
```bash
pip install -r requirements-tests.txt
```

##### Running the tests with pytest and coverage
```bash
./check_app.sh
```
or
```bash
coverage run -m pytest -v && coverage html --omit=*/venv/*,*/tests/*
```

##### Environment vars
```bash
FALKEN_VERSION="1.0.0"
ENV_PRO=N
LEVEL_LOG="INFO, WARNING, ERROR"
```

---

##### Versions
1.0.1 Including tests
1.0.0 Application
