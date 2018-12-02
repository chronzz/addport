# stratum-multiport-configs

edit version of https://github.com/cryptopool-builders/Multi-Pool-Installer


Will only work if you have used the Cryptopool Builder Multi server Install

<div><h2>Install</h2></div>
<p>cd /tmp</p>
<p>git clone https://github.com/chronzz/stratum-multiport-configs.git</p>
<p>cd stratum-multiport-configs</p>
<p>sudo chmod +x addport</p>
<p>sudo cp -r addport /usr/bin/</p>

<div><h2>Usage</h2></div>
<p>run command in stratum server</p>
<code>addport</code>
<br><br>
<p>To START | RESTAT | STOP STRATUM</p>
<code>stratum."coinsympol" start "coinsympol"</code><br>
<code>stratum."coinsympol" restart "coinsympol"</code><br>
<code>stratum."coinsympol" stop "coinsympol"</code><br>
<p>to view screen</p>
<code>screen -r "coinsympol"</code>
