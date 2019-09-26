<link rel="stylesheet" type="text/css" href="https://files.hoppel.us/css/reset_rick.css" media="all">
<link rel='stylesheet' type='text/css' href='https://fonts.googleapis.com/css?family=Fjalla+One%7CAnaheim'>

<style>#preview-box {background-color: rgba(1,1,1,0.1);padding: 1px 10px;border-radius: 10px;}</style>
<link id="linkstyle" rel='stylesheet' href='https://files.hoppel.us/css/lodge-default.css'/>
<div id="preview-box">
    <strong>preview another css ...</strong>
    <select style="width:100%" id="themes">
        <option value="https://files.hoppel.us/css/default.css"      >default</option>
        <option value="https://files.hoppel.us/css/lodge-default.css">lodge-default</option>
        <option value="https://files.hoppel.us/css/lodge-brown.css"  >lodge-brown</option>
        <option value="https://files.hoppel.us/css/lodge-green.css"  >lodge-green</option>
        <option value="https://files.hoppel.us/css/reset_rick.css"   >reset_rick</option>
        <option value="https://files.hoppel.us/css/github-markdown.css">github-markdown</option>
        <option value="https://files.hoppel.us/css/markdown.css"     >markdown</option>
        <option value="https://files.hoppel.us/css/markdown-alt.css" >markdown-alt</option>
        <option value="https://files.hoppel.us/css/markdown1.css"    >markdown1</option>
        <option value="https://files.hoppel.us/css/markdown2.css"    >markdown2</option>
        <option value="https://files.hoppel.us/css/markdown3.css"    >markdown3</option>
        <option value="https://files.hoppel.us/css/markdown4.css"    >markdown4</option>
        <option value="https://files.hoppel.us/css/markdown5.css"    >markdown5</option>
        <option value="https://files.hoppel.us/css/markdown6.css"    >markdown6</option>
        <option value="https://files.hoppel.us/css/markdown7.css"    >markdown7</option>
        <option value="https://files.hoppel.us/css/markdown8.css"    >markdown8</option>
        <option value="https://files.hoppel.us/css/markdown9.css"    >markdown9</option>
        <option value="https://files.hoppel.us/css/markdown10.css"   >markdown10</option>
        <option value="https://files.hoppel.us/css/avenir-white.css" >avenir-white</option>
        <option value="https://files.hoppel.us/css/foghorn.css"      >foghorn</option>
        <option value="https://files.hoppel.us/css/screen.css"       >screen</option>
        <option value="https://files.hoppel.us/css/swiss.css"        >swiss</option>
        <option value="https://files.hoppel.us/css/retro.css"        >retro</option>
        <option value="https://files.hoppel.us/css/reset.css">       reset</option>
