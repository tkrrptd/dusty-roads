# INTRODUCTION TO THE GUIDE

## The Guide

<p>This guide aims to help you set up a stable <span class="highlight">Fallout New Vegas</span> experience built around <span class="highlight">DUST Survival Simulator</span>, incorporating stability and performance improvements that have stood the test of time.</p>

<p><b>What <span class="warn">not</span> to expect:</b></p>
<ul>
  <li>Tacticool overhaul;</li>
  <li>Slooty outfits;</li>
  <li>Bazillion additional weapons;</li>
  <li>Ultra-high-resolution textures for every dust speck in the Mojave.</li>
</ul>
<br>
<p>This guide is divided into two paths:</p>

<div style="display: flex; gap: 20px; margin-bottom: 20px;">

  <div class="guide-box" style="flex: 1;">
    <div>
	  <p class="fake-h2" style="margin-top:0;">DUSTy Roads - Base</p>
	  <p>The <span class="highlight">Base Setup</span> establishes a stable <span class="highlight">DUST</span> foundation, along with a selection of stability improvements and essential bug fixes. It does not include expansions or additional content, and is intended for those who want to experience the original, yet more stable, version of <span class="highlight">DUST</span>, or use it as a base for their own mod list.</p>
    </div>
  </div>

  <div class="guide-box" style="flex: 1; border: 1px solid hsl(35, 80%, 45%);">
    <div>
	  <p class="fake-h2" style="margin-top:0;">⮚ DUSTy Roads - Expanded ⮘</p>
      <p>The <span class="highlight">Expanded Setup</span> (and <u>recommended</u> setup) builds on this base, introducing additional mods that enhance gameplay and add extra content, including the major expansions <span class="highlight">DUST - Expansion Project</span> and <span class="highlight">DUST - Ink & Ash</span>, both of which are highly recommended! You'll be guided first through the <span class="highlight">Base</span> setup first, with the option to continue into the <span class="highlight">Expanded</span> section if you choose to go further.</p>
    </div>
  </div>

</div>

<p>And if that still isn’t enough, there is also an <a href="../optional/#optional-mods" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">OPTIONAL SECTION</a> with additional suggestions to further expand your setup, either by complementing the existing mod list or replacing certain installed mods. Keep in mind that inclusion in this section does not necessarily mean the mods are plug-and-play. Some optional mods may require additional patching to resolve balance issues or other conflicts.</p>

---

## Using the Guide

<p>Take your time, read the guide in full and avoid skipping steps. If you need support with following the guide, or with your modded game, you can open a support ticket on the <a href="https://discord.gg/AJxH6mFTnE" >DUST Discord</a> (<code>#support-and-bugs-dust</code>), but it’s expected that you’ve followed the instructions carefully and done your due diligence before asking for help. The support page at the end of the guide also includes a modest <a href="../support/#faq" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">FAQ</a> covering common issues and questions.<br>
<br>
Each mod’s requirements and dependencies are accounted for. When a mod lists requirements on its download page, they are either already covered elsewhere in the guide or will be addressed later. Some may be recommendations rather than strict requirements, and may be omitted if not considered necessary. If a required dependency is not already included in the guide, it will be explicitly listed for download at the relevant step.<br>
<br>
The mod manager of choice is <span class="highlight">Mod Organizer 2</span>. Though that does not mean you cannot follow the guide as a <span class="highlight">Vortex</span> user, but you'll have to rely on other sources of information to set up <span class="highlight">Vortex</span>, or how to install and deploy mods, such as the <a href="https://github.com/Nexus-Mods/Vortex/wiki">Vortex Wiki</a>.<br>
<br>
If you choose to add additional mods, always read their descriptions, instructions, and requirements. You may need to revisit earlier installations to enable compatibility options or install additional patches.</p>

<div class="guide-box">
  <div>
    <p>A few mods in this guide are marked with a tag indicating that they:</p>
    <ul>
      <li style="margin-bottom: 0.6em;"><span class="badge-settings">SETTINGS</span> | require a custom INI file that is installed later in the guide (for instance, a custom <code>nvse_stewie_tweaks.ini</code>)</li>
	  <li style="margin-bottom: 0.6em;"><span class="badge-patch" style="margin-right: 0.5em;">DUST PATCH</span> | require a <span class="highlight">DUST</span> compatibility patch that is installed later in the guide.</li>
      <li><span class="badge-reinstall" style="margin-right: 0.5em;">REINSTALL</span> | require reinstalling a previously installed mod to select additional installer options (primarily used in the <span class="highlight">Expanded Version</span>).</li>
    </ul>
  </div>
</div>

<p>If this process becomes overwhelming at any point, you can always switch to the <a href="../wabbajack/" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">WABBAJACK</a> automated installation route.</p>

---

## Credits

<ul>
  <li><a href="https://vivanewvegas.moddinglinked.com/index.html" >Viva New Vegas</a>, the long-standing benchmark for reliable modded <span class="highlight">FNV</span> setups, and inspiration and example for this guide;</li>
  <li><a href="https://www.nexusmods.com/profile/Redawt" >Red</a>, for leading by example with his <a href="https://redawt.github.io/BelowZeroGuide/" >Below Zero</a> guide for <span class="highlight">FROST Survival Simulator</span>;</li>
  <li><a href="https://www.nexusmods.com/profile/theSnort" >theSnort</a> and <a href="https://www.nexusmods.com/profile/Grimpup" >Grimpup</a> for support, motivation and <a href="https://www.nexusmods.com/newvegas/mods/91012" >Ink & Ash</a>;</li>
  <li><span class="highlight">sw</span> for their awesome <a href="../Resources/">Perk Planner</a>;</li>
  <li><span class="highlight">The Council</span> of the <span class="highlight">DUST Discord</span> for support and ideas;</li>
  <li>The active and lively user base over at the <span class="highlight">DUST Discord</span>, and especially <span class="highlight">Stevenesque</span> and <span class="highlight">holyjay</span>;</li>
  <li>The good people at the <span class="highlight">Wabbajack Discord</span> for their support and help;</li>
  <li>And last but not least, the storyteller extraordinaire, <a href="https://www.nexusmods.com/profile/naugrim04" >naugrim04</a>, for <span class="highlight">DUST Survival Simulator</span>, a mod that fundamentally changed what <span class="highlight">Fallout New Vegas</span> could be!</li>
</ul>