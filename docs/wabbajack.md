---
title: ""
hide:
  - title
---

<style>
.md-footer,
.md-sidebar--primary {
  display: none !important;
}

.md-content__inner h1:first-child {
  display: none !important;
}

</style>

<img src="/dusty-roads/images/wabbajacklist.png" alt="Pick your road" style="display:block; margin:auto;"><br>
<br>

<p><span class="highlight">Wabbajack</span> is an automated modlist installer. Instead of manually downloading, installing, and configuring hundreds of mods yourself, <span class="highlight">Wabbajack</span> automates most of the process and reproduces a curated setup as intended by the modlist author. A <span class="highlight">Wabbajack</span> modlist is built around a predefined collection of mods, configuration files, load orders, patches, and installer settings.<br>
For the user, the process is straightforward: after installing the required tools and selecting a modlist, <span class="highlight">Wabbajack</span> automatically downloads the necessary files from sources such as <span class="highlight">Nexus Mods</span> and configures the setup with minimal manual interaction. Once completed, you receive a ready-to-play modded installation.<br>
If you'd like to learn more about <span class="highlight">Wabbajack</span>, check out the <a href="https://wiki.wabbajack.org/">Wabbajack Wiki</a>.<br>
<br>
The <span class="highlight">DUSTy Roads Wabbajack</span> provides two profiles: 
  <ul>
    <li>a <span class="highlight">Base Version</span> featuring <span class="highlight">DUST</span>, and essential fixes,</li>
	<li>and an <span class="highlight">Expanded Version</span> that further builds upon this foundation with additional gameplay enhancements and content, such as <span class="highlight">Expansion Project</span>, <span class="highlight">Ink & Ash</span>, and more.</li>
  </ul><br>
You can consult the mod lists on <span class="highlight">Load Order Library</span> for a complete overview of the included mods: <a href="https://loadorderlibrary.com/lists/dusty-roads-base" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">DUSTy Roads - Base</a> | <a href="https://loadorderlibrary.com/lists/dusty-roads-expanded" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">DUSTy Roads - Expanded</a>.<br>
Alternatively, you can browse through the sections of the guide.</p>

<div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        This <span class="highlight">Wabbajack</span> has been developed and tested on <span class="highlight">Windows</span>. <span class="highlight">Linux</span> has not been tested or verified by me. Although it may work through <span class="highlight">Proton/Wine</span>, compatibility is not guaranteed, and <span class="highlight">Linux</span> installations are not supported. Support is provided only for <span class="highlight">Windows</span> installations.
	  </div>	
</div>
  
---

## Pre-Installation
<p>Prior to starting the automated installation, a few manual steps are required to prepare your system, including installing the game and downloading <span class="highlight">Wabbajack</span>.</p>

### Preparation
<div class="guide-box"> 
  <p>It is essential to read and complete the <a href="../preparation/" target="_blank"  style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">Preparation</a> section of the guide before proceeding with the <span class="highlight">Wabbajack</span> installation!</p>
   
</div>

---
	  
## Installation

### <a href="https://www.wabbajack.org/">Wabbajack</a>
<div class="guide-box" style="flex-direction: column;">

  <div style="display: flex; gap: 20px; margin-bottom: 10px;">
    <div style="flex: 1;">
      <ol>
        <li>Download the installer using the <code>Download Now</code> button</li>
        <li>Create a new folder outside of any default Windows folders or the game folder itself, for example: <code>D:\Wabbajack</code></li>
	    <li>Move the downloaded <code>Wabbajack.exe</code> into this new folder, and run it</li>
		<li> Click <span class="highlight">Browse lists</span>, check <span class="highlight">Non-featured</span>, and search for <span class="highlight">dusty roads</span> in the <span class="highlight">Search for a modlist...</span> field</li>
		<li>Click the <span class="highlight">DUSTy Roads</span>tile, and then click on the <span class="highlight">Install</span> button at the bottom</li>
		<li>On the left-hand side, set both the <span class="highlight">Installation Location</span> and the <span class="highlight">Downloads Location</span>. These folders cannot be:
          <ul>
            <li>the game folder,</li>
            <li>a default Windows folder,</li>
            <li>the <span class="highlight">Wabbajack</span> folder,</li>
            <li>or another folder already containing a <span class="highlight">MO2</span> installation.</li>
          </ul>
          Example of a suitable location: <code>D:\Mod Lists\DUSTy Roads</code></li>
        <li>Click the <code>Install</code> button and log in to <span class="highlight">Nexus Mods</span> when prompted</li>
        <li>Authorize <span class="highlight">Wabbajack</span>, then simply wait for the downloads and installation to finish...</li>
        <li>When finished, click the <code>Open in File Explorer</code> button to open the folder where the mod list is installed</li>
      </ol>
    </div>
    <div style="flex: 1; display: flex; align-items: center; justify-content: center; min-height: 200px;">
      <img src="/dusty-roads/images/wjui.png" alt="Wabbajack Installation" style="width: 80%; height: auto; border-radius: 4px;">
    </div>
  </div>

  <div class="infobox-info">
    <div class="infobox-title"><span class="icon-info"></span> Information</div>
    <div class="infobox-content">
      If you do not have a <span class="highlight">Premium</span> account, you will need to manually confirm each mod download.<br>
      The time required to download and install everything depends on your <span class="highlight">Nexus Mods</span> account type and internet speed.
    </div>
  </div>

