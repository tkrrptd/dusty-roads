# PREPARATION

<p>Before deep diving into modding, it’s essential to start with a clean and  <span class="warn">non-pirated</span> <span class="highlight">Fallout: New Vegas (FNV)</span> installation and a stable system environment. Only the English version of the game is supported, from either <span class="highlight">Steam</span>, <span class="highlight">GOG</span>, or the <span class="highlight">Epic Games Store</span>. <span class="highlight">Microsoft Store</span> is not supported.<br>
While the game itself is over 15 years old and its <a href="https://help.bethesda.net/#en/answer/16744"  >vanilla requirements</a> are modest, a modded setup can place significantly more strain on low-end systems.</p>

As a baseline, you should have at least:
<ul>
  <li>8 GB of RAM,</li>
  <li>An SSD (strongly recommended) with approximately 20 GB of free space,</li>
  <li>and a CPU and GPU roughly equivalent to a mid-range system from the past decade or newer.</li>
</ul>

<div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        This guide has been developed and tested on <span class="highlight">Windows</span>. <span class="highlight">Linux</span> has not been tested or verified by me. Although the guide may work through <span class="highlight">Proton/Wine</span>, compatibility is not guaranteed, and <span class="highlight">Linux</span> installations are not supported. Support is provided only for <span class="highlight">Windows</span> installations that follow this guide.
	  </div>	
</div>

---

## <a href="https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/" >VC++ Redistributables</a>
<div class="guide-box">
  
  <div>
    <p>VC++ Redistributables are runtime libraries published by Microsoft that contain the compiled code for common C++ standard library functions, on which most modding tools rely. By installing the AIO package, you ensure you have the right version installed and won’t encounter crashes on game launch or when using certain modding tools.</p>
    
    <ol>
      <li>Extract the zip-archive</li>
	  <li>Run the <code>install_all.bat</code> (as administrator)</li>
	  <li>Restart your PC to complete the installation</li>
    </ol>
  </div>

</div>

## Disable Base Address Randomization
<div class="guide-box">
  
  <div>
    <p>Base Address Randomization is a Windows security feature that loads executables and DLLs at randomized memory addresses every time a process starts, rather than fixed/predictable ones. Disabling this setting prevents Windows from forcibly randomizing memory addresses for applications that weren’t designed for it, which can otherwise break certain modding hooks.</p>
    
    <ol>
      <li>Open Windows Security</li>
	  <li>Open <code>App & Browser Control</code></li>
	  <li>Open <code>Exploit Protection Settings</code></li>
	  <li>Make sure <code>Force randomization for images (Mandatory ASLR)</code> is set to <code>Use default (off)</code></li>
    </ol>
  </div>

</div>

## Enable File Extensions
<div class="guide-box">
  
  <div>
    <p>By default, Windows does not display file extensions. File extensions are the suffixes at the end of file names that indicate the file type (such as .exe, .dll, or .esp). These extensions are important when following this guide, so it is highly recommended to enable them.</p>
	
	<span class="highlight">Windows 11:</span>	
	  <ol>
	    <li>Open <span class="highlight">File Explorer</span></li>
	    <li>Open the drop-down menu by clicking <code>View</code> in the menu bar at the top</li>
	    <li>Under <code>Show</code>, enable <code>File name extensions</code>
	  </ol>
	<br>  
	<span class="highlight">Windows 10:</span>
	  <ol>
	    <li>Open <span class="highlight">File Explorer</span></li>
	    <li>Go to the <code>View</code> tab</li>
	    <li>Enable <code>File name extensions</code>
	  </ol>  
  </div>
  
</div>  


## Fallout New Vegas Installation

### Uninstalling FNV
<div class="guide-box">

  <div>
    <p>A clean installation is <span class="highlight">strongly</span> recommended to make sure no leftover files from previous modding attempts can cause issues, and to guarantee the game is installed in a safe location. A safe location means avoiding Windows default directories such as <code>Program Files</code>, as well as folders managed by services like <span class="warn">OneDrive</span>, which can silently overwrite or restore files.</p> 
  </div>
  
</div>

