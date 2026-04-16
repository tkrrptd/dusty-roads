<style>
.md-typeset h2 a::after,
.md-typeset h3 a::after,
.md-typeset h4 a::after {
  content: none;
}
</style>

# RESOURCES

<p>The road into modding is long, and not always forgiving. These resources will help you make it through.</p>

## The Tools

### xEdit
<p><span class="highlight">xEdit</span> is a powerful utility for Bethesda games that lets you inspect and modify plugin files. It presents edits in a structured, side-by-side view, making it easy to see how mods interact with each other and with the base game. With <span class="highlight">xEdit</span>, you can create compatibility patches, analyze what a mod changes, and make your own adjustments where needed. For most use cases, this will be your primary tool for resolving conflicts and creating patches, often without ever needing to open the <span class="highlight">GECK</span>.</p>

<div style="display: flex; gap: 20px; margin-bottom: 20px;">

  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px;">
    <p class="fake-h3" style="margin-top: 0;"><a href="https://discord.gg/5t8RnNQ" target="_blank"><b>xEdit</b></a></p>
	<img src="/dusty-roads/images/xedit.png" alt="xEdit" style="width: 80px; margin-right: 15px; flex-shrink: 0; float: left;">
    <p style="margin-top: 0;">You can always find the latest build on the <span class="highlight">xEdit</span> discord server.</p>
	
	<ol>
      <li>Download the latest build in the <code>#xedit-builds</code> channel</li>
	  <li>Extract the 7z-archive to a folder on the same drive as <span class="highlight">FNV</span> and <span class="highlight">MO2</span> (and not a default Windows folder!)</li>
	  <li>Add <code>xFOEdit.exe</code> as an executable to <span class="highlight">MO2</span> (see <a href="../mo2/#adding-executables">Adding Executables</a>)</li>
	  <li>Add <code>-fnv</code> in the arguments field</li>
	  
	</ol>
    
  </div>

  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px;">
    <p class="fake-h3" style="margin-top: 0;"><a href="https://tes5edit.github.io/docs/" target="_blank"><b>Tome of xEdit</b></a></p>
	<img src="https://tes5edit.github.io/docs/img/tes5edit-ico-blue.png" alt="xEdit" style="width: 80px; margin-right: 15px; flex-shrink: 0; float: left;">
    <p style="margin-top: 0;">A Comprehensive Guide to using xEdit.</p>
   
  </div>

</div>

### GECK
<p>The <span class="highlight">GECK</span>, or <span class="highlight">Garden of Eden Creation Kit</span>, is Bethesda’s official editor for <span class="highlight">FNV</span>, used to create and modify game content. Unlike <span class="highlight">xEdit</span>’s structured, record-based approach, the <span class="highlight">GECK</span> provides an environment where you can work with worldspaces, quests, scripts, and other gameplay elements directly. While more <em>powerful</em>, it is also more complex and less suited for quick adjustments.<br>
The <span class="highlight">GECK</span> can be installed from <span class="highlight">Steam</span>, and it is also bundled with the <span class="highlight">GOG</span> version.</p>

<div class="infobox">
      <div class="infobox-title"><span class="icon-warning"></span> Warning</div>
      <div class="infobox-content">
        The <span class="highlight">GECK</span> is a harsh mistress and often introduces dirty edits. Always clean any modified or newly created plugins with <span class="highlight">xEdit</span>!
	  </div>	
</div>

