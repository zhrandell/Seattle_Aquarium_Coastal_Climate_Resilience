# Hardware and Software 

The intent of this document is to make ROV information as accessible as possible in order to give other entities a head start when considering initiating their own ROV program. To do this we summarize information about (**1**) the primary hardware being used in the field to support our Coastal Complexity & Resilience (CCR) projects, and (**2**) ROV firmware as well as analytical software supporting our analyses and communication. We include links to websites, the purpose of the component, and the price (at the time of document compilation). Prices are subject to vary over time; prices do not include sales tax. 

We have x2 BlueROV2s. Our original, ROV _Nereo_ is powered by the standard Blue Robotics 14.8V, 15.6Ah battery. Our second ROV, ROV _Lutris_ is configured to recieve power via the Outland Technology power supply system, itself powered by x2 200Ah lithium-ion batteries on the Seattle Aquarium vessel. We break down the distinct hardware below via the two sections. Aside from the power supply, all other components (lights, cameras, DVL, etc.) are identical. 

Please feel free to contact z.randell@seattleaqaurium.org regarding questions about these components, particularly if you are interested in obtaining a laptop optimized for ROV operations, or if you are interested in WaterLinked's acoustic GPS tracking system. 

## Hardware

### Components shared across both ROVs
<table>
  <tr> <td> <i>Component</i> </td> <td> <i>Purpose</i> </td> <td> <i>Price</i> </td> </tr>
  <tr> <td> <a href="https://bluerobotics.com/store/rov/bluerov2/"> BlueROV2 </a></td> <td> Conduct benthic surveys via photo and video collection </td> <td> $3490 </td> </tr>
  <tr> <td> <a href="https://bluerobotics.com/store/rov/bluerov2-upgrade-kits/brov2-heavy-retrofit-r1-rp/"> Heavy retrofit kit </a></td> <td> Provide additional thrust </td> <td> $740 </td> </tr>
  <tr> <td> <a href="https://bluerobotics.com/store/rov/bluerov2-accessories/brov-payload-skid/"> Payload skid </a></td> <td> Provides undercarriage for lights, cameras, and sensors </td> <td> $300 </td> </tr>
</table>

### Components specific to ROV _Nereo_ -- standard battery power
<table>
<tr> <td> <i>Component</i> </td> <td> <i>Purpose</i> </td> <td> <i>Price</i> </td> </tr>
<tr> <td> <a href="https://bluerobotics.com/store/comm-control-power/powersupplies-batteries/battery-li-4s-15-6ah/"> 14.8V, 15.6Ah </a> battery </td> <td> On-board power supply </td> <td> $380 </td> </tr>
<tr> <td> <a href="https://bluerobotics.com/store/cables-connectors/cables/fathom-rov-tether-rov-ready/"> 150m tether </a></td> <td> Necessary for ROV navigation and communication </td> <td> $1000 </td> </tr>
<tr> <td> <a href="https://bluerobotics.com/store/cables-connectors/tether-management/tms-asm-kit-vp/"> Tether spool </a></td> <td> Tether management </td> <td> $680 </td> </tr>
</table>


### Components specific to ROV _Lutris_ -- surface-supplied power for extended operations
<table>
<tr> <td> <i>Component</i> </td> <td> <i>Purpose</i> </td> <td> <i>Price</i> </td> </tr>
<tr> <td> <a href="https://bluerobotics.com/store/comm-control-power/powersupplies-batteries/otps1kw/"> Outland Technology power supply </a> </td> <td> Provide power down the ROV's (125m) tether </td> <td> $12,800 </td> </tr>
<tr> <td> <a href="https://www.dropbox.com/scl/fi/0qq1bzaal2ee7c7cy3qlz/vessel_power_supply.jpg?rlkey=ri8nqzq1ftqcamb4ldnr3gfk7&dl=0"> Custom power bank </a> consisting of x2 200Ah Victron Li-ion batteries, Victron multi 2000 inverter and charger </td> <td> Power the ROV from the surface </td> <td> custom install; price will vary; it cost us ~$12k via the excellent Shawn Rutan at <a href="https://boatwired.com/"> BoatWired </a> </td> </tr>
</table>


