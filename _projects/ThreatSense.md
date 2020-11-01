---
name: ThreatSense
tools: [Python, Streamlit, API Technology]
image: https://myventurepad.com/wp-content/uploads/2018/08/rest-api.jpg
description: A web application that provides continuous data about potential threats actors, including indicators of compromise, giving security professionals an easily digestible, real-time look at known threats
---

# ThreatSense: Cyber Intelligence Tool

## Structure
API services offered by VirusTotal were integrated into this web application. Public Endpoints provided by the [VirusTotal APIs](https://developers.virustotal.com/v3.0/reference#public-vs-premium-api) are freely accessible to all registered users. Some features of the public API include:
* 4 requests per minute.
* Usable in non-commercial products.

## App Components
ThreatSense provides users the following services:
1. Kaspersky's own real-time threatmap.
2. identification of threats pertaining to -
    - Files, 
    - E-mails, 
    - IP Addressess and  
    - URLs
3. Map showing origin of an IP Address

 
## Built With
* [Streamlit](https://www.streamlit.io/) - Open-source Python library that makes it easy to build beautiful custom web-apps for machine learning and data science.
* [VirusTotal](https://developers.virustotal.com/v3.0/reference#public-vs-premium-api) - VirusTotal's aggregates data from many different antivirus engines, website scanners, file and URL analysis tools.
* [PyDeck](https://deckgl.readthedocs.io/en/latest/installation.html) -  The pydeck library is a set of Python bindings for making spatial visualizations.

<p class="text-center">
{% include elements/button.html link="https://github.com/NuhMohammed/ThreatSense" text="View Code" %}
</p>