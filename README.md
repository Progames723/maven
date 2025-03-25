# maven
Maven repository for my mods i guess

not just mods now huh

### How to use:
```gradle
repositories {
    maven {
        name = "Progames723 repository" // optional
        url = "https://github.com/Progames723/maven/raw/main/maven/"
    }
}

dependencies {
    modImplementation "dev.progames723.<artifact>:<artifact>:<type>:<version>"
    //or
    implementation "dev.progames723.<artifact>:<artifact>:<type>:<version>"
}
```
