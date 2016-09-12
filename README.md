# dv-patentes

#### Usage

There are three different ways of using this script.

1# You can use it here: http://pablomatiasgomez.github.io/dv-patentes/index.html

2# Download dv-patente.sh and execute it from any command line like this:

```bash
./dv-patente.sh FAY097 FAY098 
```
This will list all the digits for every plate that you entered. 
Or you can just execute the script and write the plates to stdin, and the code will be printed to stdout:
```bash
./dv-patente.sh
FAY097
29
```

3# The odd way is to paste the contents of dv-patente.js into any javscript console and run it like this:

```javascript
getDV("FAY097");
```


That will return the DV. Digits are not case senstive, so it would be the same to write:

```bash
./dv-patente.sh FaY-097
```
```javascript
getDV("fAy-097");
```
