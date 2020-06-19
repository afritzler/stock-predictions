# stock-predictions

Stock Predictions Playground

## Setup

First lets create a `virtualenv` for our project and activate it

```shell
virtualenv -p python3 env
source env/bin/activate
```

As we are using [fbprophet](https://github.com/facebook/prophet) we need to install it as well

```shell
pip install numpy
pip install fbprophet
pip install jupyter
```

Or just use the `requirements.txt`

```shell
pip install -r requirements.txt
```

Start using the notebooks available in the `notebooks` folder by starting `jupyter-notebook`

```shell
jupyter-notebook
```
