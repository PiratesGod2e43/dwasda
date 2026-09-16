# Pirates Client 1.21.11
Fabric client project, Java 21. Press L to open the GUI. Pirates Mode is a single toggle. PvP, HUD, Crosshair, Visuals, Custom Capes and Keybinds are separate sections.

Build with `./gradlew build`; output is in `build/libs/`. A network connection is required on first build to download Minecraft/Fabric dependencies.


Build fix: Minecraft 1.21.11 uses the obfuscated/remap Loom plugin. This project uses `net.fabricmc.fabric-loom-remap` 1.14.10 instead of the unavailable 1.13.7. The GitHub Actions workflow uses Java 21 and Gradle 8.14.3.
