[![Build Status](https://travis-ci.org/etao-open-source/cube-sdk.svg?branch=dev)](https://travis-ci.org/etao-open-source/cube-sdk)

##[中文说明](https://github.com/etao-open-source/cube-sdk/blob/master/README-cn.md)


`Cube` is a light package for Android development.

![Screen Shot](https://raw.githubusercontent.com/etao-open-source/cube-sdk/dev/screen-shot.png)

DEMO project has been moved to [HERE](https://github.com/liaohuqiu/android-cube-app).

All of the `readme` content and document are moved to Github Pages, please visit the Github Pages for more imformation:

http://cube-sdk.liaohuqiu.net

### Import to your project

#### Repository

The latest version: `1.0.45.3.5-SNAPSHOT`, has been published to: https://oss.sonatype.org/content/repositories/snapshots, in gradle:

*   gradle

    ```
    maven {
        url 'https://oss.sonatype.org/content/repositories/snapshots'
    }
    ```
    
*   pom.xml
    
    ```
    <repository>
        <id>oss-snapshots</id>
        <url>https://oss.sonatype.org/content/repositories/snapshots</url>
        <releases>
            <enabled>false</enabled>
        </releases>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
    ```

The stable version: `1.0.44`, https://oss.sonatype.org/content/repositories/releases, in gradle:


*   gradle

    ```
    mavenCentral()
    ```

#### dependency

*   pom.xml, latest version:

```xml
<dependency>
    <groupId>in.srain.cube</groupId>
    <artifactId>cube-sdk</artifactId>
    <type>aar</type>
    <!-- or apklib format, if you want -->
    <!-- <type>apklib</type> -->
    <version>1.0.45.3.5-SNAPSHOT</version>
</dependency>
```

*  pom.xml, stable version:

```xml
<dependency>
    <groupId>in.srain.cube</groupId>
    <artifactId>cube-sdk</artifactId>
    <type>aar</type>
    <!-- or apklib format, if you want -->
    <!-- <type>apklib</type> -->
    <version>1.0.44</version>
</dependency>
```

*   gradle, latest version:

```
compile 'in.srain.cube:cube-sdk:1.0.45.3.5-SNAPSHOT@aar'
```

*   gradle, stable version:

```
compile 'in.srain.cube:cube-sdk:1.0.44@aar'
```

###### Eclipse

Load the content into you eclipse, it's a library project. Then use it in your application project.

SDK version >= 19
