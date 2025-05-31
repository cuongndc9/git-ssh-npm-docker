# git-ssh-npm-docker

🐊 git+ssh for npm & docker

## npm package

```sh
yarn add git+ssh://git@your_git_server_domain:your_username/your_private_repo_name.git
```
**example**

```sh
yarn add git+ssh://git@github.com:kimcuong060498/vietnamese.git
```

```json
{
  "dependencies": {
    "vietnamese-js": "git+ssh://git@github.com:kimcuong060498/vietnamese.git"
  }
}
```

## docker image

```sh
git clone git@github.com:kimcuong060498/git-ssh-npm-docker.git
docker build -t kimcuong060498/git-ssh-npm-docker --build-arg SSH_PRIVATE_KEY="$(cat ~/.ssh/id_rsa | base64)" .
```


<!-- INSPIRATIONAL_QUOTE_START -->
![Image](https://github.com/user-attachments/assets/e5dd7943-9aef-4ee2-94a1-c411600f6674)
🧑‍💻
<!-- INSPIRATIONAL_QUOTE_END -->
