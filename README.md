# git-env

Generate environment variable of the current working directory/repo.

## Usage

To use `git-env` please run this command within directory of a git repo.

```sh
git env
```

**Output**

```
GIT_ACTOR=<actor>
GIT_REPOSITORY=<owner>/<reop>
GIT_REPOSITORY_OWNER=<owner>
GIT_REF=refs/heads/main
GIT_REF_NAME=main
GIT_SHA=7e6fe70a107dd5902da637fcc58a89f05bfdd27f
```

## License

Licensed under [MIT](LICENSE)
