# [VSLab](https://hu-lab.netlify.app/): the homepage of Vision & Security Lab based on [Hugo](https://gohugo.io)

## Prerequisites

* [Download and install Git](https://git-scm.com/downloads)
* [Download and install Hugo Extended v0.73-v0.74](https://gohugo.io/getting-started/installing/#quick-install)


## Installation

First, clone this repository.

```
git clone https://github.com/auhowielau/hu-lab.git
git submodule update --init --recursive
```

Then, you can choose any editor you like as long as Markdown is supported, such as [Visual Studio](https://code.visualstudio.com/), [Jupyter](https://jupyter.org/install).

Now, you can view your site by running the following command. Before that, be sure to naviagte to this folder using the `cd` command.

```
hugo server
```

Hugo then provides you with a link (e.g. http://localhost:1313/) to open in your web browser.


## Getting Started

### Create a publication
 - Option 1:

    **Automactically**

    Open your Terminal or Command Prompt app and install Academic's admin tool:
    ```
    pip3 install -U academic
    ```
    Use the `cd` command to navigate to this folder in the terminal.

    Then import your publications with:
    ```
    academic import --bibtex <path_to_your/publications.bib>
    ```
- Option 2:

    **Manually**

    Publications can be manually created using the command:
    ```
    hugo new --kind publication publication/<my-publication>
    ```
Then, you need to edit the parameters in `content/en/publication/<my-publication/index.md` to include the details of your publication. Detials can be found in [this website](https://wowchemy.com/docs/managing-content/#create-a-publication).

Then, you need to copy this publication to the coresponding folder in `zh`.

```
cp -r content/en/publication/<my-publication> content/zh/publication/<my-publication>
```

Now, you need to modify the parameters in `content/zh/publication/<my-publication>/index.md`.

### Create a user

An additional user can be create by the following command:

```
hugo new --kind authors authors/<name>
```
Then edit the newly created file at `content/en/authors/<name>/_index.md`. 

You can also upload a square photo for the user to the new `authors/<name>/` folder and name it `avatar` (in JPEG or PNG format).

You need to also copy this authors' folder to the coresponding folder in `zh`.

```
cp -r content/en/authors/<name> content/zh/authors/<name>
```

Now, you need to modify the parameters in `content/zh/authors/<name>/_index.md`.

## License

Hugo Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/gcushen/hugo-academic/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/hugo-academic/readme?pixel)](https://github.com/igrigorik/ga-beacon)
