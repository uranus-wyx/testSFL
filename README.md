# StackOverflow Listing Test

## Set up
Clone the project and install needed packages.

```code 
git@github.com:uranus-wyx/testSFL.git
```

Please add files in testSFL repo into qa-frontend-repo
```code=\
git clone git@github.com:dannnyliang/stackoverflow-listing.git && cd stackoverflow-listing && yarn
```

Check Chrome version, default 105
If your version is different, please download new Chromedriver. 

[Chromedriver download link](https://chromedriver.chromium.org/downloads)

## Development
1. Install node.js

2. Open Terminal
```code=
npm install
npm install —global yarn
```

If it cannot install yarn and error message is "command not found error", maybe it needs root administrator.
Solving:
```code
sudo npm install --global yarn
```

3. Start

```code
yarn start
```
![](https://i.imgur.com/ULrbGNd.png)

4. Open http://localhost:3000 to view it in the browser.

## Execute Python file
1. Open Termimal
2. Switch path to **qa-frontend-repo**
3. Execute ```python3 testing```
4. Logs data in logs folder
