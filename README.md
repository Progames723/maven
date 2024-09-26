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
    modApi "dev.progames723:<mod>:common:<modVersion>"
    // or
    modImplementation "dev.progames723:<mod>:common:<modVersion>"

    // Fabric
    modApi "dev.progames723:<mod>:fabric:<modVersion>"
    // or
    modImplementation "dev.progames723:<mod>:fabric:<modVersion>"

    // Forge
    implementation fg.deobf("dev.progames723:<mod>:forge:<modVersion>")
    // or
    modApi "dev.progames723:<mod>:forge:<modVersion>"
    // or
    modImplementation "dev.progames723:<mod>:forge:<modVersion>"

    //i hope neoforge is obvious
}
```
