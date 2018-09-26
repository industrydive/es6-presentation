# ES6 Presentation

## Installation

Install [pyenv](https://github.com/pyenv/pyenv/) to manage versions
```
brew update
brew install pyenv
```

Install Python 3.7
```
pyenv install 3.7
cd <path to this repo>
pyenv local 3.7
```

Use [pipenv](https://pipenv.readthedocs.io/en/latest/) to install dependencies
```
pipenv shell
pipenv install
```

Install the [ijavascript](https://github.com/n-riesco/ijavascript) kernel
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install pkg-config node zeromq
sudo easy_install pip
pip install --upgrade pyzmq jupyter
npm install -g ijavascript
ijsinstall
```

Run the notebook
```
jupyter notebook
```

Server will be at localhost:8888
