### AxiomOS v1.0 based on Android 13 WIP ###

### Sync ###
```bash
        repo init -u https://github.com/AxiomAOSP-WIP/manifest.git -b tesla-wip
        repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

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
