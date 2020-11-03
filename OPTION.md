

## maven

    maven {
        url('https://nexus.mhw828.com/repository/maven-releases/')
    }


## (或者下载项目发布到自己本都)发布到本地使用mavenLocal()

    ./gradlew libwcvcodec : publishToMavenLocal


## 依赖

    implementation 'com.ms:android-module-wechat-voice-codec:latest-release'