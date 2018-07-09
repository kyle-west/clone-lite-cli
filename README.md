# clone-lite

Have you ever wanted to run `git clone` on a single file? This CLI allows for you to do just that.

Below is an example of how to clone a single `package.json` file from a repo. 

```sh
clone-lite https://github.com/owner/repo.git#version-or-branch package.json
```

<br>

## Installing

To install run

```sh
npm install -g clone-lite
```

For private repos, you will need to have a [person access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) in the `GITHUB_AUTH_TOKEN` environment variable.

```sh
export GITHUB_AUTH_TOKEN=the-oauth-access-token
```

<br>

