# interaction18
conference for 2018

## Install and work on the website env=dev

### Dependencies
In order to minimize dependencies, we tried to be minimalist

- Yarn
- Postcss
- Autoprefixer
- Hugo

### Install

1. Get Yarn https://yarnpkg.com/en/
2. ```$ yarn install```

### Work on CSS
1. Edit only css files in `/themes/interaction18/static/css` folder
2. ```$ yarn run build:watch```

### Work with Hugo
1. Install Hugo http://gohugo.io/getting-started/installing/
2. ```hugo serve``` to view the output
2.1 ``hugo serve --ignoreCache`` to ignore cache for JSON files
