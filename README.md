![Logo](admin/ankersolix2.png)

# ioBroker.ankersolix2

[![NPM version](https://img.shields.io/npm/v/iobroker.ankersolix2.svg)](https://www.npmjs.com/package/iobroker.ankersolix2)
[![Downloads](https://img.shields.io/npm/dm/iobroker.ankersolix2.svg)](https://www.npmjs.com/package/iobroker.ankersolix2)
![Number of Installations](https://iobroker.live/badges/ankersolix2-installed.svg)
![Current version in stable repository](https://iobroker.live/badges/ankersolix2-stable.svg)

[![NPM](https://nodei.co/npm/iobroker.ankersolix2.png?downloads=true)](https://nodei.co/npm/iobroker.ankersolix2/)

**Tests:** ![Test and Release](https://github.com/ronny130286/ioBroker.ankersolix2/workflows/Test%20and%20Release/badge.svg)

## ankersolix2 adapter for ioBroker

Integrade Anker Solix 2

## Description

This project is derived from https://github.com/tomquist/solix2mqtt and brings information from the anker api directly into ioBroker.

## Config

1. Create a familie-account in anker app and add it to your main-account
2. install the adapter
3. go to adapter setting and set your credentials
4. at first time, pleas use a high poll time (180sec), so you have enought time to stop the adapter if everything goes wrong.
   Normally you can see in logfile that you have an site_id and you got the message: Published.

## Helps

If you have errors like 401, than please check you credentials.
If you have erros again and cant login, stop the adapter and delete the session.data under the iobroker-data/ankersolix2.0 (e.g. /opt/iobroker/iobroker-data/ankersolix2/), after this start adapter again.

## Changelog

<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->

### **WORK IN PROGRESS**

- (ronny130286) edit refreshtimer
- (ronny130286) add to repo

### 1.0.2 (2024-12-04)

- (ronny130286) bugfix

### 1.0.1 (2024-12-01)

- (ronny130286) ESLint 9.x

### 1.0.0 (2024-11-29)

- (ronny130286) stable release
- (ronny130286) fixed backup_info object

### 0.1.0-beta.0 (2024-10-02)

- (ronny130286) beta release

### 0.0.3-alpha.0 (2024-09-25)

- (ronny130286) fix session.data
- (ronny130286) npm release

### 0.0.2-alpha.0 (2024-09-20)

- (ronny130286) initial release

## License

MIT License

Copyright (c) 2024 ronny130286 <ronnymatthei@gmx.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgements
