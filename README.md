![bagpack](https://raw.githubusercontent.com/scriptnull/bagpack/master/logo.png)

![npm](https://img.shields.io/npm/v/bagpack.svg?style=flat-square) ![License](https://img.shields.io/npm/l/bagpack.svg?style=flat-square) [![Join the chat at https://gitter.im/scriptnull/bagpack](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/scriptnull/bagpack?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

bagpack is a versatile local package manager. bagpack has 2 ideas at its core , 
- Versatile - Don't care what the package is. Just deliver it.
- Local - No Internet connection needed. Everything is local to the machine.

# Inspiration
npm and bower are the main inspirations for bagpack. I have ended up using them atleast once a day and there are times when I have to install packages from them when my internet is down. So , bagpack's main purpose is to fill the gap left by them.

bagpack got its name from the  bagpack character of the TV Series named [Dora the Explorer](https://en.wikipedia.org/wiki/Dora_the_Explorer). Yeah ! bagpack provides all the necessary things for your quest. We even got the [map](https://github.com/scriptnull/bagpack/blob/master/bagpack.js#L13) inside the bagpack.

# Install
```bash
npm install -g bagpack
```

# Features
- Package anything. This allows your private libraries to be served easily.
- publishing and installing packages are done local without internet.
- reuse already installed packages from other package managers like bower and npm.
- Less overhead - bagpack stores key pair values and not a clone of the package.
- Dead simple copy paste utility.

# Concepts 
In order to start working with bagpack, here are some basic concepts.
- No configuration file is needed for identifying bagpack packages.
- All bagpack packages are identified as directories , with directory name as the package name.
- Versioning is not needed as , any changes inside the package will be effective automatically. 

# Commands
Here are some verbs to help you with 
- **pack** or **publish**  - Pack something into the bagpack. This will mean publishing your package via bagpack for using it.
- **pick** or **install** - Pick anything from bagpack. This means installing a package that is available in the bagpack.
- **list** - Lists all the things inside the bagpack.
- **remove** - Removes a package from bagpack.

![Demo](https://raw.githubusercontent.com/scriptnull/bagpack/master/demo.gif)

# Contribution 
Contributions are welcome.
- Feel free to send in Pull requests. 
- Report bug if you have found any.
- Refactor the already existing code.
- Feature requests and feedback sharing. 
- Whatever. Lets get started !

# License 
![GPLv3](https://raw.githubusercontent.com/scriptnull/bagpack/master/GPL.png)
