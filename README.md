
![logo.apidsl.com](https://logo.apidsl.com/1/cover.png)


# [contribution.apidsl.com](https://bash.apidsl.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/MD/MENU.md)

+ [Sourcecode - bash.apidsl.com](https://bash.apidsl.com/) 
+ [Examples - examples.apidsl.com](http://examples.apidsl.com/)
+ [Documentation - docs.apidsl.com](https://docs.apidsl.com/)
+ [Blog - www.apidsl.com](https://www.apidsl.com/)
+ [Logotyp - logo.apidsl.com](https://logo.apidsl.com/)

+ [LICENSE](../LICENSE)



## APIfoundation [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/MD/APIFOUNDATION.md)

Here are 3 levels of apifoundation solutions
+ apifork
+ apibuild
+ apidsl

**apifork** to bring dependencies,packagages to the project

**apibuild** - to build it over composer, maven, npm, ...

**apidsl** - to use it over hi level domain language 


## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/MD/CONTRIBUTION.md)

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
echo "./MD/MENU.md" >> "readme.txt"
echo "./MD/ABOUT.md" >> "readme.txt"
echo "./MD/FOOT.md" >> "readme.txt"
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


## Contribution with GIT [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/CONTRIBUTION/GIT.md)

problem with local repositories
```bash
git config --global --add safe.directory /media/tom/projects/apidsl/docs
```

Solutions for development:

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```



### Update documentation by flatedit

```bash
flatedit
```

Config project file

## apifork

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


## Install [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/MD/INSTALL.md)


Solutions for development:

### Install

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```


Install package list after created project
```bash
curl https://raw.githubusercontent.com/apipackage/bash/main/apipackage.sh -o apipackage
echo "https://github.com/letwhois/bash apidsl/apidsl/bash letwhois" >> "apipackage.txt"
./apipackage install
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


## Start usage [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/CONTRIBUTION/START.md)

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



## About flatedit [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/MD/FLATEDIT.md)

Edit documentation with flatedit
```bash
echo "./MD/MENU.md" > "flatedit.txt"
echo "./MD/ABOUT.md" >> "flatedit.txt"
echo "./MD/FOOT.md" >> "flatedit.txt"
```

### Dependencies

projects list [**readme1.txt**](readme1.txt)
```
./MD/MENU.md
../bash/MD/TODO.md
./MD/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme1.txt
```

### Comments

With comments not to load this file

projects list [**readme2.txt**](readme2.txt)
```
./MD/MENU.md
../bash/MD/TODO.md
./MD/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme2.txt
```


### Logs

Show not- & working/existing files


projects list [**readme3.txt**](readme3.txt)
```
./MD/MENU.md
../bash/MD/TODO.md
./MD/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme3.txt
```


## PLAINEDIT [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/contribution/edit/main/MD/PLAINEDIT.md)



Edit documentation in 2 steps, first make the outputs over **plainedit.sh**
Create docs over **readme.sh**

list of projects
```bash
./plainedit.sh
```

Update html over plainedit

```bash
./plainedit.sh debug
```
```bash
./plainedit.sh deployment
```
```bash
./plainedit.sh api
```
```bash
./plainedit.sh client
```
```bash
./plainedit.sh path
```
```bash
./plainedit.sh whois
```
```bash
./plainedit.sh loop
```
```bash
./plainedit.sh monitoring
```
```bash
./plainedit.sh screenshot
```


Update documentation

```bash
./readme.sh
```



# Tags

+ scripts
+ language

---

+ [apidsl/examples](https://github.com/apidsl/contribution)
+ [contribution.apidsl.com](https://contribution.apidsl.com)

