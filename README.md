# TinyWebDB

TinyWebDB Protocol:

|    Action        |URL                      |Post Parameters  |Response                          |
|------------------|-------------------------|-----------------|----------------------------------|
|    Get Value     |{ServiceURL}/getvalue    |tag              |JSON: ["VALUE","{tag}", {value}]  |
|    Store A Value |{ServiceURL}/storeavalue |tag,value        |JSON: ["STORED", "{tag}", {value}]|
