# maven
Maven repository for my mods i guess

### How to use:
```gradle
repositories {
    maven {
        name = "Progames723 mods or smh"
        url = "https://github.com/Progames723/maven/tree/main/maven/"
    }
}

dependencies {
    // Common
    api "dev.progames723:<modId>-common:<modVersion>"
    // Fabric
    modApi "dev.progames723:<modId>-fabric:<modVersion>"
    // Forge
    api fg.deobf("dev.progames723:<modId>-forge:<modVersion>")
}
```
