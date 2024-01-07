# Ocarina of Time: New Actor Script
This script automatically creates a new actor for any ZeldaRet Ocarina of Time repository

This is viable with both standard assets management, and the custom mod_assets management systems

```
-name NAME
--noobject
--help
```

`-name`: any alphanumeric characters as well as `_`. If you use `-` it will be replaced with `_`

`--noobject`: will skip creating anything related to the Object. Useful for actors that will use another actor's Object file (Defaults to `OBJECT_GAMEPLAY_KEEP`)

Examples:
```
python3 new_actor.py -name en_new_actor
python3 new_actor.py -name en_new_actor --noobject
```

## To Use
- Download the most recent file from Releases

- Unzip and place all files in the main folder of your Repository

- In command line, run the script as described above

- If you are using the mod_assets system, it will detect that and use it instead of standards assets
