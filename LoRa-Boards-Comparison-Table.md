---
layout: default
title: LoRa Boards Comparison Table
---

# LoRa Boards Comparison Table

## Filter Boards

<div style="display: flex; flex-wrap: wrap;">
  <div style="margin-right: 20px;">
    <label>MCU Chip:</label>
    <div>
      <input type="checkbox" class="mcuFilter" value="ESP32"> ESP32<br>
      <input type="checkbox" class="mcuFilter" value="nRF"> nRF52840<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>LoRa Chip:</label>
    <div>
      <input type="checkbox" class="loraFilter" value="SX1276"> SX1276<br>
      <input type="checkbox" class="loraFilter" value="SX1278"> SX1278<br>      
      <input type="checkbox" class="loraFilter" value="SX1262"> SX1262<br>
      <input type="checkbox" class="loraFilter" value="SX1280"> SX1280<br>
      <input type="checkbox" class="loraFilter" value="LR1110"> LR1110<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>GPS:</label>
    <div>
      <input type="checkbox" class="gpsFilter" value="Yes"> Yes<br>
      <input type="checkbox" class="gpsFilter" value="No"> No<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Screen:</label>
    <div>
      <input type="checkbox" class="screenFilter" value="Eink"> Eink<br>
      <input type="checkbox" class="screenFilter" value="LCD"> LCD<br>      
      <input type="checkbox" class="screenFilter" value="OLED"> OLED<br>      
      <input type="checkbox" class="screenFilter" value="TFT"> TFT<br>
      <input type="checkbox" class="screenFilter" value="None"> None<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>WiFi:</label>
    <div>
      <input type="checkbox" class="wifiFilter" value="Yes"> Yes<br>
      <input type="checkbox" class="wifiFilter" value="No"> No<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Input Interface:</label>
    <div>
      <input type="checkbox" class="inputFilter" value="Touch"> Touch<br>
      <input type="checkbox" class="inputFilter" value="Keyboard"> Keyboard<br>
      <input type="checkbox" class="inputFilter" value="User"> User Button<br>
      <input type="checkbox" class="inputFilter" value="None"> None<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Price Range USD:</label>
    <div>
      <input type="checkbox" class="priceFilter" value="0-20"> 0-20<br>
      <input type="checkbox" class="priceFilter" value="21-40"> 21-40<br>
      <input type="checkbox" class="priceFilter" value="41-60"> 41-60<br>
      <input type="checkbox" class="priceFilter" value="61+"> 61+<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Brand:</label>
    <div>
      <input type="checkbox" class="brandFilter" value="Heltec"> Heltec<br>
      <input type="checkbox" class="brandFilter" value="Rack"> Rak Wireless<br>
      <input type="checkbox" class="brandFilter" value="Lilygo"> Lilygo<br>
      <input type="checkbox" class="brandFilter" value="B&Q"> B&Q Consulting<br>
      <input type="checkbox" class="brandFilter" value="Seeed"> Seed Studio<br>
      <input type="checkbox" class="brandFilter" value="Indie"> Indie<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Case Included:</label>
    <div>
      <input type="checkbox" class="caseFilter" value="Yes"> Yes<br>
      <input type="checkbox" class="caseFilter" value="No"> No<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Battery Included:</label>
    <div>
      <input type="checkbox" class="batteryFilter" value="Yes"> Yes<br>
      <input type="checkbox" class="batteryFilter" value="No"> No<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Meshtastic Preloaded:</label>
    <div>
      <input type="checkbox" class="meshtasticFilter" value="Yes"> Yes<br>
      <input type="checkbox" class="meshtasticFilter" value="No"> No<br>
    </div>
  </div>
  <div style="margin-right: 20px;">
    <label>Ready-to-use:</label>
    <div>
      <input type="checkbox" class="readyFilter" value="Yes"> Yes<br>
      <input type="checkbox" class="readyFilter" value="No"> No<br>
    </div>
  </div>
</div>

