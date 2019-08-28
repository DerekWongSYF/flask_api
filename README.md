## [Creating Machine Learning API using Flask](https://www.analyticsvidhya.com/blog/2017/09/machine-learning-models-as-apis-using-flask/)
#### Code accompanying the AnalyticsVidhya article

__NOTE: This code is not a bit old, please do not use this for production level tasks. There are better ways to do all these things, consider using [FlaskAppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) & [quart](https://github.com/pgjones/quart) or [FastAPI](https://github.com/tiangolo/fastapi) for your production apis__ 

#### How to setup the Anaconda environment:

- Make sure you have __Anaconda distribution__, if not then visit: [Miniconda Installation](https://conda.io/miniconda.html) to install it.
- For a faster installation, run command (on terminal): `curl -L mini.conda.ml | bash` (Courtesy: [@mikb0b](https://twitter.com/mikb0b))
- For any queries regarding conda environment, visit: [Managing Conda Environments](https://conda.io/docs/user-guide/tasks/manage-environments.html)
- Go to the folder `./flask_api`, you'll encounter `flask_api.yml` file.
- In the terminal run command: `conda env create -f flask_api.yml`
- Once done, run: `source activate flask_api`. Your virtual environment is setup successfully!
