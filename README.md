<h1 align="center">browser-ui-tools</h1>
<p align="center">Browser extension wanting to be multi-purpose envolving design and script improvements/utilities.</p>

<h6 align="center">Para ler a versão em português deste documento <a href="https://github.com/GuiDevloper/browser-ui-tools/blob/master/README-BR.md">clique aqui</a>
</h6>

<h3 align="center">Youtube Music</h3>
<p align="center">
  <img width="400px" alt="Default Youtube Music" src="https://dl.dropbox.com/s/o6qc0bhncax35sv/YTbefore.jpg">
  <img width="400px" alt="Custom Youtube Music" src="https://dl.dropbox.com/s/c7qpgte5lpxllng/YTafter.jpg">
  <br><em align="center">Disabled/Enabled YT Music redesign</em><br>
  <a href="https://dl.dropbox.com/s/bhnf0km2qqx8sbo/YTCompress.mp4" target="_blank" rel="noopener">
    Open video with overview of changes
  </a>
</p>

## How to use

+ Download this [repository in ZIP](https://github.com/GuiDevloper/browser-ui-tools/archive/master.zip) and extract
+ Open your browser extension list on More Tools > Extensions
+ Activate the Developer Mode of extensions
+ Click on Load Unpacked and select the location where the extraction was saved

Note: It's recommended to change the zoom on the altered page to your liking

## How to Customize

As everything in this extension, customizing is simple to do:

+ If wanting to change the design, open the respective CSS file, change, save and reload the extension on More Tools > Extensions

+ If wanting to disable a page change (like a redesign) just open your [manifest.json](https://github.com/GuiDevloper/browser-ui-tools/blob/master/manifest.json) and remove the respective `content_script` or `matches` (disabling completelly changes made by that file)

## How to Contribute

+ If you seen a thing which looked like a bug or needing improvement just create your [Issue](https://github.com/GuiDevloper/browser-ui-tools/issues).

+ If you want to add here your own redesign/functionality, awesome!

You can Fork this repo, add functions and send your Pull Request :)

## License

[MIT](https://github.com/GuiDevloper/browser-ui-tools/blob/master/LICENSE)

Copyright (c) 2020 Guilherme Correia
