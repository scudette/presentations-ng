---
title: "Cybersecurity"
subtitle: Why choose a Cybersecurity career?
author: Mike Cohen
author_role: Digital Paleontologist
author_company: Rapid7
outputs: ["Reveal", "HTML"]
reveal_hugo:
  custom_theme: "themes/swiss-executive.css"
  margin: 0.2
published: 2026-10-02
---

{{% title_slide %}}

---

## What this talk is about?

* I have been in the cybersecurity field over 25 years
* The field has changed and grown over time
* It is a challenging field with important work!

<div style="padding-top: 50px;">

* You will find this talk on

    * https://present.velocidex.com

</div>

---

## What I hope you gain from this talk

* This is a quick tour of my experience in Cybersecurity.
* I hope this will spark your interest to pursue a career in Cybersecurity!
* No two careers are the same!
    * Forge your own path.
* No one knows where they will end up at the start of the journey
    * Enjoy the ride!

---

## Australian Signals Direcotorate (ASD)

* Where I started! Graduate intake program (circa 2001).
* Responsible for whole of government information security posture
* Really a great place to start your carreer - so much to learn!
* Very impactful and important work!

---

## Security policy and guidance

* ASD helps set Government policy.
   * Helps departments implement secure systems.
   * Advises, assists and provides guidance.
   * [ASD Essential 8 Maturity Model](https://www.cyber.gov.au/resources-business-and-government/essential-cybersecurity/essential-eight)

* ASD also has an incident response and reporting function.
   * [Report and
     coordinate](https://www.cyber.gov.au/report-and-recover/report)
     various law enforcement and government agencies.

---

## Compliance and certifications

* 20 Years ago was the wild west!
   * Outsourcing was all the rage!

* Today we have extensive frameworks:
   * [GDPR](https://gdpr.eu/) - enforces privacy guards with penalties!!!
   * [PCI](https://www.pcisecuritystandards.org/) - Required for CC data!
   * [HIPAA](https://www.cdc.gov/phlp/php/resources/health-insurance-portability-and-accountability-act-of-1996-hipaa.html) - Required for managing health data
   * [IRAP](https://www.cyber.gov.au/irap) - Certification for Aus Gov
* Many professional auditors and consultants to enforce compliance.
   * Is it perfect? No...

---

## Security auditing of application code.

* Back in early 2000's:
   * Everyone was speeding to deploy a web presence
   * Security was an afterthought in many cases
   * Low skill of developers
   * Languages were not robust enough - too easy to do the wrong thing.

* Really fun to break applications!

---

## Software vulnerabilities

Common vulnerabilities include [SQL Injection](https://pentest-tools.com/blog/sql-injection-attacks)
*  This vulnerability leads to complete server take over

![](sql_injection_code.png)


---

## Impact of software vulnerability
### In early 2000s

* When a security vulnerability was exploited:
   * It was usually a teenager or student just playing around
   * Often they tried to embarrass the agency or government department
   * Media jumped on the "incompetence of government"

* Generally not a huge impact
   * backup, restore, rebuild!

---


## Today: Not messing around

<img style="max-height: 60vh; margin-left: 0vw; margin-bottom: -20px;" src="ransomware_splashscreen.png" />

---

<!-- .slide: class="full_screen_diagram" -->
## Ransomware Negotiators

![](ransomware_negotiator.png)

https://www.darkreading.com/cyberattacks-data-breaches/meet-the-ransomware-negotiators

---

<!-- .slide: class="full_screen_diagram" -->
## Impact of software vulnerability today

* Such a vulnerability **will** result in a ransomware attack.

![](ransomware_payments.png)

https://www.theguardian.com/technology/2023/may/10/ransomware-payments-nearly-double-in-one-year

---

<!-- .slide: class="full_screen_diagram" -->
## How hard is it to exploit today?
### AI makes it much easier to exploit

![](ai-hack.png)

https://www.abc.net.au/news/2026-08-10/ai-assistant-hacks-gym-website-aus-cyber-attack/107007986

---


## How hard is it to exploit today?
### Advanced models have autonomy and initiative

![](openai-hack.png)

https://www.abc.net.au/news/2026-08-19/openai-slows-development-pauses-testing-after-hugging-face-hack/107053332

---

## AI Powered security reviews
### AI makes it much easier to audit large quantities of code

![](velociraptor-vulns.png)

---

## Law enforcement

* The field of Digital Forensics was just getting started in early
  2000's
* Today most cases involve an element of Digital Forensics:
    * Computers
    * Phones
    * Cars
    * Watches and health data
    * Surveillance
    * Game consoles

---

## A hacking case from 2006


<a href="nat_060322internetarrest.pdf">

![](../dfrws_apac_2024/nat_060322internetarrest.svg)

<a>

---

## A hacking case...


<a href="nat_060322internetarrest.pdf">

![](../dfrws_apac_2024/nat_060322internetarrest2.svg)

<a>

---

## A hacking case...

* A complex case consisting of
  * Manual investigation of multiple server drives.
    * Compromises over a couple of years

  * Images shipped from multiple countries.

* Arrest made of 22yo University Student
* Outcome was no conviction recorded
  * let off with a warning: motive was curiosity and desire to learn computer security.

* Really good exercise for all involved!
  * Best practice evidence collection, chain of custody etc!

---

## Law Enforcement challenges

* Modern criminals are highly aware of information security!
* Software has gotten a lot more secure
* Sometimes new and innovative solutions are required
* Legislation to provide access is sometimes at odds with privacy
    * End to End Encryption vs Law enforcement access
    * US [Fifth amendment](https://constitution.congress.gov/constitution/amendment-5/) vs Australia's [Section 3LA](https://www5.austlii.edu.au/au/legis/cth/consol_act/ca191482/s3la.html)

---

## Operation Ironside

![Operation Ironside](operation_ironside.png)

---

## Corporate Information Security

* Companies operate business critical information systems.
* An information security incident can destroy companies in an instant!
    * Ransomware
    * Insider threats
    * IP leaks
    * Privacy breaches (PII) can result in fines and loss of confidence
    * Business Email Compromise (BEC)

---

## Business Email Compromise (BEC)

* [BEC](https://www.cyber.gov.au/threats/types-threats/business-email-compromise) is very common, and extremely hard to combat.
* Can affect companies big and small.

* Also affecting
   * Property transactions
   * Large transfers etc

---

## Inoteq vs Mobius Group

<a href="https://www.abc.net.au/news/2025-01-16/court-orders-inoteq-to-pay-190k-after-fraudulent-invoice/104783454">

![](innotec_1.png)

</a>

https://www.abc.net.au/news/2025-01-16/court-orders-inoteq-to-pay-190k-after-fraudulent-invoice/104783454

---

## Inoteq vs Mobius Group

<a href="https://www.abc.net.au/news/2025-01-16/court-orders-inoteq-to-pay-190k-after-fraudulent-invoice/104783454">

![](innotec_2.png)

</a>

---

## Business Email Compromise (BEC)

![](bec_losses.png)

https://www.itnews.com.au/news/australian-businesses-lose-227-million-to-bec-like-scams-582162

---

<!-- .slide: class="full_screen_diagram" -->

<a href="https://www.smartcompany.com.au/technology/business-email-hacks-undetected-11-days-average/">

![BEC](bec.png)

</a>

https://www.smartcompany.com.au/technology/business-email-hacks-undetected-11-days-average/

---

<!-- .slide: class="content" -->

## Incident Response - Blue team

* When a security breach occurs - Time is of the essence!

* Attacks typically follow the [Cyber Kill Chain](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html):
   * Installation or compromise
   * Command and Control (C2)
   * Actions on objectives - i.e. Data exfiltration or encryption.

* Dwell time is the time between initial compromise and objective.

---

## Dwell time is getting shorter

![](dwell_time.png)

<div class="ref">

https://news.sophos.com/en-us/2023/08/23/active-adversary-for-tech-leaders/

</div>

---

## Security Operation Center (SOC)


> A SOC is a centralized function or team responsible for improving an organization’s cybersecurity posture and preventing, detecting, and responding to threats.
{cite="https://www.microsoft.com/en-us/security/business/security-101/what-is-a-security-operations-center-soc" caption="Microsoft Security 101"}

---

## Security Operation Center (SOC)

![](soc.png)
{cite="https://www.ncsc.gov.uk/collection/building-a-security-operations-centre" caption="Building a Security Operations Center"}

---

### What is Detection Engineering?

![](detection_engineering.png)
{cite="https://www.crowdstrike.com/en-us/cybersecurity-101/next-gen-siem/detection-engineering/" caption="Introduction to detection engineering"}

---

## What is Detection Engineering?

* Requires low level understanding of attack cycles
* Combines many fields:
    * Digital Forensics
    * Writing detection rules
    * Replicating attack methods
    * Tuning and refining

---

## Security auditing: Red teams

* Perform simulated attacks against an organization
    * Test forensic readiness
    * Test application security
    * Test Incident Response

* Reporting security weaknesses to C level execs!

---

## Security auditing: Red teams

![](red_team.png)
{cite="https://rapid7.com/fundamentals/what-is-a-red-team/"}

---

## Software development
### Security industry

* All software developers must have a strong grounding in information
  security!

* Developing security specific software needs a working knowledge of:
    * Detection Engineering
    * Low level OS internals - gather telemetry
    * High performance computing - scaling up!
    * Large Data analytics
    * Cloud technologies

---

## Software development
### Security industry

* Many companies require
   * Custom solutions
   * Integration with existing systems
   * Streamline SOC operations
   * Enhance logging and auditing from custom systems
   * Tuning and automating

* AI Awareness and training
   * AI is getting good at writing code
   * But security is an afterthought!

---

## What about Vibe coding?

![](vibe-coding-risks.png)
{cite="https://theconversation.com/vibe-coding-is-fun-and-easy-but-theres-a-major-catch-287693"}

---

## Cybersecurity as a career

* Information Security is a huge field!
   * Over the years it has evolved
   * There is something for everyone!
   * In your career you will likely move between specializations.
   * Every day is a new challenge

* Bootstrap your career anywhere!
   * Help desk
   * Government graduate intake programs.
   * Always be the person in the room who is least experienced!

---

### Always be learning!

![](abl.jpg)
