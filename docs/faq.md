# FAQ

## General

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Do I need to run the 4GB Patcher with the GOG version of the game?</p>
<div class="expander-faq-content" style="display:none;">
  <p>Eventhough the <code>LAA</code> flag is already set in the executable of the <span class="highlight">GOG</span> version, you still need to run the <span class="highlight">4GB Patcher</span> to make the executable auto-load <span class="highlight">xNVSE</span>.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ The game crashes even before reaching the title screen.</p>
<div class="expander-faq-content" style="display:none;">
  <p>Make sure <span class="highlight">xNVSE</span> is installed in the game's root folder, and/or <span class="highlight">lStewieAl's Tweaks and Engine Fixes</span> is installed and enabled.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ I get notified I miss certain masters: <code>YUP - Base Game + All DLC.esm</code>, <code>DUST - Manan's Tweaks.esp</code>, and <code>DUSTed DUSTesp</code>.</p>
<div class="expander-faq-content" style="display:none;">
  <p>You probably did not install the updated plugin for <span class="highlight">DUST - Expansion Project</span> (found under <span class="highlight">Update Files</span>), or it is not placed below the main <span class="highlight">DUST - Expansion Project</span> installation in <span class="highlight">MO2</span>. Alternatively, you may have installed a <span class="highlight">DUST</span> mod that has not been updated for compatibility with <span class="highlight">DUST Community Fixes and Tweaks</span>.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Vortex reports a cyclic interaction between rules.</p>
<div class="expander-faq-content" style="display:none;">
  <p>See the previous question.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Should I use LOOT to sort my plugins?</p>
<div class="expander-faq-content" style="display:none;">
  <p>No, not at all. If you followed the guide religiously or installed the <span class="highlight">wabbajack</span> modlist, your plugins will already be in the correct load order. If in doubt, you can verify it against the online <span class="highlight">Load Order Library</span> files (<a href="https://loadorderlibrary.com/lists/dusty-roads-base-2">Base</a> and <a href="https://loadorderlibrary.com/lists/dusty-roads-expanded-2">Expanded</a>). If you add additional mods, follow the instructions on their <span class="highlight">Nexus Mods</span> pages, use good judgment, and check for conflicts with <a href="../resources/#xedit" target="_blank">FNVEdit</a>.</p>
</div>

## Gameplay

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ There's water in Lake Mead and/or Colorado River.</p>
<div class="expander-faq-content" style="display:none;">
  <p>This is usually caused by a load order issue. Either the guide's or your own custom LOD is being overridden by another mod's LOD files, or <code>DUST LOD.esp</code> is not the last plugin in your load order. Check for conflicts in the left pane of <span class="highlight">MO2</span> and ensure <code>DUST LOD.esp</code> loads last.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Vanilla NPCs appear in DUST.</p>
<div class="expander-faq-content" style="display:none;">
  <p>Another mod is overwriting <span class="highlight">DUST</span>'s NPC changes and requires a compatibility patch.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Some weapons and armor appear as red diamond shapes.</p>
<div class="expander-faq-content" style="display:none;">
  <p>You probably forgot to install the assets for <span class="highlight">DUST - Ink and Ash</span>. Make sure you downloaded and installed both files, and do not let <span class="highlight">MO2</span> overwrite during installation.</p>
</div>

## Wabbajack

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ The game crashes on startup, without generating a crash log.</p>
<div class="expander-faq-content" style="display:none;">
  <p>Make sure to follow the steps on the <a href="../wabbajack/" target="_blank">Wabbajack</a> page, including copying the files from the <code>_Manual Install</code> folder to the game's root folder and running the included executables.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Can I add more mods after the Wabbajack installation?</p>
<div class="expander-faq-content" style="display:none;">
  <p>Sure, you can. However, support may be limited, and compatibility is your own responsibility. Make sure to add the <code>[NoDelete]</code> prefix to the mod name so it persists through <span class="highlight">Wabbajack</span> updates.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ I installed additional mods, and they are gone after updating the DUSTy Roads Wabbajack.</p>
<div class="expander-faq-content" style="display:none;">
  <p>You did not add the <code>[NoDelete]</code> prefix to their names in the left pane.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Can I update whenever there's an update?</p>
<div class="expander-faq-content" style="display:none;">
  <p>Consult the <a href="../changelog/" target="_blank">changelog</a> first to find out whether it is safe to update mid-game. If it isn't, this will be stated explicitly. If in doubt, don't hesitate to ask.</p>
</div>

