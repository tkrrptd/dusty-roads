# MOD ORGANIZER 2

<p><span class="highlight">Mod Organizer 2</span>, aka <span class="highlight">MO2</span>, is a powerful and versatile mod manager, primarily used for Bethesda games. Its standout feature is the virtual file system (<span class="highlight">USVFS</span>), which keeps mods separate from the actual game folder. This means you can install or remove mods safely, reorder them at any time via drag-and-drop, maintain multiple profiles, and keep your original game files untouched.</p> 

<p><span class="highlight">MO2</span>’s interface is split into two panes (one for mods, one for plugins) making it easy to spot conflicts and manage load order. Unlike <span class="highlight">Vortex</span>, which relies on a convoluted group/rules system, <span class="highlight">MO2</span> gives you complete control over how mods interact. Additional perks include a fully portable setup, integrated <span class="highlight">Nexus Mods</span> support for direct downloads, and a plugin system that allows advanced users to extend functionality. While <span class="highlight">MO2</span> is generally the superior choice, this doesn’t mean <span class="highlight">Vortex</span> is a bad mod manager: use whichever tool best fits YOUR needs and comfort level. That said, it is <span class="warn">strongly advised</span> to avoid older or unsupported mod managers such as <span class="highlight">FOMM</span>, <span class="highlight">NMM</span> (even the Community Edition), <span class="highlight">Kortex</span>, or <span class="highlight">Wrye Bash</span>. This also includes <span class="highlight">MO1</span>.</p>

---

## <a href="https://www.nexusmods.com/skyrimspecialedition/mods/6194" >Installing Mod Organizer 2</a>
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">

  <div>
    <ol>
      <li>Download the main file (manual download)</li>
	  <li>Run the installer <code>Mod Organizer 2.exe</code></li>
	  <li>When choosing a destination location, pick a location that is not a default Windows directory, not the game folder, not a folder managed by <span class="warn">OneDrive</span>, and not inside another portable <span class="highlight">MO2</span> installation</li>
	  <li>When prompted to <code>Select Components</code>, just click <code>Next</code></li>
	  <li>You can choose a <code>Start Menu</code> folder and desktop shortcut, or not</li>
	  <li>Click <code>Install</code> and wait for it to complete</li>
	  <li>Launch <span class="highlight">MO2</span></li>
	</ol>
  </div>

</div>

## Configuring Mod Organizer 2

