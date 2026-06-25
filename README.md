# **AutoJoinParty**

**AutoJoinParty** is a lightweight, high-performance client-side Fabric utility mod designed specifically for competitive players on PvP servers. It automates public party joining and introduces real-time group party coordination.
### This mod has been mainly tested on version 1.21.11. Other versions have not been tested extensively and may contain bugs or compatibility issues. If you encounter any problems, please report them through the issue page on github 


---

## **Key Features**

### **Instant Auto-Join**
Automatically detects and intercepts public hosting invitations (such as `(1/32) Player is hosting a public party!`) in the chat, executing the join command immediately without manual clicking.

### **Real-Time Group Coordination**
Introduces a client-side group system:
* **Sleek HUD Overlay**: Press **N** to open dashboard to manage your friends list and active group members.
* **Coordinated Entry**: When a group leader joins a party, the mod automatically broadcasts the command to all active group members, syncing the entire group into the same party instantly.
* **Presence Indicators**: View which servers your friends are playing on in real-time.

### **Toggle System**
Turn the automation on or off instantly using a customizable keybind (Default: **6**). Toggling displays a clean confirmation status directly in your chat.

### **Performance Optimized**
Built using Fabric client-side event listeners. The mod is lightweight, has zero background performance footprint, and runs without impacting frame rates.

---

## **How to Use**

1. Drop the `autojoinparty.jar` file into your Minecraft or Lunar Client mods folder.
2. Launch the game (Requires Fabric Loader for version **the version you downloaded**).
3. Once in-game:
   * Press **6** to toggle the automatic party joining feature.
   * Press **N** to open the Friends & Group HUD overlay to invite friends to your group.
4. You can customize both keybindings at any time in the standard Minecraft controls menu under the **AutoJoinParty** category.

---

### **Feedback & Versions**
If you would like to request this mod for a different Minecraft version, or to report bugs and suggest new features, please submit a report through the main website: 
https://mods-watrak.vercel.app
