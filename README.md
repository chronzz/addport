# addport

edit version of https://github.com/cryptopool-builders/Multi-Pool-Installer

<li>Dedicated Port config generator</li>
<li>Created by cryptopool.builders for multipool</li>
<li>This generator will modify the main algo.conf file</li>
<li>Create the new coin.algo.conf file</li>
<li>And update the stratum start file</li>
<li>Edited to use custom port by chronzz</li>

Will only work if you have used the Cryptopool Builder Installer Script

<div><h2>Install</h2></div>
<code>cd /tmp</code><br>
<code>git clone https://github.com/chronzz/addport.git</code><br>
<code>cd addport</code><br>
<code>sudo chmod +x addport</code><br>
<code>sudo cp -r addport /usr/bin/</code><br>

<div><h2>Usage</h2></div>
<p>run command in stratum server</p>
<code>addport</code>
<br><br>
<p>To START | RESTAT | STOP STRATUM</p>
<code>stratum."coinsympol" start "coinsympol"</code><br>
<code>stratum."coinsympol" restart "coinsympol"</code><br>
<code>stratum."coinsympol" stop "coinsympol"</code><br>
<p>to view screen</p>
<code>screen -r "coinsympol"</code><br>
<br><br>
<p>example</p>
<p>"coinsympol" in lowercase</p>
<code>stratum.btc start btc</code>
