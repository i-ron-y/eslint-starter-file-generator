# ESLint Starter File Generator

Extracts rules from ESLint's [List of available rules](https://eslint.org/docs/rules/) page and outputs fully-functional .eslintrc starter files.


## Usage

Install Python.

Install the required packages:

````
pip install urllib3
pip install requests
pip install BeautifulSoup4
````

Go to the directory where `eslint-starter-file-generator.py` is located.

Run:

````
python eslint-starter-file-generator.py [filetype [filename]]
````

Valid filetypes are: `js`, `json`, `yaml`
<br />
<br />
##### Output for 0 arguments:

`.eslintrc.js`, `.eslintrc.json`, and `.eslintrc.yaml` files will be outputted in the same directory where `eslint-starter-file-generator.py` is found.
<br />
<br />
##### Output for 1 argument:

A `.eslintrc` file in `js`, `json`, or `yaml` format, according to user input, will be outputted in the same directory where `eslint-starter-file-generator.py` is found.
<br />
<br />
##### Output for 2 arguments:

A file with a user-defined name, in `js`, `json`, or `yaml` format according to user input, will be outputted in the same directory where `eslint-starter-file-generator.py` is found.
<br />
<br />
**WARNING**: If you already have files of the same name as the respective output files in this directory, they WILL be overwritten.