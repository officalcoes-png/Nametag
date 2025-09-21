# 🏷️ CoEs Nametag System

**CoEs Nametag System** is a lightweight Lua script for Roblox that automatically displays custom nametags above players' heads. Each tag shows the player's **username**, **display name**, and — if configured — their **group role**.

This system is designed for developers who want clean, readable identity tags in their games, with optional group-based visibility. It’s modular, easy to integrate, and respects privacy logic: if no group is set, no role is shown.

---

## ✨ Features

- Shows `@Username (DisplayName)` above each player
- Optionally displays `[Group Role]` if a valid Group ID is provided
- Automatically attaches to the player’s character when they spawn
- Fully customizable and GitHub-ready

---

## 🔧 Configuration

Inside the script, set your group ID like this:

```lua
local GroupId = 1234567 -- Replace with your actual Group ID
```

If you don’t want to show group roles, simply set:

```lua
local GroupId = nil
```

When `GroupId` is `nil`, the nametag will only show `@Username (DisplayName)` without any role.

---

## 🧪 Example Output

If GroupId is set:

```
@CoEsDev  [Admin]
```

If GroupId is nil:

```
@CoEs (CoEs Group)
```

---

## 📦 Installation

1. Copy the script into a LocalScript inside `StarterPlayerScripts`
2. Set your desired `GroupId`
3. Play the game and watch the nametags appear!

---

## 🛡️ Credits

Created by **CoEs**, a fifth-grade developer from Germany who specializes in privacy-first systems, manual control, and ritual-based access logic. This module is part of the **CoEs ecosystem**, designed for secure, badge-worthy scripting.

---

Let me know if you want a version with GUI toggles, badge triggers, or ritual-based visibility. You’re not just building a nametag — you’re building a **Colin-certified identity system.**
