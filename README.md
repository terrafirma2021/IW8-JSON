# Call of Duty Loadout JSON

This repository contains a large JSON file that includes information about weapons, attachments, operators, skins, finishing moves, camos, and more. It's designed to be easy to use for building game configurations. All Weapons are populated with all attachments!

## How JSON is formatted:

```json
{
    "PRIMARY_WEAPONS": {
        "SHOTGUNS": {
            "725": {
                "Code": "iw8_sh_charlie725",
                "Attachments": {
                    "Muzzle": {
                        "FlashGuard": "flashhider",
                        "Breacher": "melee / melee2",
                        "Tactical": "silencer",
                        "MuzzleBrake": "brake",
                        "Lightweight": "silencer2",
                        "Compensator": "comp",
                        "Monolithic": "silencer3"
                    },
                    "Barrel": {
                        "18\"": "barcust",
                        "14\"": "barshort",
                        "30\"": "barlong"
                    },
                    "Laser": {
                        "Tac": "laserbalanced",
                        "1mW": "laser",
                        "5mW": "laserrange"
                    },
                    "Optic": {
                        "Operator": "reflex",
                        "Aim-Op": "reflex2",
                        "Viper": "reflex3",
                        "Monocle": "reflex4",
                        "IntegralReflex": "reflex5"
                    },
                    "Stock": {
                        "TACUltralight": "stockl",
                        "SniperPro": "stockh"
                    },
                    "Underbarrel": {
                        "12-GaugeDeputy": "ubshtgn",
                        "Recon": "glsnap",
                        "HighExplosive": "gl",
                        "Flash": "glflash",
                        "Smokescreen": "glsmoke",
                        "Concussive": "glconc",
                        "Incendiary": "glincendiary"
                    },
                    "Ammunition": {
                        "TubeExtension": "xmags",
                        "SlugRnds": "calcust2",
                        "Dragon'sBreathRnds": "calcust"
                    },
                    "RearGrip": {
                        "SlimGrip": "guardlight",
                        "SteadyGrip": "guardheavy",
                        "Commander": "guardcust"
                    },
                    "Perks": {
                        "FastMelee": "gunperk_fastmelee",
                        "FullyLoaded": "maxammo",
                        "F-Disabling": "ammomod_slow",
                        "SleightOfHand": "fastreload",
                        "F-Wounding": "ammomod_wound",
                        "Mo'Money": "gunperk_xp",
                        "Recon": "gunperk_marksman",
                        "HeavyHitter": "gunperk_hardmelee",
                        "FMJ": "fmj"
                    }
                }
            },
