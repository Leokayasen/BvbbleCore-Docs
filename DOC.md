# BvbbleCore

> An all-in-one modular utility plugin for PaperMC 1.21.5

## 📦 Features
- ✅ Modular command toggles
- 🔁 TP system with movement cancel + timeout
- ⚙️ Config reload without restarting
- 🔧 God, vanish, afk, feed/heal, and more

## 💡 Player Commands
| Command     | Description         | Permission |
|-------------|---------------------|------------|
| /tpa        | Request to teleport to others | bvbblecore.tpa |
| /tpahere    | Request to teleport others to you | bvbblecore.tpa |
| /tpaccept   | Accept request      | bvbblecore.tpa |
| /tpdeny     | Deny request        | bvbblecore.tpa |
| /back       | Return to last location | bvbblecore.back |
| /spawn      | Teleport to world spawn | bvbblecore.spawn |
| /afk        | Set AFK status      | bvbblecore.afk |
| /hat        | Wear the item you are holding    | - |
| /sethome <name> | Set a home location | bvbblecore.home |
| /home <name> | Teleport home | bvbblecore.home |

## 🛠️ Operator Commands
| Command     | Description         | Permission |
|-------------|---------------------|------------|
| /vanish     | Turn invisible to non-op players    | bvbblecore.admin |
| /freeze <player> | Freeze a player | bvbblecore.admin |
| /repair     | Repair held item | bvbblecore.admin |
| /heal <player> | Set target to full health | bvbblecore.admin |
| /feed <player> | Set target hunger to full | bvbblecore.admin |

...With more coming soon!

## ⚙️ Configuration
`config.yml` preview:
```yaml
plugin:
  use-prefix: true
  prefix: "§a[BvbbleCore]"
commands:
  tpa: true
  god: true
```

***NOTE: This is a WIP plugin and API, not everything is polished or release-ready. Please be patient!***

