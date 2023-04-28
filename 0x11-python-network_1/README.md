# Resources
Read or watch:

[HOWTO Fetch Internet Resources Using urllib Package](https://intranet.alxswe.com/rltoken/KoRrs5dVWsb-B82e-M1TQQ)
[Quickstart with Requests package](https://intranet.alxswe.com/rltoken/OGcRGPr7TSWtzypDd0ZibQ)
[Requests package](https://intranet.alxswe.com/rltoken/dUNaNQrV2bMSstILitQbXQ)

# Fetching Internet Resources with Python

This repository is focused on how to fetch internet resources using Python. Specifically, covering how to use the urllib and requests packages, as well as to decode urllib body responses, make HTTP requests (GET, POST, PUT, etc.), fetch JSON resources, and manipulate data from an external service.

## Learning Objectives

- Fetch internet resources with the Python package urllib
- Decode urllib body responses
- Use the Python package requests
- Make HTTP GET requests
- Make HTTP POST/PUT/etc. requests
- Fetch JSON resources
- Manipulate data from an external service

## Requirements

To successfully complete this project, you must adhere to the following requirements:

### General

- All files can be interpreted/compiled on Ubuntu 20.04 LTS using Python 3 (version 3.8.5)
- All files end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- pycodestyle (version 2.8.*)

| File             | Description                                                                                                                |
|------------------|----------------------------------------------------------------------------------------------------------------------------|
| 0-hbtn_status.py | Python script that fetches [this link](https://alx-intranet.hbtn.io/status)                                                             |
| 1-hbtn_header.py | Python script that takes in a URL, sends a request to the URL and displays the value of the X-Request-Id variable found in the header of the response. |
| 2-post_email.py  | Python script that takes in a URL and an email, sends a POST request to the passed URL with the email as a parameter, and displays the body of the response (decoded in utf-8) |
| 3-error_code.py  | Python script that takes in a URL, sends a request to the URL and displays the body of the response (decoded in utf-8). |
| 4-hbtn_status.py | Python script that fetches [this link](https://alx-intranet.hbtn.io/status)                                                             |
| 5-hbtn_header.py | Python script that takes in a URL, sends a request to the URL and displays the value of the variable X-Request-Id in the response header |
| 6-post_email.py  | Python script that takes in a URL and an email address, sends a POST request to the passed URL with the email as a parameter, and finally displays the body of the response |
| 7-error_code.py  | Python script that takes in a letter and sends a POST request to [this](http://0.0.0.0:5000/search_user) with the letter as a parameter. |
| 8-json_api.py    | Python script that takes in a URL, sends a request to the URL and displays the body of the response.                          |
| 10-my_github.py  | Python script that takes your GitHub credentials (username and password) and uses the GitHub API to display your id.         |
|100-github_commits.py | The Holberton School staff evaluates candidates applying for a back-end position with multiple technical challenges, like this one: ```Please list 10 commits (from the most recent to oldest) of the repository “rails” by the user “rails”. You must use the GitHub API, here is the documentation [here](https://developer.github.com/v3/repos/commits/). Print all commits by: `<sha>: <author name>` (one by line)``` Write a Python script that takes 2 arguments in order to solve this challenge.