<div style="overflow-x: auto;">
  <table id="comparisonTable">
    <thead>
      <tr>
        <th>Device</th>
        <th data-mcu="ESP32" data-lora="SX1276" data-gps="No" data-screen="OLED" data-wifi="Yes" data-input="User" data-price="15.47" data-brand="Heltec" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Heltec ESP32 V2</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="OLED" data-wifi="Yes" data-input="User" data-price="17.90" data-brand="Heltec" data-case="Yes" data-battery="No" data-meshtastic="No" data-ready="No">Heltec ESP32 V3</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="Eink" data-wifi="Yes" data-input="User" data-price="15.90" data-brand="Heltec" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Heltec Wireless Paper</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="None" data-wifi="Yes" data-input="User" data-price="14.90" data-brand="Heltec" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Wireless Stick Lite (V3)</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="Yes" data-screen="TFT" data-wifi="Yes" data-input="User" data-price="22.90" data-brand="Heltec" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Heltec Wireless Tracker</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="Yes" data-screen="None" data-wifi="Yes" data-input="User" data-price="25.99" data-brand="Heltec" data-case="Yes" data-battery="Yes" data-meshtastic="Yes" data-ready="Yes">Heltec Capsule Sensor V3</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="Eink" data-wifi="Yes" data-input="User" data-price="19.90" data-brand="Heltec" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Heltec Vision Master E213</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="Eink" data-wifi="Yes" data-input="User" data-price="20.90" data-brand="Heltec" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Heltec Vision Master E290</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="TFT" data-wifi="Yes" data-input="User" data-price="20.00" data-brand="Heltec" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Heltec Vision Master T190</th>        
        <th data-mcu="nRF" data-lora="SX1262" data-gps="No" data-screen="None" data-wifi="No" data-input="None" data-price="36.97" data-brand="Rack" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">WisBlock Start Kit RAK4631</th>
        <th data-mcu="nRF" data-lora="SX1262" data-gps="Yes" data-screen="OLED" data-wifi="No" data-input="None" data-price="99.00" data-brand="Rack" data-case="Yes" data-battery="Yes" data-meshtastic="Yes" data-ready="Yes">WisMesh Pocket</th>        
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="LCD" data-wifi="Yes" data-input="Touch, Keyboard, User" data-price="52.66" data-brand="Lilygo" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">T-Deck</th>
        <th data-mcu="nRF" data-lora="SX1262" data-gps="Yes" data-screen="Eink" data-wifi="No" data-input="Touch, User" data-price="54.41" data-brand="Lilygo" data-case="Yes" data-battery="Yes" data-meshtastic="Yes" data-ready="Yes">T-Echo</th>
        <th data-mcu="ESP32" data-lora="SX1276" data-gps="Yes" data-screen="OLED" data-wifi="Yes" data-input="User" data-price="32.80" data-brand="Lilygo" data-case="No" data-battery="No" data-meshtastic="Yes" data-ready="No">T-Beam</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="Yes" data-screen="OLED" data-wifi="Yes" data-input="User" data-price="44.17" data-brand="Lilygo" data-case="No" data-battery="No" data-meshtastic="Yes" data-ready="No">T-Beam Supreme</th>
        <th data-mcu="ESP32" data-lora="SX1262 SX1276 SX1278 SX1280" data-gps="No" data-screen="OLED" data-wifi="Yes" data-input="User" data-price="17.58" data-brand="Lilygo" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">T3-S3</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="No" data-screen="OLED" data-wifi="Yes" data-input="User" data-price="109.00" data-brand="B&Q" data-case="Yes" data-battery="No" data-meshtastic="Yes" data-ready="No">Station G2</th>
        <th data-mcu="nRF" data-lora="SX1262" data-gps="Yes" data-screen="OLED" data-wifi="No" data-input="User" data-price="86.00" data-brand="B&Q" data-case="Yes" data-battery="No" data-meshtastic="Yes" data-ready="No">Nano G2 Ultra</th>
        <th data-mcu="nRF" data-lora="LR1110" data-gps="Yes" data-screen="None" data-wifi="No" data-input="User" data-price="29.90" data-brand="Seeed" data-case="No" data-battery="No" data-meshtastic="No" data-ready="No">Wio Tracker 1110</th>
        <th data-mcu="ESP32" data-lora="SX1262" data-gps="Yes" data-screen="OLED" data-wifi="Yes" data-input="Keyboard, User" data-price="95.00" data-brand="Indie" data-case="Yes" data-battery="Yes" data-meshtastic="Yes" data-ready="Yes">HelTxt</th>
        <th data-mcu="nRF" data-lora="SX1262" data-gps="Yes" data-screen="OLED" data-wifi="No" data-input="Keyboard, User" data-price="250.00" data-brand="Indie" data-case="Yes" data-battery="Yes" data-meshtastic="Yes" data-ready="Yes">Meshenger</th>        
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Brand</td>
        <td>Heltec</td><!--Heltec V2-->
        <td>Heltec</td><!--Heltec V3-->
        <td>Heltec</td><!--Wireless Paper-->
        <td>Heltec</td><!--Wireless Stick Lite-->
        <td>Heltec</td><!--Wireless Tracker-->
        <td>Heltec</td><!--Capsule Sensor V3-->
        <td>Heltec</td><!--Vision Master E213-->
        <td>Heltec</td><!--Vision Master E290-->
        <td>Heltec</td><!--Vision Master T190-->
        <td>Rak Wireless</td><!--RAKRAK19007-->
        <td>Rak Wireless</td><!--WisMesh-->
        <td>Lilygo</td><!--T-Deck-->
        <td>Lilygo</td><!--T-Echo-->
        <td>Lilygo</td><!--T-Beam-->
        <td>Lilygo</td><!--T-Beam-Supreme-->
        <td>Lilygo</td><!--T3-S3-->
        <td>B&Q Consulting</td><!--Station G2-->
        <td>B&Q Consulting</td><!--Nano G2 Ultra-->
        <td>Seeed Studio</td><!--Wio Tracker 1110-->
        <td>Indie</td><!--Heltxt-->
        <td>Indie</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Average Price USD</td>
        <td><a href="https://www.aliexpress.com/i/2251832758749430.html?gatewayAdapt=4itemAdapt" target="_blank" rel="noopener noreferrer">$15.47</a></td><!--Heltec V2-->
        <td><a href="https://heltec.org/project/wifi-lora-32-v3/" target="_blank" rel="noopener noreferrer">$17.90</a></td><!--Heltec V3-->
        <td><a href="https://heltec.org/project/wireless-paper/" target="_blank" rel="noopener noreferrer">$15.90</a></td><!--Wireless Paper-->
        <td><a href="https://heltec.org/project/wireless-stick-lite-v2/" target="_blank" rel="noopener noreferrer">$14.90</a></td><!--Wireless Stick Lite-->
        <td><a href="https://heltec.org/project/wireless-tracker/" target="_blank" rel="noopener noreferrer">$22.90</a></td><!--Wireless Tracker-->
        <td><a href="https://heltec.org/project/heltec-capsule-sensor-v3/" target="_blank" rel="noopener noreferrer">$25.99</a></td><!--Capsule Sensor V3-->
        <td><a href="https://heltec.org/project/vision-master-e213/" target="_blank" rel="noopener noreferrer">$19.90</a></td><!--Vision Master E213-->
        <td><a href="https://heltec.org/project/vision-master-e290/" target="_blank" rel="noopener noreferrer">$20.90</a></td><!--Vision Master E290-->
        <td><a href="https://heltec.org/project/vision-master-t190/" target="_blank" rel="noopener noreferrer">$20.00</a></td><!--Vision Master T190-->       
        <td><a href="https://store.rakwireless.com/products/wisblock-meshtastic-starter-kit?variant=43884035113158" target="_blank" rel="noopener noreferrer">$27.99</a></td><!--RAKRAK19007-->
        <td><a href="https://store.rakwireless.com/products/wismesh-pocket?variant=43640511365318" target="_blank" rel="noopener noreferrer">$99.00</a></td><!--WisMesh-->
        <td><a href="https://www.lilygo.cc/products/t-deck" target="_blank" rel="noopener noreferrer">$52.13</a></td><!--T-Deck-->
        <td><a href="https://www.lilygo.cc/products/t-echo" target="_blank" rel="noopener noreferrer">$54.41</a></td><!--T-Echo-->
        <td><a href="https://www.lilygo.cc/products/t-beam-v1-1-esp32-lora-module" target="_blank" rel="noopener noreferrer">$32.80</a></td><!--T-Beam-->
        <td><a href="https://www.lilygo.cc/products/t-beamsupreme-m" target="_blank" rel="noopener noreferrer">$44.17/ $70.17</a></td><!--T-Beam-Supreme-->
        <td><a href="https://www.lilygo.cc/products/t3s3-v1-0" target="_blank" rel="noopener noreferrer">$17.58</a></td><!--T3-S3-->
        <td><a href="https://shop.uniteng.com/product/meshtastic-mesh-device-station-edition/" target="_blank" rel="noopener noreferrer">$109.00</a></td><!--Station G2-->
        <td><a href="https://shop.uniteng.com/product/meshtastic-mesh-device-nano-g2-ultra/" target="_blank" rel="noopener noreferrer">$86.00</a></td><!--Nano G2 Ultra-->
        <td><a href="https://www.seeedstudio.com/Wio-Tracker-1110-Dev-Board-p-5799.html" target="_blank" rel="noopener noreferrer">$39.90</a></td><!--Wio Tracker 1110-->
        <td><a href="https://www.tindie.com/products/harukitoreda/heltxt-standalone-meshtastic-communicator/" target="_blank" rel="noopener noreferrer">$90.00</a></td><!--Heltxt-->       
        <td><a href="https://www.etsy.com/listing/1390142667/meshenger-standalone-device-for" target="_blank" rel="noopener noreferrer">$250.00</a></td><!--Meshenger-->
      </tr>
      <tr>
        <td>MCU Chip</td>
        <td>ESP32-D0</td><!--Heltec V2-->
        <td>ESP32-S3</td><!--Heltec V3-->
        <td>ESP32-S3FN8</td><!--Wireless Paper-->
        <td>ESP32-S3</td><!--Wireless Stick Lite-->
        <td>ESP32-S3FN8</td><!--Wireless Tracker-->
        <td>ESP32-S3FN8</td><!--Capsule Sensor V3-->
        <td>ESP32-S3R8</td><!--Vision Master E213-->
        <td>ESP32-S3R8</td><!--Vision Master E290-->
        <td>ESP32-S3R8</td><!--Vision Master T190-->        
        <td>NRF52840</td><!--RAKRAK19007-->
        <td>NRF52840</td><!--WisMesh-->
        <td>ESP32-S3</td><!--T-Deck-->
        <td>NRF52840</td><!--T-Echo-->
        <td>ESP32-D0WDQ6-V3</td><!--T-Beam-->        
        <td>ESP32-S3FN8</td><!--T-Beam Supreme-->
        <td>ESP32-S3FH4R2</td><!--T3-S3-->  
        <td>ESP32-S3</td><!--Station G2-->
        <td>NRF52840</td><!--Nano G2 Ultra-->
        <td>NRF52840</td><!--Wio Tracker 1110-->
        <td>ESP32-S3</td><!--Heltxt-->
        <td>NRF52840</td><!--Meshenger-->
      </tr>
      <tr>
        <td>LoRa Chip</td>
        <td>SX1276 SX1278</td><!--Heltec V2-->
        <td>SX1262</td><!--Heltec V3-->
        <td>SX1262</td><!--Wireless Paper-->
        <td>SX1262</td><!--Wireless Stick Lite-->
        <td>SX1262</td><!--Wireless Tracker-->
        <td>SX1262</td><!--Capsule Sensor V3-->
        <td>SX1262</td><!--Vision Master E213-->
        <td>SX1262</td><!--Vision Master E290-->
        <td>SX1262</td><!--Vision Master T190-->
        <td>SX1262</td><!--RAKRAK19007-->
        <td>SX1262</td><!--WisMesh-->
        <td>SX1262</td><!--T-Deck-->
        <td>SX1262</td><!--T-Echo-->
        <td>SX1276 SX1278</td><!--T-Beam-->
        <td>SX1262</td><!--T-Beam-Supreme-->
        <td>SX1262 SX1276 SX1280</td><!--T3-S3-->
        <td>SX1262</td><!--Station G2-->
        <td>SX1262</td><!--Nano G2 Ultra-->
        <td>LR1110</td><!--Wio Tracker 1110-->
        <td>SX1262</td><!--Heltxt-->
        <td>SX1262</td><!--Meshenger-->
      </tr>
      <tr>
        <td>GPS/GNSS</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>UC6580</td><!--Wireless Tracker-->
        <td>L76k</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->        
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->
        <td>L76k</td><!--T-Echo-->
        <td>NEO-6M/M8N</td><!--T-Beam-->
        <td>L76k/ MAX-M10S</td><!--T-Beam-Supreme-->         
        <td>-</td><!--T3-S3-->          
        <td>-</td><!--Station G2-->
        <td>ATGM336H-5N</td><!--Nano G2 Ultra--> 
        <td>Grove Air530 GPS</td><!--Wio Tracker 1110-->
        <td>GT-U7</td><!--Heltxt-->
        <td>u-Blox MAX-7Q</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Charging Interface</td>
        <td>Micro USB</td><!--Heltec V2-->
        <td>USB-C</td><!--Heltec V3-->
        <td>USB-C</td><!--Wireless Paper-->
        <td>USB-C</td><!--Wireless Stick Lite-->
        <td>USB-C</td><!--Wireless Tracker-->
        <td>Wireless Boot</td><!--Capsule Sensor V3-->
        <td>USB-C</td><!--Vision Master E213-->
        <td>USB-C</td><!--Vision Master E290-->
        <td>USB-C</td><!--Vision Master T190-->
        <td>USB-C</td><!--RAKRAK19007-->   
        <td>USB-C</td><!--WisMesh-->
        <td>USB-C</td><!--T-Deck-->
        <td>USB-C</td><!--T-Echo-->
        <td>Micro USB</td><!--T-Beam-->
        <td>USB-C</td><!--T-Beam-Supreme-->            
        <td>USB-C</td><!--T3-S3-->
        <td>USB-C</td><!--Station G2-->
        <td>USB-C</td><!--Nano G2 Ultra-->
        <td>USB-C</td><!--Wio Tracker 1110-->
        <td>USB-C</td><!--Heltxt-->
        <td>USB-C</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Frequency</td>
        <td>433~510 MHz, 863~928 MHz</td><!--Heltec V2-->
        <td>433~510 MHz, 863~928 MHz</td><!--Heltec V3-->
        <td>433~510 MHz, 863~928 MHz</td><!--Wireless Paper-->
        <td>433~510 MHz, 863~928 MHz</td><!--Wireless Stick Lite-->
        <td>433~510 MHz, 863~928 MHz</td><!--Wireless Tracker-->
        <td>433~510 MHz, 863~928 MHz</td><!--Capsule Sensor V3-->
        <td>433~510 MHz, 863~928 MHz</td><!--Vision Master E213-->
        <td>433~510 MHz, 863~928 MHz</td><!--Vision Master E290-->
        <td>433~510 MHz, 863~928 MHz</td><!--Vision Master T190-->
        <td>433~510 MHz, 863~928 MHz</td><!--RAKRAK19007-->     
        <td>433~510 MHz, 863~928 MHz</td><!--WisMesh-->
        <td>433~510 MHz, 863~928 MHz</td><!--T-Deck-->
        <td>433~510 MHz, 863~928 MHz</td><!--T-Echo-->
        <td>433~510 MHz, 863~928 MHz</td><!--T-Beam-->        
        <td>433~510 MHz, 863~928 MHz</td><!--T-Beam-Supreme-->      
        <td>433~510 MHz, 863~928 MHz</td><!--T3-S3-->    
        <td>863~928 MHz</td><!--Station G2-->
        <td>863~928 MHz</td><!--Nano G2 Ultra-->
        <td>863~928 MHz</td><!--Wio Tracker 1110-->
        <td>863~928 MHz</td><!--Heltxt-->
        <td>863~928 MHz</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Max. TX Power</td>
        <td>19 ± 1dB</td><!--Heltec V2-->
        <td>21 ± 1dBm</td><!--Heltec V3-->
        <td>21 ± 1dBm</td><!--Wireless Paper-->
        <td>21 ± 1dBm</td><!--Wireless Stick Lite-->
        <td>21 ± 1dBm</td><!--Wireless Tracker-->
        <td>21 ± 1dBm</td><!--Capsule Sensor V3-->
        <td>21 ± 1dBm</td><!--Vision Master E213-->
        <td>21 ± 1dBm</td><!--Vision Master E290-->
        <td>21 ± 1dBm</td><!--Vision Master T190-->
        <td>22 ± 1dBm</td><!--RAKRAK19007-->
        <td>22 ± 1dBm</td><!--WisMesh-->
        <td>22 ± 1dBm</td><!--T-Deck-->
        <td>22 ± 1dBm</td><!--T-Echo-->
        <td>22 ± 1dBm</td><!--T-Beam-->        
        <td>22 ± 1dBm</td><!--T-Beam-Supreme-->         
        <td>22 ± 1dBm</td><!--T3-S3-->  
        <td>35 ± 1dBm</td><!--Station G2-->
        <td>22 ± 1dBm</td><!--Nano G2 Ultra-->
        <td>20 ± 1dBm</td><!--Wio Tracker 1110-->
        <td>21 ± 1dBm</td><!--Heltxt-->
        <td>22 ± 1dBm</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Max. Receiving Sensitivity</td>
        <td>-148 dBm</td><!--Heltec V2-->
        <td>-136 dBm</td><!--Heltec V3-->
        <td>-134 dBm</td><!--Wireless Paper-->
        <td>-134 dBm</td><!--Wireless Stick Lite-->
        <td>-137 dBm</td><!--Wireless Tracker-->
        <td>-135 dBm</td><!--Capsule Sensor V3-->
        <td>-136 dBm</td><!--Vision Master E213-->
        <td>-136 dBm</td><!--Vision Master E290-->    
        <td>-136 dBm</td><!--Vision Master T190-->    
        <td>-136 dBm</td><!--RAKRAK19007-->     
        <td>-136 dBm</td><!--WisMesh-->
        <td>-136 dBm</td><!--T-Deck-->
        <td>-136 dBm</td><!--T-Echo-->     
        <td>-148 dBm</td><!--T-Beam-->
        <td>-136 dBm</td><!--T-Beam-Supreme-->            
        <td>-136 dBm</td><!--T3-S3-->   
        <td>?</td><!--Station G2-->
        <td>?</td><!--Nano G2 Ultra-->
        <td>-141 dBm</td><!--Wio Tracker 1110-->
        <td>-136 dBm</td><!--Heltxt-->
        <td>-136 dBm</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Wi-Fi</td>
        <td>YES</td><!--Heltec V2-->
        <td>YES</td><!--Heltec V3-->
        <td>YES</td><!--Wireless Paper-->
        <td>YES</td><!--Wireless Stick Lite-->
        <td>YES</td><!--Wireless Tracker-->
        <td>YES</td><!--Capsule Sensor V3-->
        <td>YES</td><!--Vision Master E213-->
        <td>YES</td><!--Vision Master E290-->
        <td>YES</td><!--Vision Master T190-->
        <td>NO</td><!--RAKRAK19007-->       
        <td>NO</td><!--WisMesh-->
        <td>YES</td><!--T-Deck-->
        <td>NO</td><!--T-Echo-->
        <td>YES</td><!--T-Beam-->   
        <td>YES</td><!--T-Beam-Supreme-->            
        <td>YES</td><!--T3-S3-->   
        <td>YES</td><!--Station G2-->
        <td>NO</td><!--Nano G2 Ultra-->
        <td>NO</td><!--Wio Tracker 1110-->
        <td>YES</td><!--Heltec V3-->
        <td>NO</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Bluetooth</td>
        <td>BT-5 (LE)</td><!--Heltec V2-->
        <td>BT-5 (LE)</td><!--Heltec V3-->
        <td>BT-5 (LE)</td><!--Wireless Paper-->
        <td>BT-5 (LE)</td><!--Wireless Stick Lite-->
        <td>BT-5 (LE)</td><!--Wireless Tracker-->
        <td>BT-5 (LE)</td><!--Capsule Sensor V3-->
        <td>BT-5 (LE)</td><!--Vision Master E213-->
        <td>BT-5 (LE)</td><!--Vision Master E290-->
        <td>BT-5 (LE)</td><!--Vision Master T190-->        
        <td>BT-5 (LE)</td><!--RAKRAK19007-->   
        <td>BT-5 (LE)</td><!--WisMesh-->
        <td>BT-5 (LE)</td><!--T-Deck-->
        <td>BT-5 (LE)</td><!--T-Echo-->
        <td>BT-4.2 (LE)</td><!--T-Beam-->        
        <td>BT-5 (LE)</td><!--T-Beam-Supreme-->            
        <td>BT-5 (LE)</td><!--T3-S3-->   
        <td>BT-5 (LE)</td><!--Station G2-->
        <td>BT-5.4 (LE)</td><!--Nano G2 Ultra-->
        <td>BT-5.3 (LE)</td><!--Wio Tracker 1110-->
        <td>BT-5 (LE)</td><!--Heltxt-->
        <td>BT-5 (LE)</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Display Type</td>
        <td>OLED</td><!--Heltec V2-->
        <td>OLED</td><!--Heltec V3-->
        <td>E-ink</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>TFT</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>E-ink</td><!--Vision Master E213-->
        <td>E-ink</td><!--Vision Master E290-->
        <td>TFT</td><!--Vision Master T190-->
        <td>-</td><!--RAKRAK19007-->   
        <td>OLED</td><!--WisMesh-->
        <td>LCD</td><!--T-Deck-->
        <td>E-ink</td><!--T-Echo-->
        <td>OLED</td><!--T-Beam--> 
        <td>OLED</td><!--T-Beam-Supreme-->            
        <td>OLED</td><!--T3-S3-->       
        <td>OLED</td><!--Station G2-->
        <td>OLED</td><!--Nano G2 Ultra-->
        <td>OLED</td><!--Wio Tracker 1110-->
        <td>OLED</td><!--Heltxt-->
        <td>OLED</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Display Size</td>
        <td>0.96 Inch</td><!--Heltec V2-->
        <td>0.96 Inch</td><!--Heltec V3-->
        <td>2.13 Inch</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>0.96-inch</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>2.13 Inch</td><!--Vision Master E213-->
        <td>2.9 Inch</td><!--Vision Master E290-->
        <td>1.9 Inch</td><!--Vision Master T190-->
        <td>-</td><!--RAKRAK19007--> 
        <td>1.3 Inch</td><!--WisMesh-->
        <td>2.8 Inch</td><!--T-Deck-->
        <td>1.54 Inch</td><!--T-Echo-->
        <td>0.96 Inch</td><!--T-Beam-->      
        <td>1.3 Inch</td><!--T-Beam-Supreme-->            
        <td>0.96 Inch</td><!--T3-S3-->        
        <td>1.3 Inch</td><!--Station G2-->
        <td>1.3 Inch</td><!--Nano G2 Ultra-->
        <td>0.96 Inch</td><!--Wio Tracker 1110-->
        <td>0.96 Inch</td><!--Heltxt-->
        <td>1.3 Inch</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Charging IC</td>
        <td>TP4054</td><!--Heltec V2-->
        <td>TP4054</td><!--Heltec V3-->
        <td>TP4054</td><!--Wireless Paper-->
        <td>TP4054</td><!--Wireless Stick Lite-->
        <td>TP4054</td><!--Wireless Tracker-->
        <td>TP4054</td><!--Capsule Sensor V3-->
        <td>TP4054</td><!--Vision Master E213-->
        <td>TP4054</td><!--Vision Master E290-->
        <td>TP4054</td><!--Vision Master T190-->
        <td>TP4054</td><!--RAKRAK19007-->  
        <td>TP4054</td><!--WisMesh-->
        <td>TP4054</td><!--T-Deck-->
        <td>TP4054</td><!--T-Echo-->
        <td>AXP192</td><!--T-Beam-->            
        <td>AXP2101</td><!--T-Beam-Supreme-->            
        <td>TP4054</td><!--T3-S3-->
        <td>?</td><!--Station G2-->
        <td>?</td><!--Nano G2 Ultra-->
        <td>ETA6003</td><!--Wio Tracker 1110-->
        <td>TP4054</td><!--Heltxt-->
        <td>TP4054</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Diagram</td>
        <td><a href="https://resource.heltec.cn/download/WiFi_LoRa_32/V2.1/WIFI_LoRa_32_V2.1(868-915).PDF">Diagram Link</a></td><!--Heltec V2-->
        <td><a href="https://resource.heltec.cn/download/WiFi_LoRa_32_V3/HTIT-WB32LA(F)_V3.1_Schematic_Diagram.pdf">Diagram Link</a></td><!--Heltec V3-->
        <td><a href="https://resource.heltec.cn/download/Wireless_Paper/Wireless_Paper_V0.4_Schematic_Diagram.pdf">Diagram Link</a></td><!--Wireless Paper-->
        <td><a href="https://resource.heltec.cn/download/Wireless_Stick_Lite_V3/HTIT-WSL_V3_Schematic_Diagram.pdf">Diagram Link</a></td><!--Wireless Stick Lite-->
        <td><a href="https://resource.heltec.cn/download/Wireless_Tracker/Wireless_Tacker1.1/HTIT-Tracker_V0.5.pdf">Diagram Link</a></td><!--Wireless Tracker-->
        <td><a href="https://resource.heltec.cn/download/Heltec%20Capsule%20Sensor%20V3/Capsule_Main_Esp32_Schematic_Diagram.pdf">Diagram Link</a></td><!--Capsule Sensor V3-->
        <td><a href="https://resource.heltec.cn/download/HT-VME213/HT-VME213%20Schematic%20Diagram.pdf">Diagram Link</a></td><!--Vision Master E213-->
        <td><a href="https://resource.heltec.cn/download/HT-VME290/HT-VME290%20Schematic_Diagram.pdf">Diagram Link</a></td><!--Vision Master E290-->
        <td><a href="https://resource.heltec.cn/download/HT-VMT190/HT-VMT90%20Schematic%20Diagram.pdf">Diagram Link</a></td><!--Vision Master T190-->     
        <td><a href="https://docs.rakwireless.com/Product-Categories/WisBlock/RAK4631/Datasheet/#hardware">Diagram Link</a></td><!--RAKRAK19007-->        
        <td><a href="">-</a></td><!--WisMesh-->
        <td><a href="https://github.com/Xinyuan-LilyGO/T-Deck/blob/master/schematic/schematic.pdf">Diagram Link</a></td><!--T-Deck-->
        <td><a href="https://github.com/Xinyuan-LilyGO/T-Echo/blob/main/T-Echo_Schematic.pdf">Diagram Link</a></td><!--T-Echo-->
        <td><a href="https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series/blob/master/schematic/LilyGo_TBeam_V1.2.pdf">Diagram Link</a></td><!--T-Beam-->         
        <td><a href="https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series/blob/master/schematic/LilyGo_T-BeamS3Supreme.pdf">Diagram Link</a></td><!--T-Beam-Supreme-->         
        <td><a href="https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series/blob/master/schematic/T3_S3_V1.2.pdf">Diagram Link</a></td><!--T3-S3-->         
        <td><a href="https://wiki.uniteng.com/en/meshtastic/station-g2">Diagram Link</a></td><!--Station G2-->
        <td><a href="https://wiki.uniteng.com/meshtastic/nano-g2-ultra">Diagram Link</a></td><!--Nano G2 Ultra-->
        <td><a href="https://files.seeedstudio.com/products/SenseCAP/Wio-Tracker/Wio%20Tracker%201110%20v1.0_SCH_PDF_20230822.pdf">Diagram Link</a></td><!--Wio Tracker 1110-->
        <td><a href="https://www.printables.com/model/750293-hel-txt-standalone-meshtastic-communicator-heltec">Diagram Link</a></td><!--Heltxt-->
        <td><a href="https://www.printables.com/model/389311-meshenger-standalone-communicator-device-for-mesht">Diagram Link</a></td><!--Meshenger-->
      </tr>
      <tr>
        <td>Input</td>
        <td>User Button, Reset Button</td><!--Heltec V2-->
        <td>User Button, Reset Button</td><!--Heltec V3-->
        <td>User Button, Reset Button</td><!--Wireless Paper-->
        <td>User Button, Reset Button</td><!--Wireless Stick Lite-->
        <td>User Button, Reset Button</td><!--Wireless Tracker-->
        <td>User Button, Reset Button</td><!--Capsule Sensor V3-->
        <td>User Button, Reset Button, 3rd Button</td><!--Vision Master E213-->
        <td>User Button, Reset Button, 3rd Button</td><!--Vision Master E290-->
        <td>User Button, Reset Button, 3rd Button</td><!--Vision Master E290-->        
        <td>Reset Button</td><!--RAKRAK19007-->        
        <td>User Button, Reset Button</td><!--WisMesh-->
        <td>Touch Screen, Keyboard, trackball, Reset Button</td><!--T-Deck-->
        <td>User Button, Reset Button, Touch Button</td><!--T-Echo-->
        <td>User Button, Reset Button, Power Button</td><!--T-Beam-->        
        <td>User Button, Reset Button, Power Button</td><!--T-Beam-Supreme-->            
        <td>User Button, Reset Button</td><!--T3-S3-->   
        <td>User Button, Reset Button, Boot Button</td><!--Station G2-->
        <td>4 Buttons</td><!--Nano G2 Ultra-->
        <td>User Button, Reset Button</td><!--Wio Tracker 1110-->
        <td>Keyboard, User Button, Reset Button</td><!--Heltxt-->
        <td>Keyboard, User Button, Reset Button</td><!--Meshenger-->
      </tr>       
      <tr>
        <td>Temp/ Humidity Sensor</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>-</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>-</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td>SHT41</td><!--Wio Tracker 1110-->
        <td>BME680</td><!--Heltxt-->
        <td>-</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Air Pressure Sensor</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>-</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>-</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td>-</td><!--Wio Tracker 1110-->
        <td>BME680</td><!--Heltxt-->
        <td>-</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Air Quality Sensor</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->         
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>-</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>-</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td>-</td><!--Wio Tracker 1110-->
        <td>BME680</td><!--Heltxt-->
        <td>-</td><!--Meshenger-->
      </tr>
      <tr>
        <td>External Notification</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>Buzzer</td><!--T-Deck-->      
        <td>-</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>-</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td>-</td><!--Wio Tracker 1110-->
        <td>Buzzer / Vibration</td><!--Heltxt-->
        <td>Buzzer / Vibration / LED</td><!--Meshenger-->
      </tr>
      <tr>
        <td>UART Port</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>1x Quiic</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->         
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>-</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>-</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td>1X Grove</td><!--Wio Tracker 1110-->
        <td>-</td><!--Heltxt-->
        <td>-</td><!--Meshenger-->
      </tr>
      <tr>
        <td>I2C Port</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>1x Quiic</td><!--Vision Master E213-->
        <td>1X Quiic</td><!--Vision Master E290-->
        <td>1X Quiic</td><!--Vision Master T190-->         
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>-</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>-</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td>1X Grove</td><!--Wio Tracker 1110-->
        <td>-</td><!--Heltxt-->
        <td>-</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Battery</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>250mAh</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->         
        <td>-</td><!--Vision Master T190-->         
        <td>-</td><!--RAKRAK19007-->
        <td>3200mAh</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>850mAh</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>-</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td></td><!--Wio Tracker 1110-->
        <td>4000mAh</td><!--Heltxt-->
        <td>4000mAh</td><!--Meshenger-->
      </tr>      
      <tr>
        <td>Enclosure</td>
        <td>-</td><!--Heltec V2-->
        <td>ABS Case</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>ABS Case</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->         
        <td>-</td><!--RAKRAK19007-->
        <td>?</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>ABS Case</td><!--T-Echo-->
        <td>-</td><!--T-Beam-->        
        <td>-</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>Resin</td><!--Station G2-->
        <td>Resin</td><!--Nano G2 Ultra-->
        <td></td><!--Wio Tracker 1110-->
        <td>PLA Case</td><!--Heltxt-->
        <td>ASA, PETG, TPU Case</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Meshtastic Preloaded</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>Yes</td><!--Capsule Sensor V3-->
        <td>-</td><!--Vision Master E213-->
        <td>-</td><!--Vision Master E290-->
        <td>-</td><!--Vision Master T190-->         
        <td>-</td><!--RAKRAK19007-->
        <td>Yes</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>Yes</td><!--T-Echo-->
        <td>Yes</td><!--T-Beam-->        
        <td>Yes</td><!--T-Beam-Supreme-->            
        <td>-</td><!--T3-S3-->                  
        <td>Yes</td><!--Station G2-->
        <td>Yes</td><!--Nano G2 Ultra-->
        <td></td><!--Wio Tracker 1110-->
        <td>Yes</td><!--Heltxt-->
        <td>Yes</td><!--Meshenger-->
      </tr>      
      <tr>
        <td>Memory ROM</td>
        <td>448KB ROM</td><!--Heltec V2-->
        <td>384KB ROM</td><!--Heltec V3-->
        <td>384KB ROM</td><!--Wireless Paper-->
        <td>384KB ROM</td><!--Wireless Stick Lite-->
        <td>384KB ROM</td><!--Wireless Tracker-->
        <td>384KB ROM</td><!--Capsule Sensor V3-->
        <td>384KB ROM</td><!--Vision Master E213-->
        <td>384KB ROM</td><!--Vision Master E290-->
        <td>384KB ROM</td><!--Vision Master T190-->         
        <td>?</td><!--RAKRAK19007-->
        <td>?</td><!--WisMesh-->
        <td>384KB ROM</td><!--T-Deck-->      
        <td>?</td><!--T-Echo-->
        <td>384KB ROM</td><!--T-Beam-->        
        <td>384KB ROM</td><!--T-Beam-Supreme-->            
        <td>384KB ROM</td><!--T3-S3-->            
        <td>384KB ROM</td><!--Station G2-->
        <td>?</td><!--Nano G2 Ultra-->
        <td></td><!--Wio Tracker 1110-->
        <td>384KB ROM</td><!--Heltxt-->
        <td>?</td><!--Meshenger-->
      </tr>
      <tr>
        <td>Memory SRAM</td>
        <td>520KB SRAM</td><!--Heltec V2-->
        <td>512KB SRAM</td><!--Heltec V3-->
        <td>512KB SRAM</td><!--Wireless Paper-->
        <td>512KB SRAM</td><!--Wireless Stick Lite-->
        <td>512KB SRAM</td><!--Wireless Tracker-->
        <td>512KB SRAM</td><!--Capsule Sensor V3-->
        <td>512KB SRAM</td><!--Vision Master E213-->
        <td>512KB SRAM</td><!--Vision Master E290-->
        <td>512KB SRAM</td><!--Vision Master T190-->         
        <td>?</td><!--RAKRAK19007-->
        <td>?</td><!--WisMesh-->
        <td>512KB SRAM</td><!--T-Deck-->      
        <td>?</td><!--T-Echo-->
        <td>512KB SRAM</td><!--T-Beam-->        
        <td>512KB SRAM</td><!--T-Beam-Supreme-->            
        <td>512KB SRAM</td><!--T3-S3-->         
        <td>512KB SRAM</td><!--Station G2-->
        <td>?</td><!--Nano G2 Ultra-->
        <td></td><!--Wio Tracker 1110-->
        <td>512KB SRAM</td><!--Heltxt-->
        <td>?</td><!--Meshenger-->
      </tr>      
      <tr>
        <td>Memory RTC SRAM</td>
        <td>16KB RTC SRAM</td><!--Heltec V2-->
        <td>16KB RTC SRAM</td><!--Heltec V3-->
        <td>16KB RTC SRAM</td><!--Wireless Paper-->
        <td>16KB RTC SRAM</td><!--Wireless Stick Lite-->
        <td>16KB RTC SRAM</td><!--Wireless Tracker-->
        <td>16KB RTC SRAM</td><!--Capsule Sensor V3-->
        <td>16KB RTC SRAM</td><!--Vision Master E213-->
        <td>16KB RTC SRAM</td><!--Vision Master E290-->
        <td>16KB RTC SRAM</td><!--Vision Master T190-->         
        <td>?</td><!--RAKRAK19007-->
        <td>?</td><!--WisMesh-->
        <td>16KB RTC SRAM</td><!--T-Deck-->
        <td>?</td><!--T-Echo-->
        <td>16KB RTC SRAM</td><!--T-Beam-->
        <td>16KB RTC SRAM</td><!--T-Beam-Supreme-->
        <td>16KB RTC SRAM</td><!--T3-S3-->
        <td>16KB RTC SRAM</td><!--Station G2-->
        <td>?</td><!--Nano G2 Ultra-->
        <td></td><!--Wio Tracker 1110-->
        <td>16KB RTC SRAM</td><!--Heltxt-->
        <td>?</td><!--Meshenger-->
      </tr>      
      <tr>
        <td>Memory SiP Flash</td>
        <td>-</td><!--Heltec V2-->
        <td>8MB SiP Flash</td><!--Heltec V3-->
        <td>8MB SiP Flash</td><!--Wireless Paper-->
        <td>8MB SiP Flash</td><!--Wireless Stick Lite-->
        <td>8MB SiP Flash</td><!--Wireless Tracker-->
        <td>8MB SiP Flash</td><!--Capsule Sensor V3-->
        <td>8MB SiP Flash</td><!--Vision Master E213-->
        <td>8MB SiP Flash</td><!--Vision Master E290-->
        <td>8MB SiP Flash</td><!--Vision Master T190-->         
        <td>?</td><!--RAKRAK19007-->
        <td>?</td><!--WisMesh-->
        <td>-</td><!--T-Deck-->      
        <td>?</td><!--T-Echo-->
        <td></td><!--T-Beam-->        
        <td></td><!--T-Beam-Supreme-->            
        <td></td><!--T3-S3-->          
        <td>8MB SiP Flash</td><!--Station G2-->
        <td>16MB SiP Flash</td><!--Nano G2 Ultra-->
        <td></td><!--Wio Tracker 1110-->
        <td>8MB SiP Flash</td><!--Heltxt-->
        <td>?</td><!--Meshenger-->
      </tr>     
      <tr>
        <td>Memory PSRAM</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>8MB PSRAM</td><!--Vision Master E213-->
        <td>8MB PSRAM</td><!--Vision Master E290-->
        <td>8MB PSRAM</td><!--Vision Master T190-->
        <td>-</td><!--RAKRAK19007-->
        <td>-</td><!--WisMesh-->
        <td>8MB PSRAM</td><!--T-Deck-->      
        <td>-</td><!--T-Echo-->
        <td>8MB PSRAM</td><!--T-Beam-->        
        <td>8MB PSRAM</td><!--T-Beam-Supreme-->            
        <td>8MB PSRAM</td><!--T3-S3-->
        <td>8MB PSRAM</td><!--Station G2-->
        <td>-</td><!--Nano G2 Ultra-->
        <td>-</td><!--Wio Tracker 1110-->
        <td>-</td><!--Heltxt-->
        <td>-</td><!--Meshenger-->
      </tr>           
      <tr>
        <td>Memory Flash</td>
        <td>-</td><!--Heltec V2-->
        <td>-</td><!--Heltec V3-->
        <td>-</td><!--Wireless Paper-->
        <td>-</td><!--Wireless Stick Lite-->
        <td>-</td><!--Wireless Tracker-->
        <td>-</td><!--Capsule Sensor V3-->
        <td>16MB Flash</td><!--Vision Master E213-->
        <td>16MB Flash</td><!--Vision Master E290-->
        <td>16MB Flash</td><!--Vision Master T190-->         
        <td>1MB Flash</td><!--RAKRAK19007-->
        <td>1MB Flash</td><!--WisMesh-->
        <td>16MB Flash</td><!--T-Deck-->      
        <td>1MB Flash</td><!--T-Echo-->
        <td>16MB Flash</td><!--T-Beam-->        
        <td>16MB Flash</td><!--T-Beam-Supreme-->            
        <td>16MB Flash</td><!--T3-S3-->                  
        <td>16MB Flash</td><!--Station G2-->
        <td>1MB Flash	</td><!--Nano G2 Ultra-->
        <td>1MB Flash</td><!--Wio Tracker 1110-->
        <td>-</td><!--Heltxt-->
        <td>1MB Flash</td><!--Meshenger-->
      </tr>                       
    </tbody>
  </table>
