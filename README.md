{
  "path": {
    "game": "C:\\Program Files (x86)\\NCSOFT\\BnS",
    "data": "contents\\Local\\TENCENT\\CHINESES\\data",
    "tencent": "contents\\Local\\TENCENT\\CHINESES\\CookedPC",
    "bns": "contents\\bns\\CookedPC"
  },
  "version": "v2.0.6",
  "lang": "en_US",
  "mesh_parser": {
    "childProcess": 15,
    "cycleInterval": 200
  },
  "upk_scanner": {
    "childProcess": 30,
    "cycleInterval": 200
  },
  "umodel_shooter": {
    "interval": 3000
  },
  "icon_dumper": {
    "childProcess": 5,
    "cycleInterval": 1500
  },
  "png_optimizer": {
    "options": {
      "childProcess": 15,
      "cycleInterval": 300
    },
    "tasks": {
      "icon": {
        "src": "database/icon/png",
        "dest": "database/icon/png-cps",
        "level": 7
      },
      "attach": {
        "src": "database/attach/pics",
        "dest": "database/attach/pics-cps",
        "level": 7
      },
      "costume": {
        "src": "database/costume/pics",
        "dest": "database/costume/pics-cps",
        "level": 7
      },
      "weapon": {
        "src": "database/weapon/pics",
        "dest": "database/weapon/pics-cps",
        "level": 7
      }
    }
  }
}
