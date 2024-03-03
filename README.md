# AngularStarter

## Linux Install

### nvm
* curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
* export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
* [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
* nvm install --lts

### Angular
* npm install -g @angular/cli

### create new project
* ng new <project-name>
* cd <project-name>
* optional with Material: ng add @angular/material
* code .

### or clone from github
* cd ~
* git clone <remote-url.git>
* cd <remote>
* code .
