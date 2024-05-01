# EnkWatch
<h6>Note: I am still in the process of writing the firmware</h6>
<h4>Custom designed e-ink smartwatch with 2 weeks of battery life! The watch uses a PIC MCU with a built in RTC module and attached to an external temperature and humidity
    sensor via SPI bus to display data to the user on a e-ink screen. The time/date and off-times are set, aswell as the sensors calibrated through USB 2.0 by the user through
    python scripts.The watch is enclosed is a 3D printed shell designed using solidworks.</h4>

<h4><u>Features</u></h4>
<ul>
  <li>2 Week Battery Life: Use low power components and efficient firmware to maximize battery life</li>
  <li>Power Switching and Protection: USB power can simulatenously charge the battery and power the watch. Battery overchage protection provided by a management IC and over
      discharge protection via mosfet controlled by the PIC.</li>
  <li>USB 2.0 Communication: User can ineract with the MCU through USB to set the time/date, calibrate the altitude sensor and determine at which times to power down their watch
      (for greater battery life).</li>
</ul>
