# ✍️ touch-x

[![basher install](https://www.basher.it/assets/logo/basher_install.svg)](https://www.basher.it/)
![GitHub](https://img.shields.io/github/license/alexander-mart/touch-x)
![Static Badge](https://img.shields.io/badge/topic-unix--philosophy-blue?logo=github&link=https%3A%2F%2Fgithub.com%2Ftopics%2Funix-philosophy)

One command to create a new script file and give it executable permission (touch &amp; add bash shebang &amp; chmod +x)


## Usage

### What does it do

1. Create new file: `touch <filename>`
2. Add shebang: `echo "#!/bin/bash" > <filename>`
3. Make it file executable: `chmod +x <filename>`


### Install with [basher](https://www.basher.it/)

```sh
$ basher install alexander-mart/touch-x
```


## Unix philosophy

> Make each program do one thing well.
> 
> To do a new job, build afresh rather than complicate old programs by adding new "features".
>
> -- <cite>Douglas McIlroy</cite>
> 
> See more: [en.wikipedia.org/wiki/Unix_philosophy](https://en.wikipedia.org/wiki/Unix_philosophy)


### Unix philosophy projects on GitHub

- Explore other [unix-philosophy](https://github.com/topics/unix-philosophy) projects on GitHub

- Please use a badge ![Static Badge](https://img.shields.io/badge/topic-unix--philosophy-blue?logo=github&link=https%3A%2F%2Fgithub.com%2Ftopics%2Funix-philosophy)
 if your project follows the same principles:

```markdown
![Static Badge](https://img.shields.io/badge/topic-unix--philosophy-blue?logo=github&link=https%3A%2F%2Fgithub.com%2Ftopics%2Funix-philosophy)
```


## TODO

- [x] add bash shebang by default
- [ ] add any shebang from library (`sh`, `python3`, etc...) with not requried parameter `-s|--shebang=<shebang>`
  - [ ] [Shebang snippets list](https://github.com/Rpinski/vscode-shebang-snippets/blob/master/snippets/shebang-plaintext.json)
- [ ] [Make Linux/Unix Script Portable With #!/usr/bin/env As a Shebang](https://www.cyberciti.biz/tips/finding-bash-perl-python-portably-using-env.html)
- [ ] [awesome package manager](https://github.com/shinokada/awesome) support: `ls -s ./bin/touch-x ./touch-x`


## Other projects

- 🦁 [rugit](https://github.com/alexander-mart/rugit) — run command & semantic git commit it
