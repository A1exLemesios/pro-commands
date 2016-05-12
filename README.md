# pro-commands

A repository describing basic useful terminal commands

## Creating new git project : ##

- Create new repository( Add a readMe file , license , gitignore file.)

- Open a terminal ( Run as administrator if you use windows)

- Change the directory to the folder the new project should go in

- Type in the following command  :

```bash
$ git clone [Github project link]

$ cd [project folder]
```

## Commiting and pushing changes : ##

- After you ve made your changes , open a terminal window.

- Type in the following commands :

```bash
$ git status

$ git add --all

$ git commit -am"Your message goes here"

$ git push origin master
```

Use always both `$ git add --all ` and `$ git commit -am"Your message goes here"`

## Pulling from github ##

- Open a terminal window and type in the following command :

```bash
$ git pull origin master
```
