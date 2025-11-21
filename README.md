# Noah's Server Modpack

**Minecraft 1.21.1 | Fabric**

This modpack auto-updates every time you launch the game!

---

## Setup Guide (5 minutes)

### Step 1: Download the Installer

👉 **[Click here to download packwiz-installer-bootstrap.jar](https://github.com/packwiz/packwiz-installer-bootstrap/releases/latest/download/packwiz-installer-bootstrap.jar)**

Save it somewhere you can find it (like your Downloads folder).

---

### Step 2: Create a New Instance in Prism Launcher

1. Open **Prism Launcher**
2. Click **Add Instance**
3. Select **Custom** on the left sidebar
4. Set these options:
   - **Name:** `Noahs Server`
   - **Version:** `1.21.1`
   - **Mod Loader:** `Fabric` (use version `0.18.1` or latest)
5. Click **OK**

---

### Step 3: Add the Installer File

1. **Right-click** your new instance → **Folder**
2. Open the `.minecraft` folder
3. **Copy** the `packwiz-installer-bootstrap.jar` file you downloaded into this folder

---

### Step 4: Set Up Auto-Updates

1. **Right-click** your instance → **Edit**
2. Click **Settings** on the left
3. Click **Custom commands**
4. Check the box for **Pre-launch command**
5. Paste this exactly:

```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://noahsmiley.github.io/noahs-server-modpack/pack.toml
```

6. Click **Close**

---

### Step 5: Launch!

Click **Play** - the mods will download automatically.

Every time you launch, it checks for updates and downloads any changes!

---

## Troubleshooting

**"Java not found" error?**
- Make sure you have Java 21 installed
- In Prism: Settings → Java → Auto-detect

**Mods not downloading?**
- Double-check the pre-launch command is exactly as shown above
- Make sure `packwiz-installer-bootstrap.jar` is in the `.minecraft` folder

**Game crashes?**
- Allocate more RAM: Instance → Edit → Settings → Java → Memory: 4096 MB minimum

---

## Server IP

`[Your server IP here]`

---

*Questions? Ask Noah!*
