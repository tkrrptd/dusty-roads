# PREPARATION

<p>Before deep diving into modding, it’s essential to start with a clean and  <span class="warn">non-pirated</span> <span class="highlight">Fallout: New Vegas (FNV)</span> installation and a stable system environment. While the game itself is over 15 years old and its <a href="https://help.bethesda.net/#en/answer/16744"  target="_blank">vanilla requirements</a> are modest, a modded setup can place significantly more strain on low-end systems.</p>

As a baseline, you should have at least:
<ul>
  <li>8 GB of RAM,</li>
  <li>an SSD (strongly recommended),</li>
  <li>and a CPU and GPU roughly equivalent to a mid-range system from the past decade or newer.</li>
</ul>

## <a href="https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/" target="_blank">VC++ Redistributables</a>
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
    <p>A clean installation is <span class="highlight">strongly</span> recommended to make sure no leftover files from previous modding attempts can cause issues, and to guarantee the game is installed in a safe location. A safe location means avoiding Windows default directories such as <code>Program Files</code>, as well as folders managed by services like <span class="warn">OneDrive</span>, which can silently overwrite or restore files.<br>    
    Whether you’re using <span class="highlight">Steam</span> or <span class="highlight">GOG</span>, start by uninstalling the game through your library. Then manually delete any remaining files in the installation directory (e.g. <code>steamapps\common\Fallout New Vegas</code>), as well as the <code>Documents\My Games\FalloutNV</code> folder.</p> 
	
  </div>
  
</div>

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
	
	<span style="font-weight: bold;"><u>Steam specific:</u></span><br>
	If your Steam Library is currently located in a default Windows directory, or if you are unsure how to set up a custom library location, you can use the <a href="https://github.com/LostDragonist/steam-library-setup-tool/releases" target="_blank">Steam Library Setup Tool &#10515;</a>.</p>
	
	<ol>
	  <li>Close <span class="highlight">Steam</span></li>
	  <li>Run the downloaded setup tool and add a new entry (<code>Add Row</code>)</li>
	  <li>Click <code>Accept</code>, confirm when prompted to create a new folder, and exit the tool</li>
	  <li>Open <span class="highlight">Steam</span>, install <span class="highlight">FNV</span> and when asked for install folder, select the newly created library folder</li>
	</ol>
	
  </div>	

</div>

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

