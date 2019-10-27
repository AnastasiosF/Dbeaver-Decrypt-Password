# Dbeaver-Decrypt-Password

### For DBeaver 6.1.3+
This is a Java program that decrypts the connections of the DBeaver
-----
I just share the code that I find in stackoverflow.
-----
##### This code help me to find the passowrd that I forgot so I create a programm and also share the code.
-----
## How to run:
File location
 * Windows: USERNAME\AppData\Roaming\DBeaverData\workspace6\General\.dbeaver\credentials-config.json
 * Linux: locate the ```credentials-config.json```
 * Mac: locate the ```credentials-config.json```
```
java -jar DecryptDbeaver credentials-config.json
```
----
The code is from: https://stackoverflow.com/a/57630312

