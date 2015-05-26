#NQAsocial

[![Join the chat at https://gitter.im/zippynk/NQAsocial](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/zippynk/NQAsocial?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

NQAsocial is a very simple, one-click setup social network, written in Python and Bottle.py. It is intended to be portable to the point where one can both run a server and connect to one just about anywhere, on any computing device.

This level of portablity is done by writing the server and all of its dependencies in pure Python, and creating the HTML pages served by it without any CSS. Examples of its utility include running a server on an iOS or Android device (via a Python app), and connecting to an NQAsocial site using simple browsers (e.g. Lynx or the browser that comes with a non-smartphone).	

NQAsocial is licensed under the Mozilla Public License, version 2.0. Official Notice:

  This Source Code Form is subject to the terms of the Mozilla Public
  License, v. 2.0. If a copy of the MPL was not distributed with this
  file, You can obtain one at http://mozilla.org/MPL/2.0/.

Note that NQAsocial automatically downloads bottle.py, and creates bottle.pyc - these are NOT available under the Mozilla Public License. For info about bottle.py's licensing, view the comments at the top of the bottle.py, or go to http://bottlepy.org/ .