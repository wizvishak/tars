# TARS
**TARS** is a [Stardew Valley](https://www.stardewvalley.net/) mod that activates a friendly drone. It helps you while you mine in the treacherous caves of the Valley - protecting you from monsters and zapping stones that it hovers over. 

TARs is fun weekend project. It was inspired by and is a open source fork of [@camcamcamcam/murderdrone](https://github.com/camcamcamcam/murderdrone).

### Use
Press `F8` to activate TARS.

Your personal drone will always hover around you and come to life in the mines and sewers. Without instruction it will,
- Destroy all monsters, even the invincible Armored Bugs
- Break down stones it hovers over so you can collect items

If you would not like the TARS as your aide, press `F8` again to deactivate TARS.

### Configure
The mod creates a `config.json` file in its mod folder the first time you run it. Open that file in a text editor to change what you'd like.Stardew

**Available settings**
<table>
<tr>
  <th>Setting</th>
  <th>Default</th>
  <th>What it affects</th>
</tr>
<tr>
  <td><code>Active</code></td>
  <td><code>true</code></td>  
  <td>
    State on game launch. You can press <code>F8</code> to toggle the state once the game starts.</br>
  </td>
</tr>
<tr>
  <td><code>KeyboardShortcut</code></td>
  <td><code>F8</code></td>  
  <td>
    The configured keyboard button.</br>
  </td>
</tr>
<tr>
  <td><code>Damage</code></td>
  <td><code>-1</code></td>  
  <td>
    Damage inflicted on monsters by your drone. <code>-1</code> results in a one-hit KO.</br>
  </td>
</tr>
</table>

### Compatibility
TARS is compatible with Stardew Valley 1.4+ on Linux/Mac/Windows single player.

### Thanks to
Huge shout out to [@Pathoschild](https://github.com/Pathoschild) for [SMAPI](https://github.com/Pathoschild/SMAPI) and [StardewMods](https://github.com/Pathoschild/StardewMods)

### License
MIT