# sdkman
### - install JAVA using SDKMAN

#### SDKMAN - https://sdkmain.io

```shell
-- default
# curl -s "https://get.sdkman.io" | bash 

-- custom location 
# export SDKMAN_DIR="/usr/local/sdkman" && curl -s "https://get.sdkman.io" | bash

-- for all users, edit /etc/profile
# vi /etc/profile

-- add these
#THIS MUST BE AT THE END OF THE FILE FOR SDKMAN TO WORK!!!
[[ -s "/usr/local/sdkman/bin/sdkman-init.sh" ]] && source "/usr/local/sdkman/bin/sdkman-init.sh"

-- apply changes
# source /etc/profile

-- install java
# sdk list java
================================================================================
Available Java Versions
================================================================================
 Vendor        | Use | Version      | Dist    | Status     | Identifier
--------------------------------------------------------------------------------
 AdoptOpenJDK  |     | 14.0.2.j9    | adpt    |            | 14.0.2.j9-adpt
               |     | 14.0.2.hs    | adpt    |            | 14.0.2.hs-adpt
               |     | 13.0.2.j9    | adpt    |            | 13.0.2.j9-adpt
               |     | 13.0.2.hs    | adpt    |            | 13.0.2.hs-adpt
               |     | 12.0.2.j9    | adpt    |            | 12.0.2.j9-adpt
               |     | 12.0.2.hs    | adpt    |            | 12.0.2.hs-adpt
               |     | 11.0.8.j9    | adpt    |            | 11.0.8.j9-adpt
               |     | 11.0.8.hs    | adpt    |            | 11.0.8.hs-adpt
               |     | 11.0.7.hs    | adpt    |            | 11.0.7.hs-adpt
               |     | 8.0.262.j9   | adpt    |            | 8.0.262.j9-adpt
               |     | 8.0.262.hs   | adpt    |            | 8.0.262.hs-adpt
               |     | 8.0.252.hs   | adpt    |            | 8.0.252.hs-adpt
 Amazon        |     | 11.0.8       | amzn    |            | 11.0.8-amzn
               |     | 8.0.262      | amzn    |            | 8.0.262-amzn
 Azul Zulu     |     | 14.0.2       | zulu    |            | 14.0.2-zulu
               |     | 13.0.4       | zulu    |            | 13.0.4-zulu
               |     | 13.0.3.fx    | zulu    |            | 13.0.3.fx-zulu
               |     | 12.0.2       | zulu    |            | 12.0.2-zulu
               |     | 11.0.8       | zulu    |            | 11.0.8-zulu
               |     | 11.0.7.fx    | zulu    |            | 11.0.7.fx-zulu
               |     | 10.0.2       | zulu    |            | 10.0.2-zulu
               |     | 9.0.7        | zulu    |            | 9.0.7-zulu
               |     | 8.0.262      | zulu    |            | 8.0.262-zulu
               |     | 8.0.252.fx   | zulu    |            | 8.0.252.fx-zulu
               |     | 8.0.232.fx   | zulu    |            | 8.0.232.fx-zulu
               |     | 7.0.262      | zulu    |            | 7.0.262-zulu
               |     | 6.0.119      | zulu    |            | 6.0.119-zulu
 BellSoft      |     | 14.0.2.fx    | librca  |            | 14.0.2.fx-librca
               |     | 14.0.2       | librca  |            | 14.0.2-librca
               |     | 13.0.2.fx    | librca  |            | 13.0.2.fx-librca
               |     | 13.0.2       | librca  |            | 13.0.2-librca
               |     | 12.0.2       | librca  |            | 12.0.2-librca
               |     | 11.0.8.fx    | librca  |            | 11.0.8.fx-librca
               |     | 11.0.8       | librca  |            | 11.0.8-librca
               |     | 8.0.262.fx   | librca  |            | 8.0.262.fx-librca
               |     | 8.0.262      | librca  |            | 8.0.262-librca
 GraalVM       |     | 20.1.0.r11   | grl     |            | 20.1.0.r11-grl
               |     | 20.1.0.r8    | grl     |            | 20.1.0.r8-grl
               |     | 20.0.0.r11   | grl     |            | 20.0.0.r11-grl
               |     | 20.0.0.r8    | grl     |            | 20.0.0.r8-grl
               |     | 19.3.1.r11   | grl     |            | 19.3.1.r11-grl
               |     | 19.3.1.r8    | grl     |            | 19.3.1.r8-grl
 Java.net      |     | 16.ea.6      | open    |            | 16.ea.6-open
               |     | 15.ea.32     | open    |            | 15.ea.32-open
               |     | 14.0.2       | open    |            | 14.0.2-open
               |     | 13.0.2       | open    |            | 13.0.2-open
               |     | 12.0.2       | open    |            | 12.0.2-open
               |     | 11.0.7       | open    |            | 11.0.7-open
               |     | 10.0.2       | open    |            | 10.0.2-open
               |     | 9.0.4        | open    |            | 9.0.4-open
               |     | 8.0.252      | open    |            | 8.0.252-open
 SAP           |     | 14.0.2       | sapmchn |            | 14.0.2-sapmchn
               |     | 13.0.2       | sapmchn |            | 13.0.2-sapmchn
               |     | 12.0.2       | sapmchn |            | 12.0.2-sapmchn
               |     | 11.0.8       | sapmchn |            | 11.0.8-sapmchn
================================================================================
Use the Identifier for installation:

    $ sdk install java 11.0.3.hs-adpt
================================================================================

-- install java with Identifier
# sdk install java 11.0.8-zulu
# sdk install java 8.0.262-zulu

-- set default java	
# sdk default java 11.0.8-zulu

```



