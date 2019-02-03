Below are the steps needed to install SASS in your local environment!
Source: https://stackoverflow.com/questions/46719549/why-did-sass-fell-down-on-highsierra

STEP 1: Install Homebrew
  - Open Terminal
  - Install Homebrew: Run ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" in Terminal
  - Be sure to keep the terminal window open while installing homebrew

STEP 2: Install RUBY
  - To install ruby run the following command in terminal: brew install rbenv ruby-build

STEP 3: Install Sass
  - To install SASS Gem, run the following command: sudo gem install -n /usr/local/bin sass
  - Once install is successful run the following command in terminal: sass --watch SCSS/style.scss:CSS/style.css
  - If all is successful then you've installed Sass! Time to test boi

STEP 4: Testing
    - Open style.scss and style.css files on text editor
    - To make sure scss is functioning properly, write out a css rule in the style.scss file and see if it gets written to the
      style.css file
    - index.html is a whiteboard for seeing your changes live. Go wild with it! 