### Sensors
<table>
<tr> <td> <i>Component</i> </td> <td> <i>Purpose</i> </td> <td> <i>Price</i> </td> </tr>
<tr> <td> <a href="https://waterlinked.com/shop/underwater-gps-g2-standard-kit-132?hsCtaTracking=0a800400-424e-4db6-93bc-2b699c906568%7C4c019475-c807-4b4d-94e9-fea9b444eeec#attr=19"> UGPS G2 box </a></td> <td> WaterLinked's G2 box that integrates the acoustic and topside information </td> <td> $3690 </td> </tr>
<tr> <td> <a href="https://waterlinked.com/shop/underwater-gps-g2-locator-u1-122?category=2#attr="> Locator U1 </a></td> <td> Acoustic transmitter affixed to the ROV </td> <td> $2090 </td> </tr>
<tr> <td> <a href="https://waterlinked.com/shop/underwater-gps-antenna-102"> UGPS antenna </a></td> <td> Receives acoustic signal from U1 transmitter </td> <td> $2450 </td> </tr>
<tr> <td> <a href="https://bluerobotics.com/store/the-reef/dvl-a50/"> DVL-A50 </a></td> <td> WaterLinked's Doppler Velocity Log precisely tracks ROV movement across the seafloor enabling fine-scale ROV positioning </td> <td> $6950 </td> </tr>
<tr> <td> <a href="https://www.advancednavigation.com/inertial-navigation-systems/satellite-compass/gnss-compass/"> GNSS Satellite Compass </a></td> <td> The compass provides highly precise topside GPS and compass information that we feed to the UGPS G2 box </td> <td> $2495 </td> </tr>
</table>

### Cameras, lights, and light mounts 
<table>
  <tr> <td> <a href="https://opticaloceansales.com/products/kraken-solarflare-mini18-video-light-18-000-lumens?srsltid=AfmBOooGV_FYsP4oqP2JGPHTVSngo_kLUL0I4SAyGWN_k_1BgDUX_T7n"> x4 down-facing Kraken lights</a>, 18000 lumens each (stepped down to 15000 lumens) </td> <td> Benthic illumination </td> <td> $799 </td> </tr>
  <tr> <td> <a href="https://gopro.com/en/us/shop/cameras/hero10-black/CHDHX-101-master.html?option-id=CHDHX-101-master"> x3 GoPro HERO 12/13 </a></td> <td> x2 downward-facing photo & x1 forward-facing video </td> <td> $349 per unit  </td> </tr>
    <tr> <td> <a href="https://gopro.com/en/us/shop/mounts-accessories/protective-housing-plus-waterproof-case/ADDIV-001.html"> GoPro protective housing </a></td> <td> Waterproof housing down to 60m </td> <td> $45 </td> </tr>
  <tr> <td> <a href="https://www.backscatter.com/Ultralight-14-20-Adaptor-Female"> x4 Ultralight Ball & 1/4-20 threaded Hole </a></td> <td> Attach to ROV frame  </td> <td> $26 each </td> </tr>
  <tr> <td> <a href="https://www.backscatter.com/Ultralight-New-Style-Clamp-15-degrees-side-movemen"> Ultralight New Style Clamp </a></td> <td> Attach to frame mount and light mount </td> <td> $36 each </td> </tr>
  <tr> <td> <a href="https://www.backscatter.com/Ultralight-Aquavision-Type-Mount-Narrow-w-Std-and"> Ultralight Aquavision Type Mount-Narrow </a></td> <td> Connect to New Style Clamp and provide mount for Lumen lights </td> <td> $27 </td> </tr>
</table>

### Topside ROV command console
<table>
<tr> <td> <i>Component</i> </td> <td> <i>Purpose</i> </td> <td> <i>Price</i> </td> </tr>
<tr> <td> <a href="https://www.dell.com/en-us/shop/dell-laptops/latitude-5430-rugged-laptop/spd/latitude-14-5430-laptop"> Latitude 5430 Rugged Laptop; 64GB RAM; i5 processor </a></td> <td> Dedicated laptop to operate ROV </td> <td> starting $1709 </td> </tr>
 <tr> <td> <a href="https://www.pelican.com/us/en/product/cases/protector/1610"> 1610 Pelican Case </a></td> <td> Dedicated topside consol to contain laptop and all cables </td> <td> $325.95 </td> </tr>  
<tr> <td> <a href="https://www.amazon.com/Jackery-Portable-Explorer-Generator-Optional/dp/B082TMBYR6/ref=sr_1_3?keywords=jackery+300&qid=1679865947&sprefix=jackery%2Caps%2C178&sr=8-3&ufe=app_do%3Aamzn1.fos.c3015c4a-46bb-44b9-81a4-dc28e6d374b3"> Jackery Explorer 300 </a></td> <td> Power for GPS system, 2nd screen, and laptop </td> <td> $299.99 </td> </tr>
<tr> <td> <a href="https://www.xenarc.com/1022YH-10-inch-sunlight-readable-lcd-display-monitor-with-hdmi-dvi-vga-av-inputs.html"> 2nd screen  </a></td> <td> Display navigational information from GPS </td> <td> $499 </td> </tr>  
<tr> <td> <a href="https://www.amazon.com/Xbox-Core-Controller-Carbon-Black-one/dp/B08DF248LD/ref=sr_1_4?crid=1021IBD9OXI1A&keywords=Xbox+game+controller&qid=1679866086&sprefix=xbox+game+controlle%2Caps%2C152&sr=8-4"> Xbox controller </a></td> <td> Fly ROV </td> <td> $48 </td> </tr>  
</table>