=== "STEAM"
    1. Open <span class="highlight">Steam</span> and go to your <span class="highlight">Library</span>
    2. Find <span class="highlight">Fallout New Vegas</span> and right-click > <span class="highlight">Manage</span> > <span class="highlight">Uninstall</span>
    3. Navigate to <code>...\steamapps\common\</code> and delete the <span class="highlight">Fallout New Vegas</span> folder
    4. Navigate to <code>Documents\My Games</code> and delete the <span class="highlight">FalloutNV</span> folder

=== "GOG"
    1. Open <span class="highlight">GOG Galaxy</span> and go to your <span class="highlight">Installed games</span>
    2. Find <span class="highlight">Fallout New Vegas</span>, click <span class="highlight">Manage Installation</span> > <span class="highlight">Uninstall</span>. In case of an offline installer, run <code>unins000.exe</code> in the game's root folder
    3. Navigate to <code>Documents\My Games</code> and delete the <span class="highlight">FalloutNV</span> folder

=== "EPIC"
    1. Open the <span class="highlight">Epic Games Launcher</span> and go to your <span class="highlight">Library</span>
    2. Find <span class="highlight">Fallout New Vegas</span> and click the <span class="highlight">•••</span> > <span class="highlight">Uninstall</span>
    3. Navigate to <code>Documents\My Games</code> and delete the <span class="highlight">FalloutNV</span> folder

### Installing FNV
<div class="guide-box">  
  
  <div>
    <p>Install or reinstall <span class="highlight">FNV</span> as usual, though make sure to select an installation folder outside any default Windows directories. Instead, install the game in the root of a drive, for example <code>D:\SteamLibrary\steamapps\common\Fallout New Vegas</code>, preferably on an SSD, for the best stability and performance.<br>
	
	<div class="infobox-info">
      <div class="infobox-title"><span class="icon-info"></span> Information</div>
      <div class="infobox-content">
        The root of a drive is the top-level directory (e.g., <code>C:\</code>) that is not inside any other folder. 
	  </div>	
    </div>
	
	<span style="font-weight: bold;"><u>STEAM specific:</u></span><br>
	If your Steam Library is currently located in a default Windows directory (e.g. <code>C:\Program Files (x86)</code>, or if you are unsure how to set up a custom library location, you can use the <a href="https://github.com/LostDragonist/steam-library-setup-tool/releases" >Steam Library Setup Tool &#10515;</a>.</p>
	
	<ol>
	  <li>Close <span class="highlight">Steam</span></li>
	  <li>Run the downloaded setup tool and add a new entry (<code>Add Row</code>)</li>
	  <li>Click <code>Accept</code>, confirm when prompted to create a new folder, and exit the tool</li>
	</ol>
	
  </div>	

</div>

=== "STEAM"
    1. Open <span class="highlight">Steam</span> and go to your <span class="highlight">Library</span>
    2. Find <span class="highlight">Fallout New Vegas</span> and right-click > <span class="highlight">Install</span>
    3. Select a library folder, either on a drive other than your Windows drive or one created with the <span class="highlight">Steam Library Setup Tool</span> and click <span class="highlight">Install</span>

=== "GOG"
    1. Open <span class="highlight">GOG Galaxy</span> and go to your <span class="highlight">Owned games</span>
    2. Find <span class="highlight">Fallout New Vegas</span> and click <span class="highlight">Install</span>
    3. In the pop-up window, set the <span class="highlight">Install to</span> location to a folder outside of any default Windows folder, and click <span class="highlight">Install</span>

=== "EPIC"
    1. Open the <span class="highlight">Epic Games Launcher</span> and go to your <span class="highlight">Library</span>
    2. Find <span class="highlight">Fallout New Vegas</span> and click on the game to install it
    3. In the pop-up window, set the <span class="highlight">Install to</span> location to a folder outside of any default Windows folder, and click <span class="highlight">Install</span>

### Generating INI files
<div class="guide-box">  
  
  <div>
    <p>Before setting up a mod manager and installing mods, it’s important to generate fresh INI files. INI files are configuration files that store game settings, which are read by the game on startup. You can do this simply by launching <span class="highlight">FNV</span> once through <span class="highlight">Steam</span> or <span class="highlight">GOG Galaxy</span>. Confirm when prompted to detect video hardware, then exit.</p>
	
	<div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        If no pop-ups appear when you run the game, it means the INI files from a previous installation weren’t deleted. Go to <code>Documents\My Games\FalloutNV</code>, delete all INI files, and then try running the game again.
	  </div>	
    </div>
	
  </div>
  
</div>

