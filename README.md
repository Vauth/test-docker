# Simple docker image for [claw.cloud](https://run.claw.cloud)

<br>

### 📦 Run:
```sh
docker pull ghcr.io/vauth/claw-docker:main
```

<br>

### 🚀 How it works?
- Add `claw.sh` file in your project and fill it with required cmds.
- Launch a project in run.claw.clouds & ads this docker image in your project.
  - **Docker Image URL:** `ghcr.io/vauth/claw-docker:main`
- Import `GITHUB_URL` including your project URL into environment variables.

<br>

### 📚 Sample `claw.sh`:
```sh
#!/bin/bash

git clone https://github.com/Vauth/fastapi
cd fastapi || exit
pip3 install -r requirements.txt --break-system-packages
python3 fast.py

```
