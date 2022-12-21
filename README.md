<p align="center"><a href="https://github.com/the-control-group/voyager" target="_blank">Fork of TCG Voyager</a></p>
<br><br>
<p align="left">Improvements:</p>
<ul>
    <li>Automatic generation of seeds from BREADs. Using upsert for the tables config and role</li>
</ul><br><br>
<p align="left">How to add to your project:</p>
<ul>
    <li>Add this to your composer.json file, inside the root object:
        <pre>    "repositories": [
        {
            "type":"package",
            "package": {
              "name": "tcg/voyager",
              "version":"mhk-master",
              "source": {
                  "url": "https://github.com/mauhk/voyager.git",
                  "type": "git",
                  "reference":"mhk-master"
                }
            }
        }
    ],</pre>
    </li>
    <li>Add this to your composer.json file, inside "require" section:
        <pre>"tcg/voyager": "dev-mhk-master"</pre>
    </li>
    <li>Run <code>composer update</code> and <code>composer install</code>
    </li>
    <li>Follow the other instructions from the main TCG Voyager project</li>
</ul>