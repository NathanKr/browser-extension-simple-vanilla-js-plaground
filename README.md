<h2>Motivation</h2>
Build most simple web extension and install in chrome and firefox

<h2>Setup</h2>
<ul>
<li>create html file</li>
<li>create js file</li>
<li>manifest.json file which is meta data file about your chrom extension</li>
</ul>

<h2>Instll the extention on chrome</h2>
<ol>
<li>open new tab in chrome</li>
<li>navigate to More tools->Extensions->Turn on developer mode->Load unpacked->select the folder of your extension. Now the extetion is installed</li>
<li>open new tab in chrome->click on extentions icon->choose "My Extenion Name"</li>
</ol>

<h2>Instll the extention on firefox</h2>
<ol>
<li>perform once : npm install --global web-ext</li>
<li>test the extention by navigating to the project root and invoke : web-ext run. The browser is opened</li>
<li>click on extentions icon->choose "My Extenion Name"</li>
</ol>

<h2>Open issues</h2>
<ul>
<li>why import './style.css' cause the extenstion to load small empty reactangle</li>
</ul>