# [<img alt="Bitcoin" src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white" />](https://bitcoin.org/en/) Arbitrage Opportunities 

This user-friendly app will help the operator find Arbitrage opportunities for Bitcoin. 

Historical data is gathered from Bitstamp & Coinbase Exchanges.

Application of three fundamental phases of financial analysis will help find investment opportunities.

Analysis of this particular example is provided by Jupyter Notebook.

![<img src="http://url/image.png" style=" width:10px ; height:10px " >](https://assets-global.website-files.com/5cc1a690df4e901766e92dcd/5eec416fccc6ff9b674088cf_crypto-trading-p-800.jpeg)

---

## Technology Used

[![Python 3.7.13](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/downloads/release/python-3713/)
[![Python](https://img.shields.io/badge/Python-3.7.13-blue)](https://www.python.org/downloads/release/python-3713/)

[![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com/)

[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

[<img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />](https://pandas.pydata.org/)

[<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>](https://github.com/DigitalGoldRush?tab=repositories)

---

## Installation Guide

### The easiest way to install JupyterLab is to download the Anaconda application.
https://www.anaconda.com/products/distribution

### To install Juypter Lab with pip:
```
$ pip install jupyterlab
```
### Then install Jupyter Notebook with pip:
```
$ pip install notebook
```

### To install NumbPy with pip:
```
$ pip install numpy
```

### To install Pandas create a new (Python 3) notebook in Jupyter Notebook and then in the prompt enter:
```
$ import pandas
```
### Mathplot library will need to be installed. Using pip:
```
$ pip install mathplotlib
```

---

## [Questionary Usage](https://questionary.readthedocs.io/en/stable/pages/types.html)

### Use questionary to ask a single question
```python
import questionary
question = questionary.text("What's your first name?")
```
### Need to prompt the user to answer it:
```python
answer = question.ask()
```
### You can concatonate creating and asking the question in a single line for simplicity:
```python
import questionary
answer = questionary.text("What's your first name?").ask()
```

---
## Contributors

[![Python](https://img.shields.io/badge/Michael_Dionne-LinkedIn-blue)](https://www.linkedin.com/in/michael-dionne-b2a1b61b/)

---

## License

Copyright (c) 2022 Michael R. Dionne

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE
