<h1 align="center">Gotectivity</h1>
<h4 align="center">🕵️ A passive tool to fingerprinting and gathering technologies used on multiple domains</h4>
<p align="center">
<a href="https://travis-ci.org/JavierOlmedo/Gotectivity"><img src="https://api.travis-ci.org/JavierOlmedo/Gotectivity.svg?branch=master"></a>
<a href="https://www.python.org/"><img src="https://img.shields.io/badge/go-blue.svg"></a>
<a href="https://raw.githubusercontent.com/JavierOlmedo/Gotectivity/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
<a href="https://hackpuntes.com"><img src="https://img.shields.io/badge/website-hackpuntes.com-blue.svg"></a>
</p>

## About Gotectivity
Gotectivity is a passive Go tool designed to enumerate subdomains and extract information from technologies used on websites using OSINT. It helps penetration evaluators and bug hunters to gather sub-domains and technologies from the domain they are targeting.

## Install
Install Gotectivity is very simple, you can follow the below method:
```
go get -u github.com/JavierOlmedo/Gotectivity
```

## Usage
Short Form    | Long Form     | Description
------------- | ------------- |-------------
-d            | --domain      | Domain name to enumerate subdomains of
-v            | --verbose     | Enable the verbose mode and display results in realtime
-t            | --threads     | Number of threads to use for subbrute bruteforce (default 1)
-o            | --output      | Save the results to csv file
-h            | --help        | Show the help message and exit

## Examples
* To enumerate subdomains of specific domain:
```
▶ gotectivity -d example.com
```

> *Made with ❤️ in Spain*