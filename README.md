<h2>Motivation</h2>
Build most simple web extension and install in chrome and firefox

<h2>Setup</h2>
<ul>
<li>create html file</li>
<li>create js file</li>
<li>manifest.json file which is meta data file about your chrom extension</li>
</ul>

<h2>Instll the extension on chrome</h2>
<ol>
<li>navigate to More tools->Extensions->Turn on developer mode->Load unpacked->select the folder of your extension. Now the extetion is installed</li>
<li>open new tab in chrome->click on extensions icon->choose "My Extension Name"</li>
<li>pin the extension via Chrome->Extensions</li>
</ol>

<h2>Instll the extension on firefox</h2>
<ol>
<li>perform once : npm install --global web-ext</li>
<li>test the extension by navigating to the project root and invoke : web-ext run. The browser is opened</li>
<li>click on extensions icon->choose "My Extension Name"</li>
</ol>

<h2>Open issues</h2>
<ul>
<li>why import './style.css' cause the extension to load small empty reactangle. Inline styling does work</li>
</ul>