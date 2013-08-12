How to use
========

Simply add the repository to your build.gradle file:

    repositories {
        maven {
            url 'https://github.com/aaronlong31/mvn-repo/raw/master/'
        }
        mavenCentral()
    }

And you can use the artifacts like this:

    dependencies {
        compile "com.actionbarsherlock:actionbarsherlock:4.4.0@aar"
    }
