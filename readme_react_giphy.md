  1) Start from https://github.com/lewagon/react-boilerplate
  cd ~/code/<github_nickname>
  git clone git@github.com:lewagon/react-boilerplate.git react-giphy cd react-giphy
  // I am renaming the gitclone to "react-giphy"
  yarn install (to fetch the dependencies from NPM)
  Git log or git lg (see status)
  rm -rf .git (remove old logs from boilerplate - remove git story)

  brew update (for MAC)
  brew install node (instal node modules)
  brew upgrade node

  npm install node-sass (install)
  brew install node-sass (MAC)

  ///Ubuntu
  ///curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash - sudo apt-get install -y nodejs

  // just to let you know that I downloaded the boilerplate from Lewagon and there are some dependencies defined like webpack
  // you always have to intall webpack to "pack" Js and other codes in just one Js file
  2) Push to github:
  git init

  // these two steps just in the first commit to create a git repository:
  git remote -v
  hub create lmaguiar/react-giphy (see the options on the documentation to create a git repository)
  hub browse to open the repository in the bowser

  // every feature you do ...
  git add .
  git commit -m "Start new project from lewagon/react-boilerplate" yarn start
  git push origin master

  3) create CSS file from:
  https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css

  4)add:
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/bootstrap.min.css">
  from:
  https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css

  5) Create app.jsx, gif.jsx, gif_list.jsx, search_bar.jsx.... one file per component

  6) yarn add giphy-api (add API giphy)

  para iniciar o servidor local host 8080 yarn start

  Download react developer tools Chrome extension to help you:
  https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi
