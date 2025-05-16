# Charity Plugin for Spigot & Paper

**Charity** is a GUI-based item donation and community reward plugin for Minecraft servers.  
Originally created by [ReflexLabs](https://github.com/reflexLabs) and now maintained by [Ker35](https://github.com/Ker35), the plugin encourages generosity by letting players donate items for points and access custom rewards.

---

## ✨ Plugin Overview

- GUI-based item donation and reward system (`/charity`)
- Earn points by donating items
- Redeem rewards from a configurable shop
- Balance view and cooldown mechanics
- JSON-based lightweight storage (no database needed)
- Highly configurable with sound and message customization
- Compatible with **Spigot** and **Paper** 1.21.4+
- Plugin Version: `2.0`

---

## 🚀 Installation

1. Download the latest `.jar` from the [Releases](https://github.com/Ker35/CharityPlugin/Releases)
2. Place it into your server's `plugins/` folder
3. Restart the server
4. Modify `config.yml`, `shop.yml`, and `blacklist.yml` as needed

---

## 📜 Commands & Permissions

| Command                              | Description                                      | Permission          |
|--------------------------------------|--------------------------------------------------|----------------------|
| `/charity` or `/ch`                  | Opens the main Charity GUI                       | `charity.use`        |
| `/charity gui`                       | Opens the GUI directly                           | `charity.gui`        |
| `/charity sell` or `/charity give`  | Donates item in hand to charity                  | `charity.give`       |
| `/charity shop`                      | Opens the reward shop                            | `charity.shop`       |
| `/charity givepoints <player> <amt>`| Gives points to a player                         | `charity.points`     |
| `/charity takepoints <player> <amt>`| Removes points from a player                     | `charity.points`     |
| `/charity resetpoints <player>`     | Resets a player's points                         | `charity.points`     |
| `/charity checkpoints <player>`     | Checks a player’s point balance                  | `charity.points`     |
| `/charity reload`                   | Reloads plugin config files                      | `charity.reload`     |
| `/charity cleanup`                  | Deletes old player data                          | `charity.cleanup`    |
| `/charity help`                     | Shows help menu                                  | `charity.help`       |
| `/charity info`                     | Shows plugin author/version info                 | `charity.info`       |

- `charity.*` grants access to all commands
- Operators (`/op`) bypass all permission checks

---

## ⚙ Configuration

You can customize:
- GUI layout and naming
- Item blacklist
- Shop rewards
- Point values per item
- Cooldown durations
- Sound effects and more

All data is stored in editable YAML and JSON files.

---

## 👤 Authors

- [ReflexLabs](https://github.com/reflexLabs) – Original Developer  
- [Ker35](https://github.com/Ker35) – Current Developer & Maintainer  

---

## 🔐 License

This plugin is **proprietary software**. Redistribution, modification, or resale is **not allowed** without explicit permission from Ker35.  
See [LICENSE.md](LICENSE.md) for full terms.

---

## 📞 Support & Contact

- SpigotMC: [Charity Plugin Page](https://www.spigotmc.org/resources/charity.83242/)
- Website: [https://ker35.com](https://ker35.com)
