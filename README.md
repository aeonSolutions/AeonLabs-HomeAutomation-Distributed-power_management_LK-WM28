[![](https://dcbadge.vercel.app/api/server/hw3j3RwfJf) ](https://discord.gg/hw3j3RwfJf)
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
 [![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-yellow.svg?style=for-the-badge)](https://saythanks.io/to/mtpsilva)
![](https://img.shields.io/github/last-commit/aeonSolutions/PCB-Prototyping-Catalogue?style=for-the-badge)
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/l5m5z1845s10s47cuyl5" alt="trackgit-views" />
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/PCB-Prototyping-Catalogue.svg)

<br>

[PCB-Prototyping-Catalogue](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue)  >>  [Home-Automation](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Home-Automation)  >>   [Distributed Power Storage](https://github.com/aeonSolutions/AeonLabs-HomeAutomation-Distributed-power_storage)  >> Distributed power management LK-WM28

<p align="right">
 <a href="https://github-com.translate.goog/aeonSolutions/PCB-Prototyping-Catalogue/tree/main?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=en&_x_tr_pto=wapp">Change Language</a> <br>
Last update: 03-05-2024
</p>
<p align="right">
    partially sponsored by <br>
    <a href="https://www.seeedstudio.com/fusion.html">
       <img height="25" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/seedstudio_logo.png">
    </a>
</p>

## This Hardware Electronics is Sponsorware 💰💰💰
The optimized design files for each of the hardware electronics listed are only available to my sponsors on GitHub Sponsors.
It features many PCB optimizations such as much more energy efficiency and much less EMI  on the boards. This means, for instance, much better hardware performance and lasting battery life. 

Enjoy, and thanks for the support! ❤️

Learn more about **Sponsorware** at [https://github.com/aeonSolutions/sponsorware](https://github.com/aeonSolutions/sponsorware) 💰.

<p align="center">
    <a href="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/become_a_sponsor/aeonlabs-github-sponsorship-agreement.docx">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/want_to_become_a_sponsor.png">
    </a>
    <a href="https://github.com/sponsors/aeonSolutions">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/become_a_github_sponsor.png">
    </a>
</p>

# Distributed power management LK-WM28
This smart distributed DC power management and charging device has the purpose of charging 5V DC battery walls and power packs from the main 220V AC line at home. The innovation of this power charging device is in the ability to schedule charging to specific times during the day and night according to the price of electricity change. It can be programmed using machine learning to connect to an electricity market data source and calculate the best time to schedule battery charging according to the price variations in the electricity markets. Made to fit the LK-WM28 enclosure sold on Aliexpress ( [Buy here](https://s.click.aliexpress.com/e/_DCotQTN) ). It is a wall-mount type of installation.

<p align="center">
   <img height="300px" src="https://github.com/aeonSolutions/AeonLabs-HomeAutomation-Distributed-power_management_LK-WM28/blob/main/media/LK-WM28_PCB_FRONT.jpg">
   <img height="300px" src="https://github.com/aeonSolutions/AeonLabs-HomeAutomation-Distributed-power_management_LK-WM28/blob/main/media/LK-WM28_PCB_BACK.jpg">
   <img height="300PX" SRC="https://github.com/aeonSolutions/AeonLabs-HomeAutomation-Distributed-power_management_LK-WM28/blob/main/media/LK-WM28_ALIEXPRESS.jpg">
</p>

<p align="center">
<strong> <a href="https://aeonsolutions.github.io/sponsor/wall_mount_power_management_LK-WM28/">Interactive view of the PCB Layout</a> </strong> &nbsp;
  <strong> <a href="https://aeonsolutions.github.io/sponsor/wall_mount_power_management_LK-WM28/circuit_schematic.html">Interactive view of the circuit schematic</a> </strong> <br>
 <sup>Click to view the latest revision</sup>
</p>

### Summary of the Hardware Capabilities
- 3 USB-A for fast charging up to 30W
- With 220V AC to DC converter and Power charging scheduler to allow charging only when the electricity price is lower (during the night) using machine learning algorithms.

- With a 5.0V DC two-wire connector to allow DC charging from another source (for instance from solar panels)
- With a 5.0V DC two-wire connector to power an indoor main DC line for all 5.0V devices and electronics (smartphones, tablets, or any other)
- With individual power consumption metrics on all USB ports (voltage, current, and power )
- With the detection of an empty/full "power wall" battery pack connected to one of the 3 USB-A ports

- Display
  - 1.47" LCD TFT display

- Power Consumption
  - extreme low power consumption when in sleep mode. Only ~320nA

- Firmware update via USB-C  
  - for firmware updates/upgrades 
  - installation of Custom firmware possible ( tunning) 
  - for local troubleshooting of errors on the module and on the CANBUS network
    
You can read about this project on Hackster [here](https://www.hackster.io/mtpsilva/ultra-low-power-home-dc-electrical-system-4th-iteration-d8294a).

## Off the Grid usage (RV, Boats)
This smart distributed power management device can be installed and utilized off the grid, such as sail boats and motor homes. It can do battery charging when the AC plug is connected (this rev. max 60W) and a max 5V DC 5A solar charging to 3 USB-A ports. This means one can use those commercially available 100,000mA power banks as power walls. Or a real 5V DC power wall. Any will do as long as it runs on 5V DC and is able to connect to a USB-A Port.
 
<br>

## OEM Firmware code
The OEM version of the firmware code can be found in the folder **firmware code**.  It has by default OTA updates, meaning this smart switch device automatically updates itself when newer updated versions are made available here.  
This code uses my own ESP32 C++ class libraries to expedite the development of code for ESP32 microcontrollers. The repository is located [here](https://github.com/aeonSolutions/aeonlabs-ESP32-C-Base-Firmware-Libraries#readme) for anyone to use.

<p align="center">
 <a href="https://github.com/Domi04151309/HomeApp">
 <img height="70" src="https://raw.githubusercontent.com/Domi04151309/HomeApp/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher.webp">
 </a>
 </p>

### Home App for Android™
HomeApp is a small and easy to use smart home app with a simple framework. The goal of this application is to make remote execution of predefined features as easy and user-friendly as possible to help you get started with smart home technology.

<p align="center">
<a href="https://f-droid.org/packages/io.github.domi04151309.home">
  <img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
  alt="Get it on F-Droid"
  height="80"/>
</a>
</p>

<br>

## Compatibility

<p align="center">
 <a href"https://www.apple.com/shop/accessories/all/homekit">
<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/works_with_apple_home.png" height="50">
 </a>
<a href="https://home.google.com"> 
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/works_with_google_home.png" height="50">
 </a>
<a href="https://www.home-assistant.io">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/works_with_home_assistanr.png" height="50">
 </a>
<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/works_with_matter.png" height="50">
 </a>
<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/works_with_zigbee.jpg" height="50">
 </a>
</p>

<br>

## Parts Needed
- Buy the [LK-WM28 Enclosure 130x89x31mm  ](https://s.click.aliexpress.com/e/_DCotQTN) on AliExpress
- buy the [Smart PCB electronics (assembled)](https://www.tindie.com/stores/aeonlabs/) o Tindie.com
    
<br>
<br>

**About the sponsor** <br>
[Seeed Studio Fusion](https://www.seeedstudio.com/fusion.html) PCBA Service, offers comprehensive PCB manufacturing, prototype PCB assembly, and more. Their services cover everything from PCB fabrication, parts sourcing, and assembly, to testing,. [Seeed Co-create Program](https://www.seeedstudio.com/co-create.html) can assist you in bringing your product to market with expert guidance and business networking.

<br />
<br />

## Author

You can get in touch with me on my LinkedIn Profile:

#### Miguel Tomas

[![LinkedIn Link](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/migueltomas/)

<a href="https://stackexchange.com/users/18907312/miguel-silva"><img src="https://stackexchange.com/users/flair/18907312.png" width="208" height="58" alt="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" /></a>

<a href="https://app.userfeel.com/t/2f6cb1e0" target="_blank"><img src="https://app.userfeel.com/tester/737648/image?.png" width="257" class="no-b-lazy"></a>

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/aeonSolutions)

<br>

**Hire me** <br>
See [here](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/How-to-Hire-AeonLabs) how to hire AeonLabs.

<br>

### Be supportive of my dedication and work towards technology education and buy me a cup of coffee
The PCB design Files I provide here for anyone to use are free. If you like this Smart Device or use it, please consider buying me a cup of coffee, a slice of pizza or a book to help me study, eat and think new PCB design files.

<p align="center">
    <a href="https://www.buymeacoffee.com/migueltomas">
        <img height="35" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png">
    </a>
</p>


### Make a donation on PayPal
Make a donation on PayPal and get a TAX refund*.

<p align="center">
    <a href="http://paypal.me/mtpsilva">
        <img height="35" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/paypal_small.png">
    </a>
</p>

### Support all these open hardware projects and become a GitHub sponsor  
Did you like any of my PCB KiCad Designs? Help and Support my open work to all by becoming a GitHub sponsor.

<p align="center">
    <a href="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/become_a_sponsor/aeonlabs-github-sponsorship-agreement.docx">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/want_to_become_a_sponsor.png">
    </a>
    <a href="https://github.com/sponsors/aeonSolutions">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/become_a_github_sponsor.png">
    </a>
</p>

# 

### License

Before proceeding to download any of AeonLabs software solutions for open-source development and/or PCB hardware electronics development make sure you are choosing the right license for your project. See [AeonLabs Solutions for Open Hardware & Source Development](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development) for more information. 

