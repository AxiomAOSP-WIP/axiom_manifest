### AxiomOS v1.0 based on Android 13 WIP ###

### Sync ###
```bash
repo init -u https://github.com/AxiomAOSP-WIP/axiom_manifest.git -b tesla-wip
or
repo init --depth=1 -u https://github.com/AxiomAOSP-WIP/axiom_manifest.git -b tesla-wip

repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### For official ##
For offical you need to have private access to organization and use branch tesla-wip-private. Private repos is for working AxiomOS Privacy Guard

### Build ###
```bash
. build/envsetup.sh
lunch axiom_DEVICE-BUILDTYPE
m bacon

Example:
lunch axiom_raphael-userdebug
m bacon
```

### Info and Credits ###
Axiom is in WIP state.

Thanks to everyone involved in Creating Custom Roms, and in particular credits to
- LienageOS Team
- ArrowOS Team
- VoltageOS Team
- ProtonAOSP Team
- GrapheneOS Team
- CrDroid Team
