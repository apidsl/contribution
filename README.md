
# [contribution.apidsl.com](https://contribution.apidsl.com/)



## APIfoundation [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/DOCS/APIFOUNDATION.md)

Here are 3 levels of apifoundation solutions
+ apifork
+ apibuild
+ apidsl

**apifork** to bring dependencies,packagages to the project

**apibuild** - to build it over composer, maven, npm, ...

**apidsl** - to use it over hi level domain language 


## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/inframonit/bash/edit/main/DOCS/CONTRIBUTION.md)

git config --global --add safe.directory /media/tom/projects/apidsl/docs

Solutions for development:

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```

Edit documentation with flatedit
```bash
echo '#!/bin/bash' > 'readme'
echo './flatedit/readme.sh readme.txt' > 'readme'
echo "./DOCS/MENU.md" >> "readme.txt"
echo "./DOCS/ABOUT.md" >> "readme.txt"
echo "./DOCS/FOOT.md" >> "readme.txt"
```

### Update documentation

```bash
 ./readme
```

Config project file

The config file: **.apifork** can be another, e.g. **projects.txt**

Just change the first line in  **.apifork** on **projects.txt**
```bash
projects.txt
```


### install

[minsungson/GitHub-cURL: A guide to installing files from GitHub repos in terminal using cURL](https://github.com/minsungson/GitHub-cURL)

```bash
./apifork install
```
OR

```bash
./apifork
```

### update

```bash
./apifork update
```


### remove

```bash
./apifork remove
```


## About flatedit [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/DOCS/FLATEDIT.md)


### Dependencies

projects list [**readme1.txt**](readme1.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme1.txt
```

### Comments

With comments not to load this file

projects list [**readme2.txt**](readme2.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme2.txt
```


### Logs

Show not- & working/existing files


projects list [**readme3.txt**](readme3.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme3.txt
```

