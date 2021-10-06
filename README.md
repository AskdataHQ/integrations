<h1 align="center">
	<img width="300" src="https://uploads-ssl.webflow.com/5dff758010bfa7f94c98e37e/5e9b0ff61b847f206e4c8da8_askdata-logo-black-p-500.png" alt="Askdata">
	<br>
	<br>
</h1>
 
# Askdata Examples
This repository contains examples of [Askdata](https://www.askdata.com/) usage in serving different types of data.
## Installation
``
 pip install integrations 
``
or
``
pip install -r requirements.txt
``
## Load Excel
Lets handle our authenticaton
```python
from askdata import integration
pd.askdata.from_excel()
```