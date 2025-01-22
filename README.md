# Apache Karaf Report
--- 

Apache Karaf 4.4.7

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| CentOS Stream 9     | IBM Semeru Community Edition 17   | 3.9.6 | PPC64LE      | Failure | Jan 12, 2025 | On Full build we see LdapPoolingTest.keystore:66 » NoSuchProvider no such provider: IBMJSSE2. Test failures in JAAS :: Modules, Features Standard, and Integration Tests. |
| CentOS Stream 9     | Eclipse Adoptium 17   | 3.9.6 | PPC64LE      | Pending | Jan 12, 2025 |  |
| Ubuntu 22.04.3 LTS  | Amazon Corretto 17   | 3.9.5 | x64      | Success | Jan 12, 2025 | CamelExampleTests had a timeout. |
| Ubuntu 22.04.3 LTS  | Eclipse Adoptium 17   | 3.9.5 | x64      | Pending | Jan 12, 2025 |  |
| MacOS 15.2  | Eclipse Adoptium 17   | 3.9.9 | AArch64      | Failure | Jan 12, 2025 | On full build we see numerous unit test failures. MainLock, CamelExampleTests, and JpaExampleTest |



## Errata


Quick build to assure compilation. 
```
mvn clean install -DskipTests=true
```

## How to use this repo

Main branch is latest release of Apache Karaf.

A branch is created for each release to record lab results.
