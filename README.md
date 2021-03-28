# Linkedin Learning tutorial
Test Automation Foundation by Meaghan Lewis

Test Pyramid
Unit > Integration > UI Testing
Faster ------------> Slower
Isolated ----------> Integrated


Unit Testing
-- lower level
-- small part 
-- ensure each functionality works 
-- Large number of UI test

Integration testing
-- lower level
-- all parts of the application are seamlessly together
-- combining unit tests
-- Medium number of UI test

UI testing
-- end-to-end testing / functional testing
-- a form of integration testing
-- small number of UI test


Best Use of Automation
- Most impactful Features
- Tedious workflows
- give the same results everytime


DRY - Dont Repeat Yourself
DSL - Domain Specific Language

Note: 
Each should should only have one purpose
Test can run in any order
each test function should be describe behaviour


TestTools Framework
-Popular Framework
--mocha - nodejs
--jasmine - js
--jest - react
-Browser
--selenium
--cucumber - bdd
--cypress
#### Installation
1. Install xcode
2. Install nodejs
3. Install mongodb
```
brew tap mongodb/brew
brew install mongodb-comminuty@4.4 //latest version
brew --prefix //see the location
brew services start mongodb-community@4.4

mkdir -p /data/db
mongod --version
mongod
```
4. Git clone https://github.com/meaghanlewis/stickerfy
5. Follow the instruction on the git readme
6. got ot stickerfy
```
npm run unit-test
```


#### Personal Notes:
Agile Testing Quadrants by Brian Marick
- Classify Tests
- Helpful for planning