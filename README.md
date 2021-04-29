# Exploring CI/CD with a Profile README.md

[Profile READMEs](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme) are a fun easter egg on GitHub. If you create a
repository on your personal account, with the same name as your username,
the `README.md` in this repository will be displayed on your profile page.

Here's [an example](https://github.com/bcoe/bcoe).

In this hands on lab, we explore the topic of CI/CD using
[GitHub Actions](https://docs.github.com/en/actions) and your Profile README.md.

## The Exercise

### Prerequisites

**Join the GoogleDeveloperAcademy Organization:**

Instructions will be made available for doing so, reach out to an instructor
if you bump into any issues.

**Configure Node.js:**

Install [nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
(the Node Version Manager), and use this to configure the most recent release
of Node 14 on your computer:

```bash
nvm install 14
nvm use 14
```

### Use this repository as a template

Using this repository as a template, create a new repository on your personal
account with the same name as your username:

 <img width="600" src="https://raw.githubusercontent.com/GoogleDeveloperAcademy/profile-readme-template/main/images/template.png">

### Personalize your profile page

1. Clone the repository you've just created (_I recommend using
the [ssh](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) option, when cloning a repository_).
2. Create a branch to commit your changes on,
  `cd [my-user-name]`, `git checkout -b personalize`.
3. Replace the contents of `README.md` with the contents of `README.example.md`.
  > `README.example.md` is meant as a starting point, customize this to match
  > your bio. Make sure to leave a link to `./interests.svg` as this is used
  > in the following steps in the exercise.
4. Edit the contents of `interests.json` to match your interests (_this file is used to generate
  the pie chart on your profile page_).
5. Install the project's dependencies, `npm i`.
6. Generate a new pie chart, `npm run generate`.

## License

Apache Version 2.0

See [LICENSE](https://github.com/googleapis/nodejs-secret-manager/blob/master/LICENSE)
