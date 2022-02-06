From https://github.com/untitled-ai/jupyter_ascending:
```sh
poetry shell
python -m jupyter_ascending.scripts.make_pair --base example
jupyter notebook example.sync.ipynb
python -m jupyter_ascending.requests.sync --filename example.sync.py
```
Then use vim plugin to activate the cells
https://github.com/untitled-ai/jupyter_ascending.vim
