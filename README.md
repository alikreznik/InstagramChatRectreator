# Instagram Chat Recreator

A script that recreates Instagram chats from the raw JSON data Instagram provides in a personal data export.

## Tech Stack

- **Languages:** Python, JavaScript (Node.js)

## Table of Contents

- [How to Use](#how-to-use)
- [Function Overview](#function-overview)
  - [save_file](#save_file)
  - [get_index](#get_index)

## How to Use

1. [Download your Instagram data](https://help.instagram.com/181231772500920)
2. [Extract the downloaded archive](https://www.win-rar.com/download.html?&L=0)
3. Place the `message.json` file in the project folder
4. Open `index.js` and change `your_username` on line 20
5. Open `Extractor.py` and enter the name of your chat partner

## Function Overview

### save_file

Takes the content of the JSON file and saves the relevant content into a new, more manageable file.

![save_info](img/save_info.png)

### get_index

Given the JSON content and a target string, returns the index of that string's location within the list.

![find_index](img/find_index.png)

### Setup instruction

![js change](img/change.png)

## Note on data privacy

This project works directly with personal chat export data. It's intended for processing your own exported data locally — the script doesn't send data anywhere external.

## Author

**Alik Reznik**
[GitHub](https://github.com/alikreznik)
