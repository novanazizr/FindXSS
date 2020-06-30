# FindXSS

###Compatibility:

Windows , Linux or any device running python 2.7
###Requirements:

Python 2.7

Wordlist included(wordlist.txt)

Modules required: Colorama, Mechanize

###Modules Required:

Colorama: https://pypi.python.org/pypi/colorama/

Mechanize: https://pypi.python.org/pypi/mechanize/

###Description: BruteXSS is a very powerful and fast Cross-Site Scripting Brutforcer which is used for bruteforcing a parameters. The BruteXSS injects multiple payloads loaded from a specified wordlist and fires them at the specified parameters and scans if any of the parameter is vulnerable to XSS vulnerability. BruteXSS is very accurate at doing its task and there is no chance of false positive as the scanning is much powerful. BruteXSS supports POST and GET requests which makes it compatible with the modern web applications.

###Features:

XSS Bruteforcing

XSS Scanning

Supports GET/POST requests

Custom wordlist can be included

User-friendly UI

###Usage(GET Method):

COMMAND:  python2 FindXSS.py
METHOD:   g
URL:      http://www.site.com/?parameter=value
WORDLIST: wordlist.txt
###Usage(POST method):

COMMAND:   python2 FindXSS.py
METHOD:    p
URL:       http://www.site.com/file.php
POST DATA: parameter=value&parameter1=value1
WORDLIST:  wordlist.txt
