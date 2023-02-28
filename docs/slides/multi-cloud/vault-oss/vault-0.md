name: vault-title-slide
class: title, shelf, no-footer, fullbleed
background-image: url(https://hashicorp.github.io/field-workshops-assets/assets/bkgs/HashiCorp-Title-bkg.jpeg)
count: false

# Vault Workshop
## Modern Security with Vault for any Cloud

![:scale 15%](https://hashicorp.github.io/field-workshops-assets/assets/logos/logo_vault.png)

???
This workshop introduces students to Vault.

It is cloud agnostic.

---
layout: true

.footer[
- Copyright © 2023 HashiCorp
- ![:scale 100%](https://hashicorp.github.io/field-workshops-assets/assets/logos/HashiCorp_Icon_Black.svg)
]

---
name: Link-to-Slide-Deck
# The Slide Deck
<br><br>
### Follow along on your own computer at this link:

https://rontdz.github.io/field-workshops-vault/slides/multi-cloud/vault-oss/index.html

???

The link to this slide deck

---
name: Introductions
# Introductions

<div style="float: left; width: 50%;">
.center[![:scale 50%](images/ron-dp.jpg)]
<ul>
<li>Ron Teo</li>
<li>Solution Architecture Specialist</li>
<li>ron.teo@hashicorp.com</li>
</ul>
</div>
<div style="float: right; width: 50%;">
.center[![:scale 45%](images/zh-dp.png)]
<ul>
<li>Zhi Hao Pang</li>
<li>Partner Solution Engineer</li>
<li>zhihao.pang@hashicorp.com</li>
</ul>
</div>


???
* Use this slide to introduce yourself, give a little bit of your background story, then go around the room and have all your participants introduce themselves.

* The favorite text editor question is a good ice breaker, but perhaps more importantly it gives you an immediate gauge of how technical your users are.  

---
name: Table-of-Contents
# Table of Contents

1. HashiCorp Vault Overview
1. Interacting with Vault
1. Running a Production Server
1. Vault Secrets Engines
1. Vault Authentication Methods
1. Vault Policies
1. Hands-on Labs - Vault Basics 
1. Dynamic Database Secrets (w/ Labs)
1. Encryption as a Service (w/ Labs)

???
The table of contents for the workshop

---
name: instruqt-tracks
# Lab Environment & Conduct
* This workshop uses [Instruqt](https://instruqt.com) for hands-on labs.
* Instruqt labs are run in "tracks" that are divided into "challenges".
* The lab environment will still be available after this workshop and you can always re-attempt them.
* We will take a pause at the end of every chapter for a short Q&A.
* We will use an online poll to keep track of our progress.