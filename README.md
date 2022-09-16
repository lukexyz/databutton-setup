🔘 `databutton-setup`
================
Setup and example project for `databutton` library


## Instructions (Unix/WSL)

1.  Create **new repo on github** and clone locally

2.  Install with `pip install databutton` 
    - May require `sudo apt-get install gcc`


3. View options with $ `databutton --help`

4. 🏗️ Create new project (and authenticate)
    -  `databutton create lukepress`

5. Build and deploy new project
```sh
  cd lukepress
  pip install -r requirements.txt
  databutton start
  databutton deploy
  ```