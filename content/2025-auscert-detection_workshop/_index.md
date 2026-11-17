---
title: "Detection Engineering"
subtitle: The art and science of detecting intrusions!
author: Mike Cohen
author_role: Digital Paleontologist
author_company: Rapid7
outputs: ["Reveal", "HTML"]
reveal_hugo:
  custom_theme: "themes/swiss-executive.css"
  margin: 0.2
published: 2025-05-02

---

{{% title_slide %}}

---

## Overview

* This workshop will discuss Detection Engineering with Velociraptor
* We will use Velociraptor as an example platform
   * Not everything we show will be possible on all platforms
   * Nevertheless it is useful to see what is possible!
   * Think about the additional detections that can be implemented
     with better capabilities!
* We also introduce the Sigma detection "standard"

---

## Create a local server

* Create a local server on your windows system.
* We will use this server's notebook feature to learn about windows artifacts
* Run Velociraptor on your machine
    * Download Velociraptor from the
      [Download](https://docs.velociraptor.app/downloads/) page (`.msi`
      or `.exe`)

```bash
velociraptor-v0.74.2-windows-amd64.exe gui
```

---

The "gui" command creates an instant temporary server/client with self
  signed SSL and a hard coded admin/password.

![](/modules/gui_tour/velociraptor-gui.png)

---

## Your Velociraptor is ready to use!

{{% browser
  src="/modules/gui_tour/GUI.png" %}}

---

{{% include-page "introduction.md" %}}

---

{{% include-page "sigma.md" %}}

---

{{% include-page "windows_event_logs.md" %}}

---

{{% include-page "live_detection.md" %}}

---

{{% include-page "event_tracing.md" %}}

---

{{% include-page "forensic_detection.md" %}}
