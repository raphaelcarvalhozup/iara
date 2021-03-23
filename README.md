<p align="center">
</p>
<h1 align="center">
  _______    _   _ \n    
 |__   __|  | | | |\n    
    | | ___ | |_| |__\n  
    | |/ _ \| __| '_ \\n 
    | | (_) | |_| | | |\n
    |_|\___/ \__|_| |_|\n
  The patient GitHub leak hunter
</h1>
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
<p>
Toth is a tool that uses GitHub API to search through users/orgs for leaks and shows it to the user in a friendly way. You can use an Authentication Token your GitHub account to access private repos and it is possible to specify the repo that you want to search in.
</p>

---

## Installation
- You will need Python installed.
- Clone this repository and then, inside its folder, run
  pip install -r requirements.txt
  
## Usage
- Inside the repository directory in your terminal, use this command:<br>
  ```python iara.py -u "USER/ORG" -r "REPO_NAME" -t "YOUR_GITHUB_TOKEN"```

## CLI Flags

-  ```-h, --help```   Show help message
-  ```-u, --user```    User or organization to search in.
-  ```-t, --token```   Insert your GitHub Token if you want to do an authenticated search. *Optional
-  ```-r, --repo```    Insert a repo if you want to do a more specific search. *Optional

---

## Roadmap

- [x] MVP 
- [ ] Arg for dork list selection
- [ ] Improve search with strings that have more than 2 words.
- [ ] Return more than 1 snippet per code.
- [ ] Create a file output.
- [ ] Create a graphical output with HTML.
