# SOC with Splunk ES

|||
| --- | --- |
| VSI: | [Splunk 1 Protecting VSI (Baselines, Alerts, Dashboards, and Queries)](/Splunk%201%20Protecting%20VSI%20(Baselines%2C%20Alerts%2C%20Dashboards%2C%20and%20Queries).md) |
| | [Splunk 2 Defend Your SOC (Attack Detection)](/Splunk%202%20Defend%20Your%20SOC%20(Attack%20Detection).md) |
| | [Splunk 3 Protecting VSI from Future Attacks (Recommendations)](/Splunk%203%20Protecting%20VSI%20from%20Future%20Attacks%20(Recommendations).md) |
| Vandalay: | [Splunk Analyzing Impact, vulnerability and drawing Baselines for alerts](/Splunk%20Analyzing%20Impact%2C%20vulnerability%20and%20drawing%20Baselines%20for%20alerts.md) |

![4](/Images/2/8.png)

## About the project

This project contains two different cases:

- The VSI case. It covers three different scenarios in detail.
- Vandalay case. It covers a similar scope as the previous case, but briefly. 

## VSI

- ## VSI's scenarios:

    1. **Protecting:** This project uses Splunk and the log history provided by the networking team to create baselines to set Alerts, Automated Reports, and a Dashboard to detect suspicious activity at the Apache and Windows servers.

    2. **Defending:**  Live attack. Using Splunk to identify targets, sources, and impact.

    3. **Lesson learned:** Design mitigation strategies to protect servers from future attacks.

- ## **The Narrative behind the VSI case**

    VSI, a company that designs virtual reality programs for business, has heard rumors that a competitor may be launching cyberattacks against them. 

    As SOC analysts, you are tasked to use Splunk to monitor potential attacks on your systems and applications. Your Networking team has provided past logs to help you develop baselines and create reports, alerts, and dashboards.

    Later, VSI experienced several cyberattacks, likely from their adversary JobeCorp. Fortunately, your SOC team had set up several monitoring solutions to help VSI quickly identify what was attacked. These monitoring solutions will also help VSI create mitigation strategies to protect the organization. Now, you will need to design mitigation strategies to protect VSI from future attacks.

    You are tasked with using your findings to suggest mitigation strategies

## Vandalay

- ## VSI's scenarios:

    1. **Analyzing the Impact of the DDOS Attack:** Determine the impact of a DDOS attack.

    2. **Are We Vulnerable?:** Report about vulnerabilities found with Nessus's data.

    3. **Drawing the Baseline:** Analyze logs from a brute-force attack and determine baselines.

- ## **The Narrative behind the Vandalay case**
    As the worldwide leader in importing and exporting, Vandalay Industries has been the target of many adversaries attempting to disrupt their online business. 

    Vandaly has experienced DDOS attacks, Brute-force attacks, and low download/upload speed. Moreover, Vandaly uses Nessus to scan for vulnerabilities in its servers. 

    As a team of Vandaly's SOC, you are required to create baselines, alerts, and reports to help protect the company.



## Topics:
- Attack Detection
- Analyzing the Impact of the attack
- Log, Metrics, Packets Analysis
- Determining Baselines and Thresholds
- Lesson Learned. Recommendations
- Alerts
- DashBoards
- Queries
- Data pulled from Nessus Vulnerability Scanner

| | |
| -- | -- |
| ![4](/Images/3/4.png) | ![4](/Images/2/9.png) |


