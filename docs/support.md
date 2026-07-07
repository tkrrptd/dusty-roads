# SUPPORT

## Guide Support

<div>
  <p>If you get stuck or run into any issues, we’ve got your back. Join our <a href="https://discord.gg/AJxH6mFTnE">DUST Discord server</a> and navigate to the <code>#support-and-bugs-dust</code> channel. You can make a new post and tag it appropriately. When asking for support, please follow these simple rules:</p>
  <ul>
    <li>You did some effort to look into the matter yourself.</li>
    <li>You followed the instructions in the guide AND those of the individual mods.</li>
	<li>You did not install an ungodly amount of additional mods.</li>
    <li>You will share your load order, mod list, and crashlog in case of CTDs.</li>
    <li>Please keep things polite and clear. I work on this in my spare time, and I don't have a lot of it.</li>
  </ul><br>
  
  <div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        <b>A WORD ABOUT <span class="warn">NEW VEGAS ANTI CRASH (NVAC)</span></b><br>
		NVAC basically tells the game to not crash, when it wants to crash. So it forces the game to run when it shouldn't. That's not healthy as you can imagine, what may result in an unstable game and even save corruption. NVAC had its merits in the past I guess, but nowadays any scenario where NVAC would stop crashing are fixed by other mods. Except for crashes by broken meshes. But well, why would you want to run a broken mod anyway?<br> 
		Additionally, NVAC can also contribute to crashing due to memory corruption. And when you crash with NVAC active, the crashlog that is generated will be useless. Without reliable crash information, issues cannot be properly diagnosed or fixed. As such, support will not be provided.<br>
		<br>
		TL;DR: If your solution is NVAC, your problem isn't solved.
	  </div>	
  </div>

</div>

## FAQ

### General

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ There's water in Lake Mead and/or Colorado River.</p>
<div class="expander-faq-content" style="display:none;">
  <p>This is usually caused by a load order issue. Either the guide's or your own custom LOD is being overridden by another mod's LOD files, or <code>DUST LOD.esp</code> is not the last plugin in your load order. Check for conflicts in the left pane of <span class="highlight">MO2</span> and ensure <code>DUST LOD.esp</code> loads last.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ I get notified I miss certain masters: <code>YUP - Base Game + All DLC.esm</code>, <code>DUST - Manan's Tweaks.esp</code>, and <code>DUSTed DUSTesp</code>.</p>
<div class="expander-faq-content" style="display:none;">
  <p>You probably did not install the updated plugin for <span class="highlight">DUST - Expansion Project</span> (found under <span class="highlight">Update Files</span>), or it is not placed below the main <span class="highlight">DUST - Expansion Project</span> installation in <span class="highlight">MO2</span>. Alternatively, you may have installed a <span class="highlight">DUST</span> mod that has not been updated for compatibility with <span class="highlight">DUST Community Fixes and Tweaks</span>.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ The game crashes even before reaching the title screen.</p>
<div class="expander-faq-content" style="display:none;">
  <p>Make sure <span class="highlight">lStewieAl's Tweaks and Engine Fixes</span> is installed and enabled.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Vanilla NPCs appear in DUST.</p>
<div class="expander-faq-content" style="display:none;">
  <p>Another mod is overwriting <span class="highlight">DUST</span>'s NPC changes and requires a compatibility patch.</p>
</div>

### Wabbajack

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ I installed additional mods, and they are gone after updating the DUSTy Roads Wabbajack.</p>
<div class="expander-faq-content" style="display:none;">
  <p>You did not add the <code>[NoDelete]</code> prefix to their names in the left pane, as instructed on the <a href="../wabbajack/#how-to-update" target="_blank">Wabbajack</a> page.</p>
</div>

<p class="expander-faq clickable" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'">▼ Can I update whenever there's an update?</p>
<div class="expander-faq-content" style="display:none;">
  <p>Consult the <a href="../changelog/" target="_blank">changelog</a> first to find out whether it is safe to update mid-game. If it isn't, this will be stated explicitly. If in doubt, don't hesitate to ask!</p>
</div>

<br>
<br>

<div style="display: flex; justify-content: center; gap: 20px;">

  <a href="https://ko-fi.com/krrptd0238">
    <img src="https://uploads-ssl.webflow.com/5c14e387dab576fe667689cf/61e11d5cf697cee7ca5b65d9_Button-p-500.png" alt="Ko-Fi">
  </a>

</div>

