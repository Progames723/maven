# maven
Maven repository for my mods i guess

### How to use:
```gradle
repositories {
    maven {
        name = "Progames723 mods repository" // optional
        url = "https://github.com/Progames723/maven/raw/main/maven/"
    }
}

dependencies {
    // Common
    modApi "dev.progames723.<mod>:<mod>-common:<modVersion>"
    // alternative
    modImplementation "dev.progames723:<mod>-common:<modVersion>"

    // Fabric
    modApi "dev.progames723.<mod>:<mod>-fabric:<modVersion>"
    // alternative
    modImplementation "dev.progames723:<mod>-fabric:<modVersion>"

    // Forge
    api fg.deobf("dev.progames723.<mod>:<mod>-forge:<modVersion>")
    // alternative(only if you use architectury)
    modApi "dev.progames723.<mod>:<mod>-forge:<modVersion>"
    // alternative to the alternative
    modImplementation "dev.progames723.<mod>:<mod>-forge:<modVersion>"
}
```