</select></div>
<script> var linkstyle = document.getElementById('linkstyle'); var themes = document.getElementById('themes'); themes.onchange = function(e) {linkstyle.href = themes.value; };</script>`

![techdogs Logo](https://portfolio.hoppel.us/resources/logo/techDogs_logo_white_bar_wide.png)

# IoT TARDIS Project Demonstration

<br/>

## status: <a style="color:Red">Beta[</a> <a style="color:White">A</a> <a style="color:Red">]</a>

<br/>

<h1 style="color:#7faedb;font-size:30px; text-transform: none;">[host: <script language="JavaScript"> document.write(window.location.hostname +'</a>' );</script>]</h1><br/>
<h1 class="author" style="font-size:50px"; >creator: Richard Hoppel</h1><br/>

###### click on graphics for action & expanded information

<p class="intro">the remote control center for the universe<br/>[Raspberry Pi, NodeMCU and Node-Red]</p>

## Hardware Platforms [__tiny__ server & __tiny__ remote node]
* self-contained host platform: **Raspberry Pi 3 [node-red flow editor & controller, Apache webserver, webcam]**
* remote node platform: **WeMos D1 mini ESP8266** 

| | | |
|---|---|---|
[![demo_tn]][demo] | [![breadboard_tn]][breadboard] | [![schematic_bb_tn]][schematic_bb]

###### click to project slide __3__ for demo diagram

<div class="iframe_container">
   <iframe src="https://onedrive.live.com/embed?cid=88FCEE2150B75169&amp;resid=88FCEE2150B75169%21394381&amp;authkey=AH8Seg6YfNgh9yI&amp;em=2&amp;wdAr=1.7777777777777777" width="1100x" height="643x" frameborder="0">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>
</div>

###### K9-node Live! [platform: ESP8266]

<img src="http://demo.techdogs.us:56000/mjpeg" alt="Webcam not available - try refreshing screen " >

## Display Image Legend [platform: __K9-node__ (8266 based)]

| | | |
|---|---|---|---|
Status | I/O Pin Status | WebCam
[![display_legend_1_tn]][display_legend_1] | [![display_legend_2_tn]][display_legend_2] | [![display_legend_3_tn]][display_legend_3]

## Live Interactive Demo

| | | |
|---|---|---|---|
Node-Red Web UI controls K9-node | Monitor Node-Red Status | K9-node live Webcam
[![main_ui_tn_live]][main_ui_i] | [![main_tn_live]][main_i] | [![K9_2_live_tn]][K9_i] |

## Project Images [static]

| | | | |
|---|---|---|---|---|
Status  | I/O Pins | Schematic | Breadboard | Main UI
[![K9_1_tn]][K9_1] | [![K9_2_tn]][K9_2] | [![schematic_tn]][schematic] | [![bb_tn]][bb]  | [![main_ui_tn]][main_ui] 

## Node-Red Control Flows (platform: __Raspberry Pi__)

| | | | |
|---|---|---|---|
Configuration | Main Control | Update Node |
[![nr-config_tn]][nr-config] | [![main_tn]][main] | [![update_tn]][update_tn]

[demo_tn]: https://files.hoppel.us/techdogs/TARDIS/system_demo_tn.png
[demo]: https://files.hoppel.us/techdogs/TARDIS/system_demo.png
[breadboard_tn]: https://files.hoppel.us/techdogs/TARDIS/breadboard_notes_tn.png
[breadboard]: https://files.hoppel.us/techdogs/TARDIS/breadboard_notes.png
[schematic_bb_tn]: https://files.hoppel.us/techdogs/TARDIS/schematic_bb_tn.png
[schematic_bb]: https://files.hoppel.us/techdogs/TARDIS/schematic_bb.png


[display_legend_1]: https://files.hoppel.us/techdogs/TARDIS/display_legend_1.png
[display_legend_1_tn]: https://files.hoppel.us/techdogs/TARDIS/display_legend_1_tn.png
[display_legend_2]: https://files.hoppel.us/techdogs/TARDIS/display_legend_2.png
[display_legend_2_tn]: https://files.hoppel.us/techdogs/TARDIS/display_legend_2_tn.png
[display_legend_3]: https://files.hoppel.us/techdogs/TARDIS/display_legend_3.png
[display_legend_3_tn]: https://files.hoppel.us/techdogs/TARDIS/display_legend_3_tn.png

[K9_1]: https://files.hoppel.us/techdogs/TARDIS/K9_1.png
[K9_1_tn]: https://files.hoppel.us/techdogs/TARDIS/K9_1_tn.png
[K9_2]: https://files.hoppel.us/techdogs/TARDIS/K9_2.png
[K9_2_tn]: https://files.hoppel.us/techdogs/TARDIS/K9_2_tn.png
[K9_2_live_tn]: https://files.hoppel.us/techdogs/TARDIS/K9_2_live_tn.png
[K9_i]: http://demo.techdogs.us:56000/mjpeg

[schematic]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_Demo_schem.png
[schematic_tn]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_Demo_schem_tn.png

[bb]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_Demo_bb.png
[bb_tn]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_Demo_bb_tn.png

[main_ui]: https://files.hoppel.us/techdogs/TARDIS/main_ui.png
[main_ui_i]: http://demo.techdogs.us:1880/ui/#!/0?socketid=7n2RyrGfx_OxjrShAAAI
[main_ui_tn]: https://files.hoppel.us/techdogs/TARDIS/main_ui_tn.png
[main_ui_tn_live]: https://files.hoppel.us/techdogs/TARDIS/main_ui_tn_live.png

[nr-config_tn]: https://files.hoppel.us/techdogs/TARDIS/Configuration_a_tn.png 
[nr-config]: https://files.hoppel.us/techdogs/TARDIS/Configuration_a.png

[main]: https://files.hoppel.us/techdogs/TARDIS/MainControl__a.png 
[main_i]: http://demo.techdogs.us:1880/#flow/e0c6f6b6.0d5c68
[main_tn]: https://files.hoppel.us/techdogs/TARDIS/MainControl__a_tn.png
[main_tn_live]: https://files.hoppel.us/techdogs/TARDIS/MainControl__a_tn_live.png

[update_tn]: https://files.hoppel.us/techdogs/TARDIS/UpdateNodeDB_a_tn.png 
[update]: https://files.hoppel.us/techdogs/TARDIS/UpdateNodeDB_a.png

[iot_tn]: https://files.hoppel.us/techdogs/TARDIS/techDogs_IoT_tn.png 
[iot]: https://files.hoppel.us/techdogs/TARDIS/techDogs_IoT.png

## __K9-Node__ Software Diagrams

| | | | | | |
|---|---|---|---|---|---|
| Draw_io diagrams | component diagram | use diagram | entity diagram | class diagram | sql diagram |
| [![draw_icon]][DrawIO]  | [![Component_tn]][Component] | [![Use_tn]][Use]  | [![entity_tn]][entity] | [![class_tn]][class] | [![sqlite_tn]][sqlite] 

[draw_icon]: https://files.hoppel.us/techdogs/TARDIS/draw_io.png
[DrawIO]: https://drive.google.com/file/d/1FYDpskkRdHCHbx-Rh9Uc6l4U7X0JC8et/view?usp=sharing
[Use_tn]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS-Use-K9_tn.png
[Use]:https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS-Use.png
[Component_tn]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS_component_tn.png
[Component]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS_component.png
[sqlite_tn]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS_sqlite_tn.png
[sqlite]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS_sqlite.png
[class_tn]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS_class_tn.png
[class]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAMS_class.png
[entity_tn]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAM_entity_tn.png
[entity]: https://files.hoppel.us/techdogs/TARDIS/IoT_TARDIS_UML_DIAGRAM_entity.png

## Project Documentation

| | | | | |
|---|---|---|---|---|
[IoT TARDIS Project: PUBLIC Evernote Notebook] | [IoT TARDIS Project \[JIRA PM\]] | [IoT TARDIS Project \[Evernote Notebook\]] |[IoT TARDIS Project - OneNote notebook] | [GitHub Node-red repository]

[Online Presentation -ppt]: https://1drv.ms/p/s!AmlRt1Ah7vyImIkNnG3AiufU6QrO1Q
[IoT TARDIS Project \[JIRA PM\]]: http://hs2:8080/secure/RapidBoard.jspa?rapidView=10&selectedIssue=ESP-6
[IoT TARDIS Project: PUBLIC Evernote Notebook]: https://www.evernote.com/pub/rhoppel/iottardis
[IoT TARDIS Project \[Evernote Notebook\]]: https://goo.gl/TqXi6L
[IoT TARDIS Project - OneNote notebook]: https://login.live.com/login.srf?wa=wsignin1.0&rpsnv=13&ct=1568786824&rver=7.1.6819.0&wp=MBI_SSL_SHARED&wreply=https:%2F%2Fonedrive.live.com%2Fview.aspx%3Fresid%3D88FCEE2150B75169%2521394362%26id%3Ddocuments%2520onenote:https:%2F%2Fd.docs.live.net%2F88fcee2150b75169%2FArchive%2FDocuments%2FIOT%2520TARDIS%2520Project%2F&lc=1033&id=250206&cbcxt=sky&cbcxt=sky
[GitHub Node-red repository]: https://github.com/rhoppel/lodge-nodered-nodemcu

| | |
|---|---|
[![jira_tn]][jira]  | [![evernote_tn]][IoT TARDIS Project: PUBLIC Evernote Notebook]

[jira_tn]: https://files.hoppel.us/techdogs/TARDIS/jira_iot_tardis_tn.png
[jira]: https://files.hoppel.us/techdogs/TARDIS/jira_iot_tardis.png
[evernote_tn]: https://files.hoppel.us/techdogs/TARDIS/evernote_public_tn.png
[evernote]: https://files.hoppel.us/techdogs/TARDIS/jira_iot_tardis.png

## Project Style

| | | | | |
|---|---|---|---|---|
<a style="color:white">[background color] | <a style="color:#82624b">#82624b</a>
<a style="color:white">[text colors] | <a style="color:#7faedb">#7faedb</a> | <a style="color:#ed7d31">#ed7d31</a> | <a style="color:white">white</a> | <a style="color:LightBlue">LightBlue</a> | 
<a style="color:white">[Fonts] | [Font: Fjalla One](https://fonts.google.com/specimen/Fjalla+One?selection.family=Fjalla+One) | [Font: Anaheim](https://fonts.google.com/specimen/Anaheim?selection.family=Anaheim)

## Live Node-Red

<script language="JavaScript"]> 
	document.write('<a style="color:LightBlue;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':1880' +  '" >Node Red [Control Panel]</a>' ); 
</script>

* default user is READ-only

<script language="JavaScript"]>
	document.write('<a style="color:LightBlue;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':1880' +  '/ui" >Node Red [UI Desktop]</a>' );
</script>

* [user:password] = node-red-user : node-red-user-default

## Live Platform Tools
### for local network use only

<script language="JavaScript"]>
	document.write('<a style="color:LightBlue;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':56000' +  '/mjpeg" >WebCam [host]</a>' );
</script>

<script language="JavaScript"]>
document.write('<a style="color:LightBlue;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':10000' +  '" >Webmin Adminstrator</a>' );
</script>

<script language="JavaScript"]>
	document.write('<a style="color:LightBlue;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':8888' +  '" >RPI Monitor</a>' );
</script>
[SQLite Administrator](/phpliteadmin)
[System Information](/phpsysinfo")

## Supporting Technical Documents

| | | | |
|---|---|---|---|
[Markdown Cheatsheet] | [HTML Cheatsheet] | [Node-Red Docs] | [Node-Red Blog]
[Node-Red Releases] | [JSONata] | [Raspberry Pi Docs] | [RPi-clone]
[Raspberry Pi Hardware] | [NodeMCU Docs] | [ Lua 5.1 Reference] | [ Lua LuaSrcDiet]
[ Lua File Operations on ESP826] | [ ESP8266 Non-OS SDK API Reference] | [SPIFFS FLASH file system] |
[WeMos Devices] | [WeMos Store] | [ESP8266] | [Web Colors]

[Markdown Cheatsheet]: https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet
[HTML Cheatsheet]: http://www.simplehtmlguide.com/cheatsheet.php
[Node-Red Docs]: https://nodered.org/docs/
[Node-Red Blog]: https://nodered.org/blog/
[Node-Red Releases]: https://github.com/node-red/node-red/releases
[JSONata]: https://docs.jsonata.org
[Raspberry Pi Hardware]: https://www.raspberrypi.org/documentation/hardware/raspberrypi/README.md
[NodeMCU Docs]: https://nodemcu.readthedocs.io/en/master/
[ Lua 5.1 Reference]: https://www.lua.org/manual/5.1/
[ Lua LuaSrcDiet]: https://github.com/LuaDist/luasrcdiet
[ Lua File Operations on ESP826]: https://iotbytes.wordpress.com/managing-files-with-nodemcu/
[ ESP8266 Non-OS SDK API Reference]: https://www.espressif.com/sites/default/files/documentation/2c-esp8266_non_os_sdk_api_reference_en.pdf
[ESP8266 Hardware Notes]: https://tttapa.github.io/ESP8266/Chap04%20-%20Microcontroller.html
[SPIFFS FLASH file system]: https://github.com/pellepl/spiffs
[WeMos Devices]: https://wiki.wemos.cc/start
[WeMos Store]: https://www.aliexpress.com/store/1331105
[ESP8266]: https://nurdspace.nl/ESP8266
[Web Colors]: https://en.wikipedia.org/wiki/Web_colors

## Development Tools

| | | | | | |
--- | --- | --- | --- | --- | ---
[js sequence diagrams] | [marxi.co markup editor for Evernote] | [draw.io diagramming] | [SQLite DB on Raspberry Pi] | [Etcher: Burn SD card images] | [spiffmsg - Manipulate SPI FLASH file systems images]

[js sequence diagrams]: https://bramp.github.io/js-sequence-diagrams/
[marxi.co markup editor for Evernote]: https://marxi.co/
[draw.io diagramming]: https://www.draw.io/
[SQLite DB on Raspberry Pi]: https://iotbytes.wordpress.com/sqlite-db-on-raspberry-pi/
[Etcher: Burn SD card images]: https://etcher.io/
[spiffmsg - Manipulate SPI FLASH file systems images]: https://github.com/nodemcu/nodemcu-firmware/blob/master/docs/en/spiffs.md

## Technical Social Groups

| | | | |
--- | --- | --- | --- |
[Node-Red Discourse Discussion Group] | [Node-Red Google Group] | [Learning Node-Red] | [black for Node-Red]

[Node-Red Discourse Discussion Group]: https://discourse.nodered.org/
[Node-Red Google Group]: https://groups.google.com/forum/#!forum/node-red
[Learning Node-Red]: http://node-red.blogspot.com
[black for Node-Red]: http://nodered.org/black

## WWW and Security

| | | | | |
--- | --- | --- | --- | --- |
[Let's Encrypt]| [CertBot] | [HAproxy] | [Test SSL] | [Google Domains]

[Let's Encrypt]: https://letsencrypt.org/
[CertBot]: https://certbot.eff.org/
[HAproxy]: http://www.haproxy.org/
[Test SSL]: https://www.ssllabs.com/ssltest/analyze.html?d=techdogs.us
[Google Domains]: https://domains.google.com

## Home Assistant

 | | | | |
--- | --- | --- | ---
[Home Assistant] | [Awesome Home Assistant] | [HassOs hypervisor] | [Buildroot (used to create HassOs)]

[Home Assistant]: https://www.home-assistant.io/
[Awesome Home Assistant]: https://www.awesome-ha.com/
[HassOs hypervisor]: https://github.com/home-assistant/hassos
[Buildroot (used to create HassOs)]: (https://buildroot.org/)

## Ideas

| | | |
--- | --- | ---
[techDogs] | [Scargill's Tech Blog] | [Scargill Snippets]
[more on CSS reset]| [Home Control 2017]| [Nextion WiFi display]

[techDogs]: http://techdogs.us
[Scargill's Tech Blog]: https://tech.scargill.net/
[Scargill Snippets]: https://bitbucket.org/snippets/scargill/
[reset CSS]: https://cssreset.com/scripts/eric-meyer-reset-css/
[more on CSS reset]: https://www.webpagefx.com/blog/web-design/the-history-of-css-resets/
[Home Control 2017]: https://tech.scargill.net/home-:control-2016/
[Nextion WiFi display]: https://tech.scargill.net/nextion-wifi-touch-display/

<a target="_blank" href="https://en.wikipedia.org/wiki/TARDIS"><img src="https://portfolio.hoppel.us/resources/png/tardis4a.png" alt="TARDIS" class="center tardis"></a>

## [![panic]][system_ui]

[panic]: https://files.hoppel.us/techdogs/TARDIS/panic.png
[system_ui]: http://demo.techdogs.us:1880/ui/#!/6?socketid=_3Lu59VILtPfKDlyAAAE
