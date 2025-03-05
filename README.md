# FE-BookRead

## Description

This project is designed to be able to buy books but also read them and the main features are ...

- Translate the words automatically when switching language 
- An authentification system
- To buy books
- Read an owned book

## Getting Started

### Prerequisites

- IDE used (PhpStorm, Visual Studio Code, IntelliJ,...)
  - [Visual Studio Code (v1.92.2)](https://code.visualstudio.com/updates/v1_92)
  - [Webstorm (v2024.3.3)](https://www.jetbrains.com/webstorm/download/other.html)
- Package manager (Nuget, Composer, npm, ...)
  - [npm (10.4.0)](https://www.npmjs.com/package/npm/v/10.4.0)
- OS supported (W2k22, Debian12,...)
  - [Windows (10.22H2)](https://www.microsoft.com/fr-fr/software-download/windows10%20)
  - [Ubuntu 22.04.5](https://fridge.ubuntu.com/2024/09/13/ubuntu-22-04-5-lts-released/)
- Others
  - [Node (20.11.0)](https://nodejs.org/en/download)
  - [Git (2.43.0.windows)](https://git-scm.com)

### Configuration
[Jest Webstorm](https://www.jetbrains.com/help/webstorm/running-unit-tests-on-jest.html#ws_jest_snapshot_testing)
[Jest VSC](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)

## Deployment

### On dev environment

1. Clone the repository and install the required dependencies

```shell
git clone [*link*](https://github.com/CPNV-RIA1/FE-BookReader.git)
cd FE-BookReader
```

2. Setup main branch and init Git Flow for the project

```shell
git switch main

git flow init
```

3. Install npm on the project
```shell
npm install
```

How to get dependencies and build?

### Running tests

All test on the project :
```shell
npm run test
```

All test of a single test file :
```shell
npm run test [pathToFile.js]
```
On a single class :
```shell
npm run test [className.test.js]
```

## Directory structure

```shell
./*FE_BookReader*
├───config
├───database
│   ├────migrations
│   ├────seeders
├───docs
├───public
│   ├────assets
│   │     ├────css
│   │     ├────img
├───src
│   ├────controllers
│   ├────models
│   ├────views
├───tests
├───.gitignore
├───LICENSE.txt
├───README.md
```

## Collaborate
### Convention

#### Commit

The project uses [Conventional Commits][Commit-url]. The keywords used are: `feat`, `fix`, `chore`, `refactor`, `test`, `docs`. The commits are named with the following pattern: `type: description` eg.(feat: add awsome feature).

#### Workflow

The project uses [Gitflow][GitFlow-url]. The branches used are: `main`, `develop`, `feature`, `release`, `hotfix`. The branches are named with the following pattern: `type/short-description` eg.(feature/awsome-feature).

#### Guideline
The project uses [code guideline](https://developer.mozilla.org/fr/docs/MDN/Guidelines/Code_guidelines/JavaScript) for JS. 

#### Useful links
  + [How to propose a new feature (issue, pull request)](https://github.com/CPNV-ES/maw11-jdn/issues/new/choose)
  + [How to use your workflow - GitFlow](https://nvie.com/posts/a-successful-git-branching-model/)
  + [How to use Jest](https://jestjs.io/docs/getting-started)
    
## License

- [MIT License](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository). (renvoie sur le fichier license)

## Contact

- Nathan : [nathan.chauveau@eduvaud.ch](mailto:nathan.chauveau@eduvaud.ch), [Github](https://github.com/NathanChauveau)
- Geffroy : [geoffroy.wildi@eduvaud.ch](mailto:geoffroy.wildi@eduvaud.ch), [GIthub](https://github.com/Wildigg)
