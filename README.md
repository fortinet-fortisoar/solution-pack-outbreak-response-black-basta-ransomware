# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

A new alert from CISA, the FBI, the Department of Health and Human Services (HHS), and the Multi-State Information Sharing and Analysis Center (MS-ISAC) reveals that Black Basta affiliates have attacked 12 of the 16 critical infrastructure sectors, including healthcare organizations accelerating its activities. 

 The **Outbreak Response - Black Basta Ransomware** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.1.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/black-basta-ransomware) contains information about the outbreak alert **Outbreak Response - Black Basta Ransomware**. 

## Background: 

Black Basta is a type of ransomware-as-a-service (RaaS) that was first discovered in April 2022. Since then, its affiliates have targeted numerous businesses and critical infrastructure in North America, Europe, and Australia. By May 2024, Black Basta has impacted over 500 organizations worldwide. In this Ransomware-as-a-Service (RaaS) model, the developers offer a service such as ransomware, an infrastructure for payment processing and ransom negotiation, and technical support to its affiliates.

Black Basta has been seen to use techniques such as phishing and exploiting public facing applications to gain initial access. Previously, it was seen to exploit the PrintNightmare (CVE-2021-34527), ZeroLogon (CVE-2020-1472) and Follina (CVE-2022-30190) vulnerabilities for priviledge escalation. 

## Announced: 

Black Basta Ransomware is considered to be behind a hack at a private healthcare provider Ascension impacting
systems used to access health records system and various systems utilized to order certain tests, procedures and
medications. 

## Latest Developments: 

May 11, 2024: Black Basta Ransomware is considered to be behind a hack at a private healthcare provider Ascension impacting Systems used to access health records system and various systems utilized to order certain tests, procedures and medications.
https://about.ascension.org/cybersecurity-event

May 10, 2024: The FBI and the Cybersecurity and Infrastructure Security Agency (CISA) warned that the Black Basta gang is targeting critical infrastructure in the US.
https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-131a

February 2024: Black Basta affiliates began exploiting ConnectWise vulnerability CVE-2024-1709 for intial access.

Feb 28, 2024: FortiGuard Labs released an outbreak alert on ConnectWise vulnerability CVE-2024-1709, which has been exploited by Black Basta recently.
https://www.fortiguard.com/outbreak-alert/connectwise-screenconnect-attack

June 2023: Fortinet released a detailed blog on Blackbasta Ransomware and how Antivirus Service and FortiEDR detects and blocks the ransomware.
https://www.fortinet.com/blog/threat-research/ransomware-roundup-black-basta 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|