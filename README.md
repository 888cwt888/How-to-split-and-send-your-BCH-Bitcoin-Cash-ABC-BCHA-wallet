# How to split and send your BCH / Bitcoin Cash ABC | BCHA wallet 
# Where To Store Bitcoin ABC (BCHA)

Install the [official BCHN wallet](https://bchnwallet.org) and split your BCH coins.

After the split, you can also use BCHNwallet to send the coins. Make sure you always choose the correct network by clicking the green Network icon.
## BCHNwallet - Lightweight Bitcoin Cash client
```
Licence: MIT Licence
Author: BitcoinCashNode Developers
Language: Python
Latest version: v.3.1.1
```
## Install
| Operating system | Latest version |
| ------ | ------ |
| Windows | [Download Win64 3.1.1](https://bchnwallet.org/download/BCHNWallet-win64-3.1.1.zip) |
| Windows | [Download Win32 3.1.1](https://bchnwallet.org/download/BCHNWallet-win64-3.1.1.zip) |
| MacOS |   [Download OSX 3.0.11](https://bchnwallet.org/download/BCHNWallet-3.0.11-osx.zip) |
| Web version | [BCHNwallet 2.3.3](https://bchnwallet.org) |
## License
Bitcoin Cash Node is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

## Run the develoment server
You will need [nodeJS](https://nodejs.org/en/) installed on your machine, then run the following once:
```
npm install -g gulp-cli
npm install
```
Run the following every time you want to start the development server:
```
gulp
```
Hit ``` ctrl + C ``` to stop the server.

## Writing an article
In ```/blog/```, copy the ```example.md``` file and replace the content. Run ```gulp``` to preview the article in the browser (located at http://localhost:3000/en/newsroom/filename).
