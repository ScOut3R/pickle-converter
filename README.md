pickle-converter
================

pickle-converter is an interface for Python pickle files. It can dump a pickle file's content in JSON format and accepts base64 encoded JSON to write it out into a pickle file. Base64 encoded input is required so we don't have to escape the control characters in the JSON data for the shell.

Installation
------------
### Package ###
	easy_install pickle_converter

### Source ###
Get if from [github](https://github.com/ScOut3R/pickle-converter.git).

### Usage ###
pickle_converter.py [-h] [-f FILE] [-i INPUT] command

Pickle - JSON converter

positional arguments:
  command               what operation to perform (choices: decode, encode)

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  input/output pickle file depending on the command
  -i INPUT, --input INPUT
                        input base64 encoded JSON