</div>

<script>
document.querySelectorAll('.mcuFilter, .loraFilter, .gpsFilter, .screenFilter, .wifiFilter, .inputFilter, .priceFilter, .brandFilter, .caseFilter, .batteryFilter, .meshtasticFilter, .readyFilter').forEach(filter => {
  filter.addEventListener('change', filterTable);
});

function filterTable() {
  const mcuFilters = Array.from(document.querySelectorAll('.mcuFilter:checked')).map(cb => cb.value);
  const loraFilters = Array.from(document.querySelectorAll('.loraFilter:checked')).map(cb => cb.value);
  const gpsFilters = Array.from(document.querySelectorAll('.gpsFilter:checked')).map(cb => cb.value);
  const screenFilters = Array.from(document.querySelectorAll('.screenFilter:checked')).map(cb => cb.value);
  const wifiFilters = Array.from(document.querySelectorAll('.wifiFilter:checked')).map(cb => cb.value);
  const inputFilters = Array.from(document.querySelectorAll('.inputFilter:checked')).map(cb => cb.value);
  const priceFilters = Array.from(document.querySelectorAll('.priceFilter:checked')).map(cb => cb.value);
  const brandFilters = Array.from(document.querySelectorAll('.brandFilter:checked')).map(cb => cb.value);
  const caseFilters = Array.from(document.querySelectorAll('.caseFilter:checked')).map(cb => cb.value);
  const batteryFilters = Array.from(document.querySelectorAll('.batteryFilter:checked')).map(cb => cb.value);
  const meshtasticFilters = Array.from(document.querySelectorAll('.meshtasticFilter:checked')).map(cb => cb.value);
  const readyFilters = Array.from(document.querySelectorAll('.readyFilter:checked')).map(cb => cb.value);

  const columns = document.querySelectorAll('#comparisonTable thead th');
  const rows = document.querySelectorAll('#comparisonTable tbody tr');

  function getPriceRange(price) {
    if (price <= 20) return '0-20';
    if (price <= 40) return '21-40';
    if (price <= 60) return '41-60';
    return '61+';
  }

  function shouldDisplayColumn(column) {
    const mcu = column.getAttribute('data-mcu');
    const lora = column.getAttribute('data-lora').split(' '); // Split LoRa chips into an array
    const gps = column.getAttribute('data-gps');
    const screen = column.getAttribute('data-screen');
    const wifi = column.getAttribute('data-wifi');
    const input = column.getAttribute('data-input').split(', ');
    const price = parseFloat(column.getAttribute('data-price'));
    const brand = column.getAttribute('data-brand');
    const caseIncluded = column.getAttribute('data-case');
    const batteryIncluded = column.getAttribute('data-battery');
    const meshtastic = column.getAttribute('data-meshtastic');
    const ready = column.getAttribute('data-ready');

    const mcuMatch = mcuFilters.length === 0 || mcuFilters.includes(mcu);
    const loraMatch = loraFilters.length === 0 || loraFilters.some(loraType => lora.includes(loraType)); // Updated to handle multiple LoRa chips
    const gpsMatch = gpsFilters.length === 0 || gpsFilters.includes(gps);
    const screenMatch = screenFilters.length === 0 || screenFilters.includes(screen);
    const wifiMatch = wifiFilters.length === 0 || wifiFilters.includes(wifi);
    const inputMatch = inputFilters.length === 0 || inputFilters.some(inputType => input.includes(inputType));
    const priceMatch = priceFilters.length === 0 || priceFilters.includes(getPriceRange(price));
    const brandMatch = brandFilters.length === 0 || brandFilters.includes(brand);
    const caseMatch = caseFilters.length === 0 || caseFilters.includes(caseIncluded);
    const batteryMatch = batteryFilters.length === 0 || batteryFilters.includes(batteryIncluded);
    const meshtasticMatch = meshtasticFilters.length === 0 || meshtasticFilters.includes(meshtastic);
    const readyMatch = readyFilters.length === 0 || readyFilters.includes(ready);

    return mcuMatch && loraMatch && gpsMatch && screenMatch && wifiMatch && inputMatch && priceMatch && brandMatch && caseMatch && batteryMatch && meshtasticMatch && readyMatch;
  }

  columns.forEach(column => {
    if (column.cellIndex === 0) return;
    const display = shouldDisplayColumn(column) ? '' : 'none';
    column.style.display = display;
    rows.forEach(row => {
      row.children[column.cellIndex].style.display = display;
    });
  });
}
</script>
