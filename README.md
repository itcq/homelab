![homelab](https://user-images.githubusercontent.com/49261788/143670404-bae2d2e9-7305-4bac-8a93-26317b14649e.png)



# homelab
The Ultimate Home Lab Guide from the I.T. Career Questions Community

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-home-labs">About HOME LABS</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT HOME LABS -->
## About HOME LABS

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This will act as an up-to-date guide to building your own personal home lab.  This guide will be developed over time and with the contribution of the community.

<p align="right">(<a href="#top">back to top</a>)</p>

<!--  What Kind of Home Lab do I need? -->
## What Kind of Home Lab do I need?

This will all depend on your level of experience and the avenue of I.T. you are looking to pursue.  As you are begining your career or just starting to learn about I.T. in general we can build out very simple labs by virtualizing different operating systems, even virtualizing network equipment like routers and switches to keep things as simple and as minimal cost as possible.  You can also obtain physical equipment for your home lab as well as some people may prefer working with the physical hardware in front of them.

In this guide our primary focus will be Entry Level Home Labs that you can build to start building fundamental knowledge and experience in some of the most common tools and technologies used every day in real world I.T. positions.

If you are just starting out in the world of infomration technology this guide will provide the resources and information you will need to pursue an entry level role in I.T. and/or gear your hands-on experience towards a specific area of technology that you are interested in.

<p align="right">(<a href="#top">back to top</a>)</p>

## Types of Home Labs

The following list are the most common types of home labs that are built.
We will mostly be working with Entry Level Home Labs in this guide and will will link to external resources that can help highlight more in depth walkthroughs building more advanced labs.

``` 
**the difficulty level and/or resources required increase in order of descension:**
1. Entry Level Home Labs
2. Systems Administrator Home Labs
3. Network Administrator Home Labs
4. Cybersecurity/Penetration Testing Home Labs
``` 
<p align="right">(<a href="#top">back to top</a>)</p>


## Home Lab Requirements

Depending on your budget and available resources you will need to determine what is most appropriate to your situation.

### Networking Home Lab Requirements:

* Working Router(Models: )
* Working Switch(Models: )
* USB Console Cable(USB Preferred)
* Computer(Laptop or Desktop: Running any modern operating system - Windows/Linux/Mac)
  * Anything from the last 5-8 years should be more than sufficient
  * Multi-Core Processor Preffered
  * At least 4GB of RAM(8GB+ Preferred)
  * At least 40GB+ of HDD Space
* Multiple computers or capability of virtualizing multiple computers would be highly preferred, but not required.
  
``` 
**the difficulty level and/or resources required increase in order of descension:**
1. Entry Level Home Labs
2. Systems Administrator Home Labs
3. Network Administrator Home Labs
4. Cybersecurity/Penetration Testing Home Labs
``` 
<p align="right">(<a href="#top">back to top</a>)</p>

### Every Other Home Lab Requirements:

It is important to know and understand the minimal requirements of the software and applications you will be utilizing to verify the equipment you will be using will have sufficient resources to provide an optimal experience.

You can find the bare minimum requirements for some of the more popular operating systems listed below so you can get an idea:

| OS:      | Windows 11 | Windows Server 2022 | Ubuntu(Linux) |
| ----------- | ----------- | ----------- | ----------- |
| Processor:      | 1 gigahertz (GHz) or faster with two or more cores on a compatible 64-bit processor or system on a chip (SoC).    | 1.4 GHz 64-bit processor        | 2 GHz dual core processor |
| RAM:   | 4 gigabytes (GB) or greater       | 512 MB (2 GB for Server with Desktop Experience installation option)       | 4 GB RAM |
| Hard Drive:   | 64 GB       | Minimum: 32 GB       | 25 GB |


* Working Router(Models: )
* Working Switch(Models: )
* USB Console Cable(USB Preferred)
* Computer(Laptop or Desktop: Running any modern operating system - Windows/Linux/Mac)
  * Anything from the last 5-8 years should be more than sufficient
  * Multi-Core Processor Preffered
  * At least 4GB of RAM(8GB+ Preferred)
  * At least 40GB+ of HDD Space

  
``` 
**the difficulty level and/or resources required increase in order of descension:**
1. Entry Level Home Labs
2. Systems Administrator Home Labs
3. Network Administrator Home Labs
4. Cybersecurity/Penetration Testing Home Labs
``` 
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started with a Physical Lab
---
### <p align="center">`Before we begin discussing the physical lab portion, Virtualization and Cloud Providers are the recommended resources to utilize when creating a home lab.`</p>
---
Depending on your budget and/or ability to obtain the physical hardware(servers, routers, switches, etc..) it will almost always be cheaper to virtualize a lab environment from your existing computer or to utilize the free resources that Amazon's Web Services(AWS) or Microsoft Azure are able to provide.

> AWS Free Tier: https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all

> Microsoft Azure Free Tier: https://azure.microsoft.com/en-us/free/

You can obtain the physical hardware and equipment through eBay, Craigslist, Facebook, LinkedIn, and More(Contribute to this section?)

* eBay:
  * Servers:
  * Routers
  * Switches: 
* Craigslist: https://craigslist.com
  * Craigslist is location based
* Facebook Groups
  * Facebook Groups are location based
* LinkedIn
  * It's possible you can get lucky through creating valuable connections you can start to obtain older/cheaper equipment.
* Meet Ups
  * It is not advised going to Meet Ups purely to obtain free or cheap equipment but this may be an avenue as well.

``` 
Please Note: When you acquire physical hardware/equipment it will be important to follow specific
guides and/or setup tutorials in relation to the specific model of equipment you obtain.

For instance booting into the BIOS from different manufacturers(HP, Dell, Lenovo, ETC..) may differ depending on the model.
This is important to note when installing Operating Systems, Software, or other Firmware and miscellanious
upgrades that may require booting from different media, like USBs or CD/DVD's, and/or booting from the network.

When completing initial confirgurations or troubleshooting issues with specific hardware you will want
to include in your Google searches: the "*issue*" plus "*model name/number*"

ie: "How to Boot to BIOS on a Dell PowerEdge R720" 

``` 

<p align="right">(<a href="#top">back to top</a>)</p>

### When Purchasing Used Equipment

Verify that everything is working or if the piece of equipment is being sold as is.

You will often find you can save a significant amount of money from buying used routers and switches that have broken ports on them.

You may also find that you can save money on servers/computers from purchasing them with no hard drives or RAM.
*please *note: Please be sure to look up the price of hard drives and RAM for the specific models of equipment you are purchasing, sometimes you will find that hard drives and even RAM for older equipment can still be fairly costly to obtain.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED VIRTUAL LAB -->
## Getting Started with a Virtual Lab




<!-- Prerequisites -->
## Prerequisites




<p align="right">(<a href="#top">back to top</a>)</p>


