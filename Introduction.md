<h2>LoRa shield library</h2>
<p class='vspace'></p><table >
  <tr><td  width='55%' valign='top'>
<p class='vspace'></p>
<p>
  Arduino library for LoRa shield .
</p>
<p>  
  This library concerns the LoRa Arduino shield that uses the SX1278 SEMTECH tranceiver.
</p>  


<p>&nbsp;</p>
<p>Three classes:</p>
<ul>
  <li>SX1278 ; basic modem management.</li>
  <li>LORA ; simplified functions for LoRa modem</li>
  <li>REMOTEC ; simplified functions for using SX1278 as OOK transitter with HX2262 protocol</li>
</ul>

<p>&nbsp;</p>
<p>Both LORA class and REMOTEC class use basic SX1278 functions. So, you can use SX1278 functions mixed with LORA or REMOTEC functions for better trim.</p>
<p>SX1278 class is referenced by external name SX.</p>
<p>&nbsp;</p>
<p>Pin used by shield:</p>
<ul>
  <li>D13 : SPI SCK</li>
  <li>D12 : SPI MISO</li>
  <li>D11 : SPI MOSI</li>
  <li>D10 (or D8) : SPI CS</li>
  <li>D5 (or D7) : SX1278 RESET</li>
  <li>(D6 or D9 or none) : Inp/Out pulses</li>
  <li>(D3 or none) : interrupt</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p></td><td  width='10%' valign='top'>
<p class='vspace'></p></td><td  width='35%' valign='top'>
<p class='vspace'></p>
<p>Library archive content</p>
<h4>Classes</h4>
<ul>
<li><a class='wikilink' href='SX1278.html'>SX1278</a></li>
<li><a class='wikilink' href='LORA.html'>LORA</a></li>
<li><a class='wikilink' href='REMOTEC.html'>REMOTEC</a></li>
<li><a class='wikilink' href='sx1276.pdf'>Datasheet sx1278</a></li>
</ul>
<p class='vspace'></p><h4>Examples</h4>
<ul>
  <li><a class='wikilink' href='../examples/LoRaTxEcho.ino'>LoRaTxEcho</a></li>
  <li><a class='wikilink' href='../examples/LoRaTxEcho.ino'>LoRaRxEcho</a></li>
  <li><a class='wikilink' href='../examples/LoRaTxEcho.ino'>RemPwr</a></li>
  <li><a class='wikilink' href='../examples/LoRaTxEcho.ino'>RemPwrScanner</a></li>
</ul>
</td></tr></table>
