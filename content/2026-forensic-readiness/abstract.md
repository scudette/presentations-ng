---
draft: true
---

# Forensic Readiness through endpoint agents

Digital Forensics has become a standard part of the incident response
process. Most DFIR teams now routines deploy agent based triage
software to collect forensic evidence.

Ultimately, the purpose of DFIR is to answer critical questions about
the incident - such as what was the initial compromise vector, what
information was accessed and how long was the dwell time before the
adversaries were evicted.

Forensic capable agents, such as Velociraptor, answer these questions
by analysing digital forensic information sources that are found on
the endpoint.

However, most digital forensic artifacts are co-incidental to the
incident itself. These sources were typically never designed to
provide the type of information needed in a DFIR investigation.

This talk will discuss the different options for actively assisting
the DFIR process, by proactively increasing forensic readiness. This
approach ranges from simply enhancing logging and auditing in the
standard OS build, to actively monitoring events on the endpoint. As
an example, we show the different approach with the Velociraptor DFIR
agent.
