---
layout: guide
title: Case studies
description: A range of case study designs for bitcoin applications.
nav_order: 5
has_children: true
permalink: /guide/case-studies/
main_classes: -no-top-padding
image: /assets/images/guide/private-key-management/case-studies/page-case-studies.jpg
---

<!--

Editor's notes

-->

{% include picture.html
   image = "/assets/images/guide/case-studies/case-studies.jpg"
   retina = "/assets/images/guide/case-studies/case-studies@2x.jpg"
   mobile = "/assets/images/guide/case-studies/case-studies-mobile.jpg"
   mobileRetina = "/assets/images/guide/case-studies/case-studies-mobile@2x.jpg"
   alt-text = "Case studies header illustration"
   width = 1600
   height = 600
   layout = "full-width"
%}

# Case studies

A look at some hypothetical use case categories and what might be suitable approaches for private key management schemes for each of them.

Before deciding on a private key management scheme it’s essential to have a good idea of what use case and target audience your product has. Let’s look at some hypothetical use case categories and what might be suitable approaches.

---

**[Cloud backup]({{ '/guide/case-studies/cloud-backup/' | relative_url }})**

Explores a simple mobile wallet design that relies on automated cloud backup to store private keys. A common use case for this technique are wallets for daily spending on-the-go.

---

**[Multisig wallet]({{ '/guide/case-studies/multisig-wallet/' | relative_url }})**

Shows the user flow of setting up a 2-of-3 multsig wallet in a mobile application.

---

**[Upgradeable wallet]({{ '/guide/case-studies/upgradeable-wallet/' | relative_url }})**

A mobile experience that starts users off with a simple cloud backup solution and allows them to upgrade the security model progressively as their needs change.

---

**[Shared account]({{ '/guide/case-studies/shared-account/' | relative_url }})**

An onboarding experience for a mobile wallet shared by a couple who want to access and manage the funds together.