</div>

### <a href="https://www.nexusmods.com/newvegas/mods/97094?tab=files">Manual Installation</a>
<div class="guide-box">
  <div style="margin-top: 0;">
	  <p>Alternatively, <span class="highlight">DUSTy Roads</span> can also be installed from disk by first downloading the <code>.wabbajack</code> file.</p> 
	  <ul>
		<li>Download the main file <span class="highlight">DUSTy Roads - Wabbajack</span></li>
		<li>Open <span class="highlight">Wabbajack</span>, click on <span class="highlight">Browse lists</span>, and click the <span class="highlight">Install from disk</span> button on the top-right side</li>
		<li>Locate the downloaded <code>DUSTy Roads.wabbajack</code> file, then follow the installation instructions above.</li>
	  </ul>	
  </div>  
</div>

---

## Post-Installation
<p>Just as before the installation, a few manual steps are required before you can start playing.</p>

### Files for the Game Root Folder
<div class="guide-box" style="flex-direction: column;">
  <p>Some files that are not managed by <span class="highlight">MO2</span> need to be copied manually to the game's <span class="highlight">root folder</span>.</p>
  
  <div>
    <ol>
	  <li>In the installation folder of the <span class="highlight">DUSTy Roads Wabbajack</span>, open the <span class="highlight">_Manual Install</span> folder</li>
	  <li>Copy everything from this folder to the game's <span class="highlight">root folder</span>:</li>
	  	<ul>
		  <li><span class="highlight">xNVSE</span> files</li>
		  <li><span class="highlight">FNV BSA Decompressor</span> files</li>
		  <li><span class="highlight">FNV 4GB Patcher</span> executable</li>
		</ul>
	</ol>	
  </div>	

  <div class="infobox-info">
    <div class="infobox-title"><span class="icon-info"></span> Information</div>
    <div class="infobox-content">
      The root folder is the main directory where the game is installed; the directory containing <code>FalloutNV.exe</code>.
    </div>
  </div>
</div>  

### FNV BSA Decompressor
<div class="guide-box" style="flex-direction: column;">
  <p>Decompresses FNV's BSAs and repacks them without zlib compression for performance, and transcodes the sound effects.</p>
  
  <ol>
      <li>Run <code>FNV BSA Decompressor.exe</code></li>
	  <li>The paths should be auto-filled. If not, complete with the path of your <span class="highlight">FNV</span> installation. Click <code>Decompress</code> and wait for it to finish</li>
  </ol>
</div>

### FNV 4GB Patcher
<div class="guide-box" style="flex-direction: column;">
  <p>A patcher that enables 4GB memory access for FNV and automatically loads xNVSE</p>
  
  <ol>
      <li>Run <code>FNVpatch.exe</code>, and a window will open with the text <code>“FalloutNV.exe patched!”</code></li>
	  <li>Close the window and you'll see <code>FalloutNV_backup.exe</code> appeared (the original unpatched executable)</li>
  </ol>
</div>

### Mod Organizer 2 Setup
<div class="guide-box" style="flex-direction: column;">
  <ol>
    <li>Launch <code>ModOrganizer.exe</code> from the <span class="highlight">DUSTy Roads</span> installation folder</li>
	<li>A <span class="highlight">Register?</span> pop-up might appear: Select <code>Yes</code></li>
	<li>Run the game with the <span class="highlight">Fallout Launcher</span>, not <span class="highlight">New Vegas</span></li>
	<li>Click <code>Options</code></li>
	<li>Select the <span class="highlight">Ultra</span> preset (or another preset accordingly to your system specifications)</li>
	<li>Set the resolution to your monitor's native resolution</li>
	<li>Exit the launcher, and change the program back to <span class="highlight">New Vegas</span></li>
  </ol>	
  
  <div class="infobox-info">
        <div class="infobox-title"><span class="icon-info"></span> Information</div>
        <div class="infobox-content">
          If your resolution is not listed in the launcher, you can set it manually in <code>FalloutPrefs.ini</code>.<br>
		  <img src="/dusty-roads/images/tools.png" alt="MO2 tools" style="width:16px; height:16px; vertical-align:middle;"> Click the <code>Tools</code> button in the toolbar.<br>
		  <ol>
		    <li>Select <code>INI Editor</code></li>
			<li>Go to the <span class="highlight">FalloutPrefs.ini</span> tab</li>
			<li>Go to the <code>Display</code> section, and set the following values:<br>
			<code>iSize W</code>= screen width (e.g., 2560)<br>
			<code>iSize H</code>= screen height (e.g., 1440)</li>
			<li>Click the <code>Save</code> button</li>
			
		  </ol>  
        </div>
    </div>
