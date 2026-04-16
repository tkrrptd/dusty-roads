# LOD GENERATION

<p><span class="highlight">LOD</span> (Level of Detail) refers to simplified versions of distant objects in the game world, such as terrain, buildings, and trees. Instead of rendering full-detail models far away, the game uses lower-detail versions to improve performance. As you move closer, these objects gradually switch to their full-detail versions. Proper LOD ensures distant landscapes look consistent and reduces visual pop-in while keeping the game running smoothly.</p>

<ol>
	<li><span class="highlight">Objects</span> LOD: Displays simplified versions of distant structures and objects (like buildings and ruins).</li>
	<li><span class="highlight">Terrain</span> LOD: Renders the distant landscape (hills, ground, roads) as a lower-detail mesh to create a seamless horizon.</li>
	<li><span class="highlight">Tree</span> LOD: Primarily used for small flora (bushes, shrubs), while larger trees are often handled by objects LOD.</li>
</ol>

<p>Why generate LOD if it’s already included in a mod or in this guide? Because LOD is static and does not account for changes made by other mods. By generating LOD yourself, you ensure the visuals accurately reflect your specific mod setup. <span class="highlight">Dust Community Fixes and Tweaks</span> only includes terrain LOD for the Wasteland, primarily to address water LOD in the drained Colorado River and Lake Mead, but it does not provide object or tree LOD. For that reason, generating LOD yourself is always recommended.</p>

<p class="fake-h3">Create a separator</p> 
Right-click in the left pane of MO2 and select <code>Create separator</code>. Name it <span class="fake-h3">LOD</span>.

## Required Resources

### <a href="https://www.nexusmods.com/newvegas/mods/58562" target="_blank">FNVLODGen</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/58562-1-1432921531.jpg" alt="FNVLODGen">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">FNVLODGen Resources</span></li>
	  <li>Hide the <code>FNVLODGen.esp</code> plugin</li>
    </ol>
  	
	<div class="infobox-info">
      <div class="infobox-title"><span class="icon-info"></span> Information</div>
      <div class="infobox-content">
        You can either delete the file, hide the file, or move it away. We'll do the latter, so you can easily retrieve it when required:<br>
		  <ol>
			<li>Double click the mod in the left pane</li>
			<li>Go to the <span class="highlight">Optional Plugins</span> tab</li>
			<li>Select the plugin in the right table (<span class="highlight">Available Plugins</span>) and click on the green arrow pointing left</li>
			<li>The plugin is now moved to <span class="highlight">Optional Plugins</span></li>
		  </ol>
	  </div>
    </div>
	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/64805" target="_blank">Much Needed LOD</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/64805/64805-1523055451-793332593.jpeg" alt="Much Needed LOD">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">Much Needed LOD</span></li>
	  <li>Hide the <code>MuchNeededLOD.esp</code> plugin</li>
    </ol>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/81524" target="_blank">Much Needed LOD fixed rocks color</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/81524/81524-1686493430-941294059.png" alt="Much Needed LOD fixed">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">Much Needed LOD fixed rocks color</span></li>
	</ul>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/61206" target="_blank">LOD additions and improvements</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/61206-0-1451845583.jpg" alt="LOD additions">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">LODadditions</span></li>
	  <li>Hide the <code>tmzLODadditions.esp</code> plugin</li>
    </ol>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/72099" target="_blank">FNV LOD Supplementation</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/72099/72099-1618781091-585013970.png" alt="LOD Supplementation">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">FNV LOD Supplementation</span></li>
	  <li>Download the optional file <span class="highlight">Optional Overpasses</span></li>
	</ul>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/70155" target="_blank">TCM's LOD Overhaul</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/70155/70155-1729410224-769051876.png" alt="TCM LOD">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">TCM's LOD Overhaul</span></li>
	  
	</ul>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/81751" target="_blank">More LODs Additions and fixes</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/81751/81751-1687463780-454868802.png" alt="More LOD Additions">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">More LODs Additions and fixes</span></li>
	  
	</ul>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/83316" target="_blank">Wasted LOD - Cliffs of Mojave</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/83316/83316-1696324892-1114409732.png" alt="Wasted LOD">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">Version 1.0</span></li>
	  <li>Hide the <code>Wasted Mojave Rock LOD.esp</code> plugin</li>
    </ol>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/81981" target="_blank">Different LOD mods little tweaks and additions</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/81981/81981-1688571392-935523143.png" alt="Different LOD tweaks">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">Different LOD mods little tweaks and additions</span></li>
	  
	</ul>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/84165" target="_blank">LODIFY - Level of detail improvement for your Fallout (TTW And NV Lods)</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/84165/84165-1702935954-1498962530.png" alt="LODIFY">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">LODIFY</span></li>
	  <li>Download the optional file <span class="highlight">LODIFY FNV Wall_SoGB Editon</span></li>
	  <li>Hide the <code>TTWLods.esp</code> and <code>LODIFY_FNV.esp</code> plugins</li>
    </ol>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/88979" target="_blank">Decent LOD Kit</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/88979/88979-1735939651-1623842502.jpeg" alt="Decent LOD">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">Decent LOD Kit</span></li>
	  <li>Hide the <code>Decent LOD Kit.esp</code> plugin</li>
    </ol>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/90327" target="_blank">TTW Fallout 3 LOD</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/90327/90327-1741509621-1210897503.png" alt="TTW LOD">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">TTW Fallout 3 LOD</span>. Yes, it says <span class="highlight">TTW</span>, and yes you need it.</li>
	  <li>Hide the <code>TTW Fallout 3 LOD.esp</code> plugin</li>
    </ol>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/93393" target="_blank">Physically Based LOD</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/93393/93393-1755391477-2075757264.png" alt="Physically Based LOD">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">Physically Based LOD</span></li>
	  
	</ul>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/88902" target="_blank">Nuclear LOD</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/88902/88902-1728923685-628362077.png" alt="Nuclear LOD">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the main file <span class="highlight">Nuclear Core</span></li>
	  <li>Download the main file <span class="highlight">Nuclear Trees - Vanilla</span></li>
	  <li>Hide the <code>Nuclear_LOD.esp</code> and <code>TreeLOD_Vanilla.esp</code> plugins</li>
    </ol>
  	
  </div>
  
