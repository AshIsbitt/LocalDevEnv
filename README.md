# Local Dev Environment :disc:

This repository contains a (mostly) functional vagrant provision that sets up a mongoDB server and a node application. For more info, please see /app/README.d

## How to Use
### How to Run

1) To pull from Github:
```git clone git@github.com:AshIsbitt/LocalDevEnv.git ```

2) To create the two virtual machines set within this repo:
```vagrant up```

3) To enter into the virtual machine:
```vagrant ssh app```

4) To run the app:
```
cd /home/ubuntu/app
npm install express
npm install mongoose
npm install ejs
npm start
```

Please visit `development.local:3000` to run the home page.

### Installing Dependancies

Make sure you have the following dependancies installed:

- Vagrant v2.2.7
- Git v2.24.1
- VirtualBox v6.1.4