### Create an Instance
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">
 
   <div>
     <p>You will have the option to create either a <span class="highlight">global instance</span>, or a <span class="highlight">portable instance</span>. A global instance of <span class="highlight">MO2</span> shares settings, profiles, and mods, while a portable instance keeps everything self-contained in a single folder that can be moved or backed up independently. I recommend using a portable instance.</p>
	 
	 <img src="/dusty-roads/images/instance.png" alt="MO2 instances" style="display:block; margin:0; width:300px;"><br>
	 
	 <ol>
	   <li>From the game list, select <span class="highlight">New Vegas</span></li>
	   <li>Select the applicable game edition</li>
	   <li>Choose a name for the instance, e.g. DUSTy Roads</li>
	   <li>When asked to configure the profile settings, check <span class="warn">all</span> boxes</li>
	   <li>Default location to store data will be under <code>AppData</code>. You can keep this file path, or choose another, but preferably on the same drive as <span class="highlight">FNV</span> and <span class="highlight">MO2</span></li>
	   <li>Finish and launch the new instance</li>
	   <li>A pop-up might appear:
		 <ul>
		   <li><span class="highlight">Show tutorial?</span> Select <code>No</code></li>
		   <li><span class="highlight">Register?</span> Select <code>Yes</code></li>
		   <li><span class="highlight">INI file is read-only?</span> Select <code>Remember my choice</code> in the drop-down and opt for <code>Clear the read-only flag</code></li>
		   <li><span class="highlight">Category setup?</span> Select the option you prefer (I personally don't use the <span class="highlight">Nexus</span> categories)</li>
		 </ul>
     </ol>
   </div> 
   
</div>

### Game Settings
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">
   <div>
      <p><span class="highlight">New Vegas</span> is automatically selected to run (in the top-right corner). But to set a few game settings, change this to <span class="highlight">Fallout Launcher</span>.<br></p>
	  <ol>
	    <li>Run the game with <span class="highlight">Fallout Launcher</span></li>
		<li>Click <code>Options</code></li>
		<li>Select the <span class="highlight">Ultra</span> preset (or another preset accordingly to your system specifications)</li>
		<li>Set the resolution to your monitor's native resolution</li>
		<li>Exit the launcher, and change the program back to <span class="highlight">New Vegas</span></li>
	  </ol>
	 
	  <div class="infobox-info">
        <div class="infobox-title"><span class="icon-info"></span> Information</div>
        <div class="infobox-content">
          If your resolution is not listed in the launcher, you can set it manually in <code>FalloutPrefs.ini</code>.<br>
		  <img src="/dusty-roads/images/tools.png" alt="MO2 tools"> Click the <code>Tools</code> button in the toolbar.<br>
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
	  
	  <p>Thanks to <span class="highlight">JIP LN NVSE</span>, you can use a custom INI to add various settings without touching the main INIs. <span class="highlight">FalloutCustom.ini</span> takes precedence over the other INI files and cannot be modified by the game.<br>
	  <img src="/dusty-roads/images/tools.png" alt="MO2 tools"> Click the <code>Tools</code> button in the toolbar and paste these settings in the <span class="highlight">FalloutCustom.ini</span> tab:<br></p>
	  
	  <textarea readonly="readonly" class="dust-textarea" rows="54" onclick="this.focus();this.select()">
[Audio]
bMultiThreadAudio=1
bUseAudioDebugInformation=0
iAudioCacheSize=16384
iMaxSizeForCachedSound=2048

[BackgroundLoad]
bSelectivePurgeUnusedOnFastTravel=1
bBackgroundLoadLipFiles=1

[Controls]
fForegroundMouseAccelBase=0
fForegroundMouseAccelTop=0
fForegroundMouseBase=0
fForegroundMouseMult=0

[Display]
bFull Screen=0
iPresentInterval=1
iTexMipMapSkip=0
bDrawShadows=0
iActorShadowCountInt=0
iActorShadowCountExt=0
fDefaultWorldFOV=75.0000
fDefault1stPersonFOV=55.0000
fPipboy1stPersonFOV=47.0

[General]
bPreemptivelyUnloadCells=1
iNumHWThreads=3

[Grass]
fGrassStartFadeDistance=11200
b30GrassVS=1

[Water]
bForceHighDetailReflections=0

[BlurShaderHDR]
bDoHighDynamicRange=1

[BlurShader]
bUseBlurShader=0

[PipBoy]
fLightEffectFadeDuration=400

[TerrainManager]
fBlockLoadDistanceLow=30000
fBlockLoadDistance=130000

[SpeedTree]
bForceFullLOD=1</textarea>
	  
   </div>	
</div>
 
### Settings and Workarounds
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">

   <div>
     <p><img src="/dusty-roads/images/settings.png" alt="MO2 settings"> Click the <code>Settings</code> button in the toolbar to access <span class="highlight">MO2</span>'s settings.<br>
	 There are various settings that let you customize how you interact with <span class="highlight">MO2</span>, as well as how it looks and feels (<span class="highlight">Theme</span> tab for example). To keep this guide concise, these options will not be covered, so feel free to explore them yourself. That said, do check these out:</p>
	 <ul>
	   <li><span class="highlight">Nexus</span> tab: here you can connect/disconnect to <span class="highlight">Nexus Mods</span>, and associate <span class="highlight">MO2</span> with <code>Download with manager</code> links. Here, you can also configure your preferred download server.</li>
	   <li><span class="highlight">Workarounds</span> tab: check the option <code>Enable archives parsing (experimental)</code>. This will allow <span class="highlight">MO2</span> to report conflicts in mod's <span class="highlight">bsa</span> archives. Useful for troubleshooting!</li></p>
	 </ul>
   </div>

</div>

### Adding Executables
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">
   <div>
      <p>There are several tools used for modding (such as <span class="highlight">xEdit</span> and the <span class="highlight">GECK</span>) or generate LOD (<span class="highlight">xLODGen</span>). These tools need to be added to <span class="highlight">MO2</span> so they can detect and work with your installed mods.</p>
	  <img src="/dusty-roads/images/exe.png" alt="MO2 configuring executables"> Click the <code>Configuring executables</code> button in the toolbar.
	    <ol>
	      <li>Add an executable by clicking the <code>+</code> button and select <code>Add from file...</code></li>
		  <li>Navigate to the location where the tool is installed, and select the executable (<code>.exe</code> or <code>.bat</code>)</li>
		  <li>You can now give it a name (<span class="highlight">Title</span>) or add arguments (for instance, <code>-fnv</code> for <span class="highlight">xEdit</span>)</li>
		  <li>You can enable additional options based on preference, such as <span class="highlight">Create files in mod instead of overwrite</span>: here you can specify an output mod for new or modified files</li>
	    </ol>	
   </div>

</div>

## Using Mod Organizer 2

### Installing Mods
<div style="background:#2b2925; padding:10px; border-radius:5px; margin-bottom:20px;">
  <p>To install a mod, first download the mod and locate it in the <span class="highlight">Downloads</span> tab (right pane). Double-click the downloaded archive to install. Once installed, the mod will appear in the left pane and can be enabled or disabled by ticking its checkbox. The guide will provide any additional instructions when special installation steps are required.</p>
</div>

### Updating Mods
<div style="background:#2b2925; padding:10px; border-radius:5px; margin-bottom:20px;">
	<p>When updating a mod, download the new version and install it the same way as a normal mod. <span class="highlight">MO2</span> will detect that a mod with the same name already exists and prompt you to either <span class="highlight">Replace</span>, <span class="highlight">Merge</span>, or <span class="highlight">Rename</span> it.</p>
	<ul>
      <li><span class="highlight">Rename</span> appears when you try to install a file with the same name as an already installed mod. If you're installing an additional or optional file for that mod, rename it accordingly, either by selecting a name from the dropdown or entering one manually. This also simplifies updates when only one of the files needs updating.</li>
      <li>If you are updating a mod from an older version, select <span class="highlight">Replace</span>. This will replace <span class="warn">all</span> files from the previous version with the new ones.</li>
      <li><span class="highlight">Merge</span> combines the newly downloaded files with the existing mod installation. It's generally best avoided unless you know exactly what you're doing.</li>
    </ul>
	<p>In most cases, updates should be installed using the <span class="highlight">Replace</span> option. However, some updates only contain a few files intended to be added to the existing installation, in which case <span class="highlight">Rename</span> or <span class="highlight">Merge</span> could be used instead. Always read the update instructions provided by the mod author, and if you are unsure which option to choose, just ask the author.</p>
</div>

### Left Pane vs Right Pane
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">
	<p><span class="highlight">MO2</span> uses two panes to manage your modded setup. The <span class="highlight">left pane</span> controls installed mods and their file priority, determining which mod's assets (textures, meshes, scripts, etc.) take precedence when multiple mods contain the same files. The <span class="highlight">right pane</span> controls plugin load order, determining the order in which game plugins (<code>.esm</code> and <code>.esp</code>) are loaded. The two panes serve different purposes and should be managed independently. By following the guide's instructions in the order they are presented, mods will be installed with conflicts taken into account. Some conflicts are unavoidable and are handled by the guide's <span class="highlight">Compatibility Patch</span>. If you decide to add mods outside of the guide, be sure to read <a href="../mo2/#conflict-resolution">Conflict Resolution</a> thoroughly.</p>
</div>

### Overwrite Folder
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">
    <p>At the bottom of the left pane, you’ll find the <span class="highlight">Overwrite</span> folder. This folder contains all files generated during gameplay (such as configuration files) or created by modding tools. You can leave these files there, or keep your setup organized by creating a new mod from the <span class="highlight">Overwrite</span> contents. Keep in mind that files in <span class="highlight">Overwrite</span> will take priority over other mods, so make sure you know what’s in there and avoid unintentional conflicts. Leaving files unmanaged in <span class="highlight">Overwrite</span> is one of the most common sources of hidden issues!</p>
</div>

### Conflict Resolution
<div style="display: flex; align-items: flex-start; margin-bottom: 20px; background:#2b2925; padding:10px; border-radius:5px;">
   <div>
      <p>Just like plugin load order, the mod load order (<span class="highlight">MO2</span>’s left pane) is equally important. Assets such as textures and meshes are overridden by mods loaded below them (i.e. higher priority). <span class="highlight">MO2</span>’s <code>Flags</code> column provides visual indicators of file conflicts. Reordering mods (via simple drag and drop) may be necessary to resolve them:</p> 
	  <ul>
	    <li><img src="/dusty-roads/images/winner.png" alt="Conflict winner"> means the mod has asset(s) overriding others (conflict winner)</li>
		<li><img src="/dusty-roads/images/loser.png" alt="Conflict loser"> means the mod has asset(s) being overridden by others (conflict loser)</li>
		<li><img src="/dusty-roads/images/both.png" alt="Conflict loser/winner"> means the mod has asset(s) both conflict winners as conflict losers</li>
		<li><img src="/dusty-roads/images/blue.png" alt="Archive conflict"> When a file in a <code>bsa</code> archive is conflicting, the lightning icon will be blue</li>
	  </ul>

	  <p>To find out what file is conflicting, double-click the mod, and go to the <span class="highlight">Conflicts</span> tab:</p>
	    <ul>
		  <li>Top pane shows the <span class="highlight">winning</span> file conflicts</li>
		  <li>Middle pane shows the <span class="highlight">losing</span> file conflicts</li>
		  <li>Bottom pane shows the <span class="highlight">non-conflicting</span> files</li>
		</ul>

	  <p>In case of textures (<code>.dds</code> files), <span class="highlight">MO2</span> allows you to directly compare the conflicting textures. Double-click the texture to open it in a new window and use the arrow buttons in the top-right corner to cycle through the different versions and decide which one should win the conflict.</p>
	  
	  <div class="infobox-info">
        <div class="infobox-title"><span class="icon-info"></span> Information</div>
        <div class="infobox-content">
          Rule of thumb: “Lower = wins. Higher = loses.”
		
        </div>
      </div>
	  
	  <p>To resolve conflicts between plugins (<code>.esm</code> and <code>.esp</code> files), you need a tool like <a href="../resources/#xedit">xEdit</a>. On the <a href="../resources/" style="font-family: 'Special Elite', cursive; font-size: 1.2em; color: hsl(35, 80%, 55%);">Resources</a> page you can find further info on the basics of <span class="highlight">xEdit</span>.
	  
   </div>

</div>	