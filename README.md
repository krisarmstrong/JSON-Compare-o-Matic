# JSON-Compare-o-Matic
## JSON Comparison Tool

This tool allows you to compare an arbitrary number of JSON files and view the differences between them.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
Python 3 installed on your machine
JSON files to be compared
## Installing
Clone the repository to your local machine
~~~
git clone https://github.com/<username>/json-comparison-tool.git
~~~
Navigate to the project directory
~~~
cd json-comparison-tool
~~~
Run the script
~~~
python3 json_comparison.py file1.json file2.json file3.json ...
~~~
## Usage

The script takes in an arbitrary number of JSON file inputs. It then reads the files, parse their contents and compare them. Any differences will be displayed in the console.

The script also includes error handling for when:

Invalid file path is provided
JSON parsing errors
JSON encoding errors

## Authors

Kris Armstrong

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Hat tip to anyone whose code was used for inspiration, etc