</div>


### <a href="https://www.nexusmods.com/newvegas/mods/88898" target="_blank">High Priority LOD</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/88898/88898-1724768957-801881589.png" alt="High Priority LOD">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">High Priority Core - with NVMIM</span></li>
	  <li>Download the main file <span class="highlight">High Priority Trees - Vanilla</span></li>
	</ul>
  	
  </div>
  
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/97094" target="_blank">DUSTy Roads - LOD Plugin</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/97094/97094-1775140780-122210232.png" alt="DUSTy Roads">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the main file <span class="highlight">DUSTy Roads - LOD Plugin</span>. This will overwrite the LOD plugin shipped with <span class="highlight">DUST Community Fixes & Tweaks</span></li>
	  
	</ul>
  	
  </div>
  
</div>

<div class="infobox-decision">
  <div class="infobox-title"><span class="icon-decision"></span> Decision</div>
  <div class="infobox-content" style="padding: 1rem; font-size: 1.1em;">
    <p style="margin-top:0; font-family: 'Bebas Neue', cursive; font-size: 1.2em; letter-spacing: 0.05em;">To LOD or not to LOD?</p>
    <ul style="margin-bottom:0; list-style:none; padding-left:0;">
      <li style="margin-bottom: 0.6em;"><span class="icon-path-right"></span> If you've followed this guide closely and haven't added (or don't plan to add) mods that alter textures or the game world, you can skip generating LOD and simply use the <a href="../lod/#dusty-roads-pregenerated-lod">Pregenerated LOD</a> below.</li>
      <li><span class="icon-path-left"></span> If you didn't, or prefer to generate it yourself, skip the pregenerated LOD and proceed to <a href="../lod/#generate-lod">Generate LOD</a>.</li>
    </ul>
  </div>
</div>

### <a href="https://www.nexusmods.com/newvegas/mods/97094" target="_blank">DUSTy Roads - Pregenerated LOD</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/97094/97094-1775140780-122210232.png" alt="DUSTy Road">

  <div style="margin-top: 0;">
    <ul>
      <li>Download the optional file <span class="highlight">DUSTy Road - Pregenerated Objects LOD</span></li>
	  <li>Download the optional file <span class="highlight">DUSTy Road - Pregenerated Terrain LOD</span></li>
	</ul>
	
	<p>You still need the installed LOD resources, but you should disable these two in the left pane of <span class="highlight">MO2</span>:</p>
	  <ul>
		<li><span class="highlight">High Priority Core</span></li>	
		<li><span class="highlight">High Priority Trees - Vanilla</span></li>
	  </ul>
  	
  </div>
  
</div><br>

## Generate LOD

### <a href="https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-132-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/" target="_blank">xLODGen - Terrain LOD</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/130/images/58562-1-1432921531.jpg" alt="xLODGen">

  <div style="margin-top: 0;">
    <ol>
      <li>Download the file <span class="highlight">xLODGen beta 132</span></li>
	  <li>Extract the 7z-archive to a folder on the same drive as <span class="highlight">FNV</span> and <span class="highlight">MO2</span> (and not a default Windows folder!)</li>
	  <li>Add <code>xLODGenx64.exe</code> as an executable to <span class="highlight">MO2</span> (see <a href="../mo2/#adding-executables">Adding Executables</a>)</li>
	  <li>Add <code>-fnv -O:"D:\xLODGen Output"</code> in the arguments field. Pick a location of your choice - generated LOD will be written to this folder</li>
	</ol>
  	
	<div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        Do not use the <span class="highlight">FNVLODGen</span> version on <span class="highlight">Nexus Mods</span>. It is outdated and may produce broken LOD.
	  </div>	
    </div>
  	
  </div>
	
</div>


### Terrain LOD

<div style="display: flex; gap: 0; margin-bottom: 20px;">
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px 0 0 5px;">
    <p style="margin-top: 0;">When generating LOD, you always start with terrain LOD. Whenever a new mod is installed that modifies terrain, or terrain textures, terrain LOD needs regenerating.</p>
    
    <div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        Before starting, make sure the output folder is empty!
      </div>	
    </div>
	
    <ol>
      <li>Select <span class="highlight">xLODGen</span> from the executables drop-down in <span class="highlight">MO2</span> and run it</li>
      <li>Right click in the <span class="highlight">worldspaces</span> pane and choose <code>Select All</code></li>
	  <li>In the right pane make sure only <span class="highlight">Terrain LOD</span> is enabled</li>
	  <li>There are 4 quality levels: <span class="highlight">LOD4</span>, <span class="highlight">LOD8</span>, <span class="highlight">LOD16</span>, and <span class="highlight">LOD32</span>. By toggling the <code>Settings for</code> drop-down, you can set settings per quality level. Use the same settings as in the screenshots below.</li>
	  <li>Click <code>Generate</code> and wait until you get notified <code>LOD generation done</code>. Close <span class="highlight">xLODGen</span></li>
	  <li><img src="/dusty-roads/images/settings.png" alt="Open list options"> Click the <code>Open list options...</code> button on top of the left pane in <span class="highlight">MO2</span> (not the toolbar!), and select <code>Create empty mod</code></li>
	  <li>Name the newly created mod <span class="highlight">FNVLODGen Output - Terrain</span>, and make sure it is placed last in the left pane</li>
	  <li>Navigate to the output folder (the one set in the <span class="highlight">xLODGen</span> arguments), and move both folders (<code>Meshes</code> and <code>Textures</code>) to the <span class="highlight">FNVLODGen Output - Terrain</span> mod</li>
	  <li>Make sure the mod is enabled by clicking the checkbox</li>
    </ol>
  </div>
  
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:0 5px 5px 0; display: flex; align-items: center; justify-content: center;">
    <img src="/dusty-roads/images/xlodgen-worldspaces.png" style="max-width: 100%; height: auto;">
	
  </div>
</div>

<div style="background:#2b2925; padding:10px; border-radius:5px; margin-bottom:20px;">

  <div style="display: flex; gap: 0; margin-bottom: 10px;">
    <div style="flex: 1; display: flex; align-items: center; justify-content: center;">
      <img src="/dusty-roads/images/xlodgen-lod4.png" alt="LOD4" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 1; display: flex; align-items: center; justify-content: center;">
      <img src="/dusty-roads/images/xlodgen-lod8.png" alt="LOD8" style="max-width: 100%; height: auto;">
    </div>
  </div>

  <div style="display: flex; gap: 0;">
    <div style="flex: 1; display: flex; align-items: center; justify-content: center;">
      <img src="/dusty-roads/images/xlodgen-lod16.png" alt="LOD16" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 1; display: flex; align-items: center; justify-content: center;">
      <img src="/dusty-roads/images/xlodgen-lod32.png" alt="LOD32" style="max-width: 100%; height: auto;">
    </div>
  </div>

</div>

### Objects LOD

<div style="display: flex; gap: 0; margin-bottom: 20px;">
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px 0 0 5px;">
    <p style="margin-top: 0;">As with terrain LOD, any mod that alters world objects or textures requires regenerating Objects LOD.</p>
    
    <div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        Before starting, make sure the output folder is empty!
      </div>	
    </div>
	
    <ol>
      <li>Select <span class="highlight">xLODGen</span> from the executables drop-down in <span class="highlight">MO2</span> and run it</li>
      <li>Right click in the <span class="highlight">worlspaces</span> pane and choose <code>Select All</code></li>
	  <li>In the right pane make sure only <span class="highlight">Objects LOD</span> and <span class="highlight">Trees LOD</span> are enabled</li>
	  <li>Use the same settings as the screenshot on the right</li>
	  <li>Click <code>Generate</code> and wait until you get notified <code>LOD generation done</code>. Close <span class="highlight">xLODGen</span></li>
	  <li><img src="/dusty-roads/images/settings.png" alt="Open list options"> Click the <code>Open list options...</code> button on top of the left pane in <span class="highlight">MO2</span> (not the toolbar!), and select <code>Create empty mod</code></li>
	  <li>Name the newly created mod <span class="highlight">FNVLODGen Output - Objects</span>, and make sure it is placed last in the left pane</li>
	  <li>Navigate to the output folder (the one set in the <span class="highlight">xLODGen</span> arguments), and move both folders (<code>Meshes</code> and <code>Textures</code>) to the <span class="highlight">FNVLODGen Output - Objects</span> mod</li>
	  <li>Make sure the mod is enabled by clicking the checkbox</li>
    </ol>
  </div>
  
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:0 5px 5px 0; display: flex; align-items: center; justify-content: center;">
    <img src="/dusty-roads/images/xlodgen-object.png" alt="Objects and Trees LOD" style="max-width: 100%; height: auto;">
	
  </div>
</div>

### Disabling Mods
<div style="display: flex; gap: 0; margin-bottom: 20px;">
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px 0 0 5px;">
	<p>Once LOD generation is complete, some mods that are only needed during the generation process can be disabled. Leaving them enabled may cause visual issues. But don’t forget to re-enable them before generating LOD again!</p>
	  <ul>
		<li><span class="highlight">High Priority Core</span></li>	
		<li><span class="highlight">High Priority Trees - Vanilla</span></li>
	  </ul>
  </div>  
</div>
 
### Packing LOD in bsa Archives
<div style="display: flex; gap: 0; margin-bottom: 20px;">
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px 0 0 5px;">
	<p>This step is optional, but strongly recommended. This will positively affect the loading times of LOD assets in-game. There are a few caveats however:</p>
	  <ul>
		<li><span class="highlight">bsa</span> archives require a plugin to be loaded. So the name of the archive should equal that of the plugin, with the suffix <span class="highlight">- Objects</span> and <span class="highlight">- Terrain</span></li>
		<li>Loose files will always override archived files! Check <span class="highlight">MO2</span>'s left pane for <a href="../mo2/#conflict-resolution">conflicts</a> and act accordingly to ensure the right file is conflict winner</li>
		<li>An <code>.override</code> file is necessary to allow archived files to override other archived files (a <span class="highlight">JIP LN</span> feature)</li>
	  </ul>	

	<div class="infobox-decision">
	  <div class="infobox-title"><span class="icon-decision"></span> Decision</div>
	  <div class="infobox-content" style="padding: 1rem;>
		<span style="display:block; margin-bottom:4px;"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16" fill="hsl(150, 50%, 70%)" style="vertical-align: middle; margin-right: 4px;"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm1.5 0a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Zm10.28-1.72-4.5 4.5a.75.75 0 0 1-1.06 0l-2-2a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018l1.47 1.47 3.97-3.97a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path></svg> <u>When to pack:</u></span>
		<ul>
		  <li>I want an optimized game and avoid potential stuttering when loading new areas in-game</li>
		  <li>I am able to resolve asset conflicts and get rid of LOD included in other mods as loose files</li>
		</ul>
		<span style="display:block; margin-top:8px; margin-bottom:4px;"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16" fill="hsl(0, 70%, 75%)" style="vertical-align: middle; margin-right: 4px;"><path d="M2.344 2.343h-.001a8 8 0 0 1 11.314 11.314A8.002 8.002 0 0 1 .234 10.089a8 8 0 0 1 2.11-7.746Zm1.06 10.253a6.5 6.5 0 1 0 9.108-9.275 6.5 6.5 0 0 0-9.108 9.275ZM6.03 4.97 8 6.94l1.97-1.97a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l1.97 1.97a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-1.97 1.97a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L6.94 8 4.97 6.03a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018Z"></path></svg> <u>When not to pack:</u></span>
		<ul>
		  <li>I don’t want to deal with checking file conflicts</li>
		</ul>
	  </div>
	</div>
  </div>
</div>  

#### <a href="https://www.nexusmods.com/fallout4/mods/63243" target="_blank">BSArchPro</a>
<div class="guide-box">
  
  <img src="https://staticdelivery.nexusmods.com/mods/1151/images/63243/63243-1769254695-1137142480.png" alt="BSArchPro">

  <div style="margin-top: 0;">
    <p style="margin-top: 0;">A tool for packing and unpacking Bethesda archives.</p>
    
    <ol>
      <li>Download the optional file <span class="highlight">BSArchPro</span></li>
	  <li>Extract the zip-archive to a folder of your choice and run <code>BSArchPro.exe</code></li>
	</ol>
  		
  </div>
  
</div>

#### Packing Object LOD

<div style="display: flex; gap: 0; margin-bottom: 20px;">
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px 0 0 5px;">
        
    <ol>
      <li>In <span class="highlight">MO2</span>, right click on <span class="highlight">FNVLODGen Output - Objects</span> and select <code>Open in Explorer</code></li>
	  <li>Drag the <code>Textures</code> folder into <span class="highlight">BSArchPro</span></li>
	  <li>Object textures should be compressed (and <span class="warn">only</span> objects textures). In <span class="highlight">BSArchPro</span>'s main window, press <code>Ctrl + a</code> to select all files, use right click and select <code>Set Compressed Where Applicable</code></li>
	  <li>Drag now the <code>Meshes</code> folder into <span class="highlight">BSArchPro</span>, and click the <code>Pack</code> button</li>
	  <li>In the new window, make sure same options are selected as on the screenshot to the right</li>
	  <li>Use the <code>...</code> to select the <span class="highlight">FNVLODGen Output - Objects</span> folder, and use <code>DUST LOD - Objects.bsa</code> as file name</li>
	  <li>Click <code>OK</code> to pack</li>
	  <li>When done, a new window will appear. Click on the <code>Create .override file(s) for New Vegas</code> button, <span class="warn">not</span> the <code>OK</code> button</li>
	  <li>In <span class="highlight">BSArchPro</span>'s main window, click now the <code>Clear List</code>button</li>
	  <li>Delete now both <code>Meshes</code> and <code>Textures</code> folders</li>
	    
    </ol>
  </div>
  
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:0 5px 5px 0; display: flex; align-items: center; justify-content: center;">
    <img src="/dusty-roads/images/bsarchpro-obj.png" alt="BSArchPro Settings" style="max-width: 75%; height: auto;">
	
  </div>
</div>

#### Packing Terrain LOD

<div style="display: flex; gap: 0; margin-bottom: 20px;">
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px 0 0 5px;">
        
    <ol>
      <li>In <span class="highlight">MO2</span>, right click on <span class="highlight">FNVLODGen Output - Terrain</span> and select <code>Open in Explorer</code></li>
	  <li>Drag both <code>Meshes</code> and <code>Textures</code> folder into <span class="highlight">BSArchPro</span>. Terrain textures should <span class="warn">not</span> be compressed!</li>
	  <li>Click the <code>Pack</code> button</li>
	  <li>In the new window, make sure same options are selected as on the screenshot to the right</li>
	  <li>Use the <code>...</code> to select the <span class="highlight">FNVLODGen Output - Terrain</span> folder, and use <code>DUST LOD - Terrain.bsa</code> as file name</li>
	  <li>Click <code>OK</code> to pack</li>
	  <li>When done, a new window will appear. Click on the <code>Create .override file(s) for New Vegas</code> button, <span class="warn">not</span> the <code>OK</code> button</li>
	  <li>In <span class="highlight">BSArchPro</span>'s main window, click now the <code>Clear List</code>button</li>
	  <li>Delete now both <code>Meshes</code> and <code>Textures</code> folders</li>
	  <li>This archive will overwrite the terrain LOD archive included in <span class="highlight">DUST Community Fixes & Tweaks</span></li>
    </ol>
  </div>
  
  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:0 5px 5px 0; display: flex; align-items: center; justify-content: center;">
    <img src="/dusty-roads/images/bsarchpro-ter.png" alt="BSArchPro Settings" style="max-width: 75%; height: auto;">
	
  </div>
</div>
