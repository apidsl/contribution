
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
