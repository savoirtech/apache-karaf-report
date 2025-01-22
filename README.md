# Apache Karaf Report
--- 

Apache Karaf 4.4.7

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| CentOS Stream 9     | IBM Semeru Community Edition 17   | 3.9.6 | PPC64LE      | Success | Jan 12, 2025 |  |
| Ubuntu 22.04.3 LTS  | Amazon Corretto 17   | 3.9.5 | x64      | Success | Jan 12, 2025 |  |
| MacOS 15.2  | Eclipse Adoptium 17   | 3.9.9 | AArch64      | Success | Jan 12, 2025 | On full build we see numerous unit test failures |



## Errata


Quick build to assure compilation. 
```
mvn clean install -DskipTests=true
```

## How to use this repo

Main branch is latest release of Apache Karaf.

A branch is created for each release to record lab results.
