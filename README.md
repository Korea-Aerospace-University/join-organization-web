README : [ **Project** | [For KAU](./README_FOR_KAU.md) ]

# 아직 완성되지 않았습니다!! (Still progressing!)

---

# join-organization-web

> ~~Join this organization : https://join-kau.herokuapp.com/~~

This web app invites the `typed-github-user` who meet the conditions with github-api to the `specified-github-organization`.

E.g.)
- Users with email matching rules.
- etc.

## For contributors

[CONTRIBUTING.md](https://github.com/iiitv/getmein-web/blob/master/CONTRIBUTING.md)

## To install the dependencies

```sh
npm install
```

## To start the local server

```sh
npm start
```

## Configuration

You can configure this application to use with your environment specified settings. Just copy these Environment variable to `.env` and make make necessary changes.
Don't commit this `.env` file or remove it from `.gitignore` .

### Environment variables

| VAR                    | DESCRIPTION                              | VALUES | DEFAULT |
| ---------------------- | ---------------------------------------- | ------ | ------- |
| ...                    | ...                                      | -      | -       |
| GITHUB_ORGS_NAME       | Your github organization name            | -      | -       |
| SECRET                 | Your github (organization owner's) token | -      | -       |
| ...                    | ...                                      | -      | -       |

#### Example

```
...

GITHUB_ORGS_NAME=Korea-Aerospace-University
SECRET=abcdefg1234567812310abcedfasdf

...
```