## Software 

### BlueOS extensions and telemetry analysis tools
<table>
  <tr> <td> <i>Program</i> </td> <td> <i>Purpose</i> </td> <td> <i>Availability</i> </td> </tr>
  <tr> <td> <a href="https://github.com/clydemcqueen/wl_ugps_external_extension"> wl_ugps_external_extension </a></td> <td> A BlueOS Extension that listens for NMEA messages (GGA and HDT) and sends position information to the Water Linked UGPS system  </td> <td> open-source </td> </tr>
<tr> <td> <a href="https://github.com/clydemcqueen/ardusub_log_tools"> ardusub_log_tools </a></td> <td> A collection of log analysis tools for working with ArduSub vehicles </td> <td> open-source </td> </tr>
<tr> <td> <a href="https://github.com/clydemcqueen/wl_ugps_acoustic_analysis"> wl_ugps_acoustic_analysis </a></td> <td> Capture and process acoustic data from a Waterlinked UGPS system </td> <td> open-source </td> </tr>
<tr> <td> <a href="https://github.com/clydemcqueen/ardusub_localization"> ardusub_localization </a></td> <td> Tools to run ArduSub localization experiments </td> <td> open-source </td> </tr>
<tr> <td> <a href="https://plotjuggler.io/"> PlotJuggler </a></td> <td> Fast, intuitive and extensible
time series visualization tool </td> <td> open-source </td> </tr>
</table>

### ROV firmware and laptop software (and see [here](https://github.com/zhrandell/Seattle_Aquarium_CCR_development/blob/main/files/ROV_firmware_software_versions.md) for more detailed information)
<table>
  <tr> <td> <i>Program</i> </td> <td> <i>Purpose</i> </td> <td> <i>Availability</i> </td> </tr>
  <tr> <td> <a href="https://www.ardusub.com/"> ArduSub </a></td>  <td> ROV flight control firmware </td> <td> available to download </td> </tr>
  <tr> <td> <a href="https://docs.bluerobotics.com/ardusub-zola/software/onboard/BlueOS-1.0/overview/"> BlueOS </a></td> <td> Software for the ROV's computer </td> <td> available to download </td> </tr>
  <tr> <td> <a href="http://qgroundcontrol.com/"> QGroundControl </a></td> <td> Interface with and fly ROV </td> <td> available to download </td> </tr>
  </table>

### Imagery post-processing, data analysis, map making, document preparation
<table>
<tr> <td> <i>Program</i> </td> <td> <i>Purpose</i> </td> <td> <i>Availability</i> </td> </tr>
<tr> <td> <a href="https://www.blackmagicdesign.com/products/davinciresolve/studio"> DaVince Resolve Studio </a></td> <td> Video post-processing </td> <td> $258 one-time purchase </td> </tr>
 <tr> <td> <a href="https://coralnet.ucsd.edu/about/"> CoralNet </a></td> <td> Percent-cover analysis of photos </td> <td> <a href="https://github.com/beijbom/coralnet"> Open-source</a>; web-interface </td> </tr>
<tr> <td> <a href="https://www.viametoolkit.org/wp-content/uploads/2020/09/VIAME-AI-Workshop-Aug2020.pdf"> VIAME </a></td> <td> Object detection (metrics of abundance) in photos/video </td> <td> <a href="https://github.com/viame/VIAME"> Open-source</a>; download or web-interface </td> </tr>
<tr> <td> <a href="https://www.rstudio.com/products/rstudio/download/"> R-studio </a> & <a href="https://www.r-project.org/"> R</a> </a></td> <td> Data analysis </td> <td> Available to download </td> </tr>
<tr> <td> <a href="https://www.qgis.org/en/site/"> QGIS </a> </td> <td> Mapping program </td> <td> Available to download </td> </tr>
<tr> <td> <a href="https://www.texstudio.org/"> TeXstudio </a> & <a href="https://miktex.org/"> MikTeX </a></td> <td> document creation </td> <td> Available to download </td> </tr>
<tr> <td> <a href="https://www.mendeley.com/"> Mendeley </a> </td> <td> References manager </td> <td> Available to download </td> </tr>
<tr> <td> <a href="https://desktop.github.com/"> GitHub Desktop </a> </td> <td> Interface with GitHub </td> <td> Available to download </td> </tr>
</table>
