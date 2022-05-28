# TinyWebDB

A TinyWebDB to learn everything about Web APIs (IoT, Mobile, Cloud)

TinyWebDB Protocol:

|    Action        |URL                      |Post Parameters  |Response                          |
|------------------|-------------------------|-----------------|----------------------------------|
|    Get Value     |{ServiceURL}/getvalue    |tag              |JSON: ["VALUE","{tag}", {value}]  |
|    Store A Value |{ServiceURL}/storeavalue |tag,value        |JSON: ["STORED", "{tag}", {value}]|

Check https://github.com/TinyWebDB for more.

## TinyWebDB test program

TinyWebDb.ipynb ： a jupiter nodebook (python) for API test  