<div style="display: flex; gap: 20px; margin-bottom: 20px;">

  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px;">
    <p class="fake-h3" style="margin-top: 0;"><a href="https://www.nexusmods.com/newvegas/mods/64888" target="_blank"><b>GECK Extender &#10515;</b></a></p>
	<img src="https://staticdelivery.nexusmods.com/mods/130/images/64888/64888-1524782927-1257241392.jpeg" alt="GECK Extender" style="width: 80px; margin-right: 15px; flex-shrink: 0; float: left;">
    <p style="margin-top: 0;">The GECK Extender is a project to extend the functionality and fix bugs in the Garden of Eden Creation Kit.</p>
    
	<ol>
      <li>Download the main file <span class="highlight">Geck</span> manually and place it in the game’s root folder, replacing the original executable</li>
	  <li>Download the main file <span class="highlight">Geck Extender</span> and install with <span class="highlight">MO2</span> like any other mod</li>
	  <li>Download the main file <span class="highlight">GECK Extender - Config</span> and install with <span class="highlight">MO2</span> like any other mod</li>
	</ol>
	
  </div>

  <div style="flex: 1; background:#2b2925; padding:10px; border-radius:5px;">
    <p class="fake-h3" style="margin-top: 0;"><a href="https://geckwiki.com/index.php?title=Main_Page" target="_blank"><b>The Unofficial Community GECK Wiki</b></a></p>
	<img src="https://geckimg.mod.pub/7/7d/Photo_2017-04-01_00-02-45.jpg" alt="GECK Wiki" style="width: 80px; margin-right: 15px; flex-shrink: 0; float: left;">
    <p style="margin-top: 0;">An unofficial community-run wiki where you'll find everything you need to use The Garden of Eden Creation Kit and make mods for FNV.</p>
   
  </div>

</div>

## Other Relevant Guides

### <a href="https://performance.moddinglinked.com/falloutnv.html" target="_blank">FNV Performance Guide</a>
<div class="guide-box">
  
  <div style="margin-top: 0;">
    <p style="margin-top: 0; margin-bottom: 0;">A comprehensive guide to enhancing performance and resolving display issues, covering DXVK, framerate limiting, display modes, HDR, and more.</p>
  		
  </div>
  
</div>

### <a href="https://salamand3r.fail/salvo" target="_blank">SALVO</a>
<div class="guide-box">
  
  <div style="margin-top: 0;">
    <p style="margin-top: 0; margin-bottom: 0;">Salamand3r’s Visual Overhaul Guide for <span class="highlight">FNV</span>.</p>
  		
  </div>
  
</div>

### <a href="https://fnvdust.fandom.com/wiki/Fallout:_Dust_Wikia" target="_blank">Fallout: DUST Wikia</a>
<div class="guide-box">
  
  <div style="margin-top: 0;">
    <p style="margin-top: 0; margin-bottom: 0;">Outdated and incomplete, with some misconceptions... but still a valuable source of background and guidance for <span class="highlight">DUST</span>.</p>
  		
  </div>
  
</div>

### <a href="https://vivanewvegas.moddinglinked.com/resources.html" target="_blank">ModdingLinked Resources</a>
<div class="guide-box">
  
  <div style="margin-top: 0;">
    <p style="margin-top: 0; margin-bottom: 0;">General and game specific resources, by the creators of <span class="highlight">Viva New Vegas</span>. Beginning modders should check out the <span class="highlight">modding dogmas</span> and <span class="highlight">The Method</span>!</p>
  		
  </div>
  
</div>

## For a vanilla playthrough...

### <a href="https://vivanewvegas.moddinglinked.com/intro.html" target="_blank">Viva New Vegas</a>
<div class="guide-box">
  
  <div style="margin-top: 0;">
    <p style="margin-top: 0; margin-bottom: 0;"><b>THE</b> gold standard for modding vanilla <span class="highlight">FNV</span>, and mother of all guides.</p>
  		
  </div>
  
</div>

### <a href="https://thebestoftimes.moddinglinked.com/intro.html" target="_blank">The Best of Times</a>
<div class="guide-box">
  
  <div style="margin-top: 0;">
    <p style="margin-top: 0; margin-bottom: 0;">Another guide by <span class="highlight">ModdingLinked</span>, but now for <span class="highlight">Tale of Two Wastelands</span>.</p>
  		
  </div>
  
</div>