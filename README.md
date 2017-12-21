# My first app for now

Try https://zeit.co/now example.

ref. https://qiita.com/aggre/items/f0cb9f8b8e8c54768e50

```sh
# Install Node.js v9.3.0 e.g.
nodebrew install-binary v9.3.0
nodebrew use v9.3.0
node -v #=> v9.3.0
# Update npm package itself
npm i -g npm
npm -v #=> 5.6.0 (latest on 2017-12-21)
npm install -g now@8.5.4
```

```sh
mkdir myfirstapp
cd myfirstapp

npm init
# Input "author" only

npm install --save express

# Edit package.json to add "start": "node index.js"
# Create index.html and index.js
```

```sh
now
# Input E-mail address
# Receive an E-mail for verification
# Open a URL for verification
```