</div>	
<br>

## Finish
<div style="padding: 1.5rem; border-top: 2px solid hsl(35, 80%, 55%); border-bottom: 2px solid hsl(35, 80%, 55%); margin: 1rem 0;">
  <p style="margin-top:0;">Done. That's it. Your descent into cannibalism can now begin. Select the appropriate profile from the drop-down menu at the top of the left pane:</p>
  <ul style="margin-bottom:0;">
    <li><span class="highlight">DUSTy Roads - Base</span>: featuring <span class="highlight">DUST</span> and essential fixes.</li>
    <li><span class="highlight">DUSTy Roads - Expanded</span>: base version with major expansions and additional gameplay enhancements.</li>
  </ul>
  <p>And make sure <span class="highlight">New Vegas</span> is selected in the <span class="highlight">Run</span> drop-down menu, not <span class="highlight">NVSE</span>!
  <br>
  <img src="/dusty-roads/images/newvegas.png" alt="Run New Vegas"; margin:auto;"><br>
  
</div>
<br>

## How to Update?
<div>
  <p>Each time a new update is released, the following steps are required:</p>
    <ol>
	  <li>Before updating, always consult the <a href="../changelog/" target="_blank"  style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">changelog</a> for details on new additions, removals, fixes, and any manual update instructions. Existing saves are generally compatible unless noted otherwise.</li>
	  <li>Launch <span class="highlight">Wabbajack</span> and use the same installation folder as the existing mod list installation.</li>
	</ol>

    <div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        If you added any mods after the installation, add the <code>[NoDelete]</code> prefix to their names in the left pane. Keep in mind that these mods may still be moved or disabled after updating the mod list.		
	  </div>
	</div>
</div>	

## Support
<div>
  <p>If you get stuck or run into any issues, we’ve got your back. Join our <a href="https://discord.gg/AJxH6mFTnE">DUST Discord server</a> and navigate to the <code>#support-and-bugs-dust</code> channel. You can make a new post and tag it appropriately. When asking for support, please follow these simple rules:</p>
  <ul>
    <li>You did some effort to look into the matter yourself.</li>
    <li>You followed the installation instructions.</li>
	<li>You did not install an ungodly amount of additional mods.</li>
    <li>You will share your load order, and mod list (and crashlog in case of CTDs).</li>
    <li>Please keep things polite and clear. I work on this in my spare time, and I don't have a lot of it.</li>
  </ul>
  
  <p>You can also check the guide's <a href="../support/#faq" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">FAQ</a> for solutions to common issues.</p>
  
  <div class="infobox-info">
      <div class="infobox-title"><span class="icon-info"></span> Information</div>
      <div class="infobox-content">
        Copy-paste from <span class="highlight">Wabbajack</span>:<br>
		<blockquote style="border-left: 2px solid hsl(35, 80%, 55%); margin: 0; padding-left: 0.8rem; font-style: italic; color: hsl(30, 15%, 60%);">
        "Do not contact mod or guide authors for support.<br> 
		If you use a Wabbajack modlist, only go to that list's curator for support on any issues you may have."</blockquote>
		
	  </div>	
  </div><br>
  
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

<br>
<div class="guide-box" style="flex: 1; border: 1px solid hsl(35, 80%, 45%); display: flex; align-items: center;">
  <p style="margin: 0; font-size: 1.1em;">If you're confident enough to get your hands dirty, you can have a look at the <a href="../optional/#optional-mods" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">ADDITIONAL MODS</a> section for more content.</p>
</div>

<br>
<br>

<div style="display: flex; justify-content: center; gap: 20px;">

  <a href="https://ko-fi.com/krrptd0238">
    <img src="https://uploads-ssl.webflow.com/5c14e387dab576fe667689cf/61e11d5cf697cee7ca5b65d9_Button-p-500.png" alt="Ko-Fi">
  </a>

</div>


