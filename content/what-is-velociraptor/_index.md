---
title: "Velociraptor: Digging Deeper"
subtitle: Introducing Velociraptor
author: Mike Cohen
author_role: Digital Paleontologist
author_company: Rapid7
outputs: ["Reveal", "HTML"]
reveal_hugo:
  custom_theme: "themes/swiss-executive.css"
  margin: 0.2

---

{{% title_slide %}}

---

## What is Velociraptor?
### A DFIR tool to handle every stage of the attack timeline

![](attack_timeline.svg)

---

## How can I use Velociraptor?
### Flexible tool to handle every use case

![](use_cases.svg)

---

## Scalable, fast, accurate

* Support Linux, Windows, MacOS, FreeBSD …
* Server simply collects the results of queries - clients do all the
  heavy lifting.
* Client memory and CPU usage is controlled via throttling and active
  cancellations.
* Server is optimized for speed and scalability
* Concurrency control ensures stability
* Bandwidth limits ensure network stability
* Single or multi-server modes (20k EP/server).

---

## Interactively investigate clients

Digital forensic plugins turn VQL into a high quality DFIR tool

{{% browser
  src="/modules/gui_tour/vfs_view.png" %}}

---

## Velociraptor Artifacts
### Artifacts encode VQL into user sharable code snippets

{{% browser
  src="/modules/artifacts_introduction/artifacts.png" %}}

---

## Hunts - Collecting at scale
### Collecting artifacts at scale from multiple endpoints

{{% browser
  src="/modules/secure_shell/select_hunt_artifacts.png" %}}

---

## Postprocessing using Notebooks
### Collaborative shared VQL execution environments

{{% browser
 src="/modules/secure_shell/postprocess_hunt.png" %}}

---

## Triaging Using Sigma

* Endpoint tools can directly evaluate Sigma rules on the event logs

![](velociraptor_sigma_flow.png)

---

##  Collecting the sigma artifact

{{% browser
 src="collecting_sigma_rules.png" %}}

---

## Triaging an endpoint

{{% browser
  src="query_logs.png" %}}

---

## Stacking rules by title

{{% browser
 src="stacking_a_column.png" %}}

---


## Viewing the stacking stats

{{% browser
 src="viewing_column_stack.png" %}}

---

## Viewing common rows

{{% browser
 src="viewing_common_rows.png" %}}

---

## Detection vs. Forensics

* VQL Sigma rules bridge detection with forensics.
* Forensics: `What happened here?`
    * Recover all the information - relevant or not
    * Get a full picture.

* Detection: `What bad things happened here?`
    * Take the forensic information and rapidly zero in on obvious bad
      signals.
    * Not designed to be exhaustive! Triage oriented

* Complimentary capabilities

---

## Real Time Sigma alerting
### VQL is fully asynchronous - real time queries.

![](client_events_arch.png)
{style="height: 50vh;"}

---

## Real Time Sigma alerting

### Configuring Velociraptor's client monitoring

{{% browser
 src="configuring_client_monitoring.png" %}}

---

## Real Time Sigma alerting

### Configuring Velociraptor's client monitoring

{{% browser
  src="configuring_client_monitoring_logs.png" %}}


---

## Live detection with Sigma

{{% browser
 src="live_sigma_detection.png" %}}


---

## Administration and automation

* All server administration tasks can be automated with VQL artifacts
* API access available for external automation
* Automatic upload of data to Elastic/Slack/Discord
* Open ended architecture enables novel use cases.

---

## The Velociraptor Ecosystem

![](ecosystem.svg)

---

{{% conclusions %}}
