![BoTech Logo](https://assets.botech.dev/Logos/BoTechLogoCompleteWithSlogan.png)

## Hi there 👋

## 🛤️ Roadmap for 12.2025-12.2026
```mermaid
---
config:
  theme: redux
---
flowchart TB
  n1["`**🟢BoTech.HttpClientHelper (1)**`"] --> n2["`**🟠BoTech.UI.Forms (2)**`"]
  n2 --> n3["`**🟢BoTech.XmlParser (2.1)**`"]
  n2 --> n4["`**🟡BoTech.ApiClient.Base (3)**`"]
  n2 --> n5["`**🔵Support BoTech.ApiClient.Base in BoTech.UI.Forms (2.2)**`"]
  n4 --> n6["`**🟡BoTech.SharpStudio (4)** add designer for BoTech.UI.Forms`"]
  n6 --> n7["`**🟡BoTech.Dev.Api (5)**`"]
  n7 --> n8["`**🟡BoTech.Dev.Api.Client (5.1)**`"]
  n7 --> n9["`**🔵BoTech.Dev (5.3)** implement webpage`"]
  n7 --> n10["`**🔵BoTech.Dev.Account (5.2)** implement login system frontend`"]
  n10 --> n11["`**🟠BoTech.Update (6)** implement generic application updater for c# apps.`"]
  n11 --> n12["`**🔵BoTech.Dev.Update.Api (6.1)** implement backend for updater`"]
  n11 --> n13["`**🔵Support BoTech.Update in BoTech.SharpStudio (6.2)**`"]
  n11 --> n14["`**🟡 Finish BoTech.SharpStudio (6.3)**`"]

  n1@{ shape: rounded}
  n2@{ shape: rounded}
  n3@{ shape: rounded}
  n4@{ shape: rounded}
  n5@{ shape: rounded}
  n6@{ shape: rounded}
  n7@{ shape: rounded}
  n8@{ shape: rounded}
  n9@{ shape: rounded}
  n10@{ shape: rounded}
  n11@{ shape: rounded}
  n12@{ shape: rounded}
  n13@{ shape: rounded}
  n14@{ shape: rounded}
  style n1 stroke:#00C853
  style n2 stroke:#FF6D00
  style n3 stroke:#00C853
  style n4 stroke:#FFD600
  style n5 stroke:#2962FF
  style n6 stroke:#FFD600
  style n7 stroke:#FFD600
  style n8 stroke:#FFD600
  style n9 stroke:#2962FF
  style n10 stroke:#2962FF
  style n11 stroke:#FF6D00
  style n12 stroke:#2962FF
  style n13 stroke:#2962FF
  style n14 stroke:#FFD600
```


## Chart Legend

```mermaid
---
config:
  theme: redux
---
flowchart TB
  backlog["`**🔵Backlog** => Not started implementing`"]
  done["`**🟢Finished** => at least v1.1 has been published or all features are implemented`"] 
  inProgress["`**🟡In Progress (parts implemented)**`"]
  reimplementation["`**🟠Reimplementation and in progress** => The old implementation can no longer be integrated or is outdated`"] 
  notPlanned["`**🔴Not Planned**`"]
  devPaused["`**🟣Developemnt Paused**`"]

  backlog@{ shape: rounded}
  done@{ shape: rounded}
  inProgress@{ shape: rounded}
  reimplementation@{ shape: rounded}
  notPlanned@{ shape: rounded}
  devPaused@{ shape: rounded}
  style backlog stroke:#2962FF
  style done stroke:#00C853
  style inProgress stroke:#FFD600
  style reimplementation stroke:#FF6D00
  style notPlanned stroke:#D50000
  style devPaused stroke:#AA00FF
```

### About me
+ I am currently in my second semester studying Applied Computer Science at the University of Duisburg-Essen.
+ When I have time, I work on various (see diagram) projects in my free time.
+ I currently work as a software developer (working student) at Benteler Steel/Tube

### Get in Contact
+ Mail: [support@botech.dev](mailto:support@botech.dev)
+ Or just open a ticket (issue) in one of the repos


