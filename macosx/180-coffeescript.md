## 180 Install Node.js and CoffeeScript compiler
Tools required by server to compile CoffeeScript files into JavaScript

### 181 Node.js and Node Package Manager

Download and compile node.js and Node Package Manager

```
cd ~/code/source
curl -L https://nodejs.org/dist/v4.4.0/node-v4.4.0.tar.gz | tar xvz
cd node-v4.4.0/
./configure
make
sudo make install
```

Verify Node.js installed by typing

```
which node
```

Should return:

```console
/usr/local/bin/node
```

Verify Node.js version by typing

```
node -v
```

Should return:

```console
v4.4.0
```

Verify npm installed by typing

```
which npm
```

Should return:

```console
/usr/local/bin/npm
```

Verify npm version by typing

```
npm -v
```

Should return:

```console
2.14.20
```

### 182 CoffeeScript

Download and compile CoffeeScript

```
sudo npm install -g coffee-script
```

Verify CoffeeScript installed by typing

```
which coffee
```

Should return:

```console
/usr/local/bin/coffee
```

Verify CoffeeScript version by typing

```
coffee -v
```

Should return:

```console
CoffeeScript version 1.10.0
```

### Next Step

[190 - Install Rails Applications](https://github.com/remomueller/documentation/tree/master/macosx/190-install-rails-applications.md)
