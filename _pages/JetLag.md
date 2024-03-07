---
layout: archive
title: "JetLag, the Lagrangian jet tracking algorithm"
permalink: /JetLag/
author_profile: true
---

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}


![](../images/logo2.png)

**The JetLag data sets and documentation will be released shortly**<br>
Sign up for the [JetLag mailing list](https://web.lists.fas.harvard.edu/mailman/lists/jetlag.lists.fas.harvard.edu/) to be notified.<br>

---

**What is JetLag?**<br>

JetLag is a jet tracking algorithm in development, in collaboration with [Dr. Jezabel Curbelo](https://web.mat.upc.edu/jezabel.curbelo/) at Universitat Politècnica de Catalunya with the support of [Centre de Recerca Matemàtica](https://www.crm.cat/).<br>
JetLag relies on Lagrangian descriptors of the general circulation, hence the name.

---

**Why JetLag?**<br>

Many jet tracking algorithms have been developed in the past, but significant limitations still exist:

* Existing algorithms define the jets in the Eulerian framework (instantaneous or time-averaged meteorological fields) and are therefore unable to distinguish the true axis of the jet from underlying waves;

  _JetLag defines jets as Lagrangian coherent structures to account for their spatial <em>and</em> temporal coherence_

* Most algorithms rely on a variety of empirical, climatological parameters to detect jet features (e.g. latitude and wind magnitude thresholds). Such algorithms are by design tailored to the current state of the climate and cannot be used to analyze other climate states;

  _JetLag's 2 parameters are rooted in wave dynamics, independent of the state of the climate_

* The majority of algorithms are tailored to track either the subtropical jet or the polar front jet, but not both;

  _JetLag identifies both jet types with the same method_

---

**How does JetLag work?**<br>

The algorithm uses a Lagrangian descriptor of the general circulation, the 'M function', which is defined at any location (x,y,z,t) as the length of the Lagrangian parcel trajectory initiated at (x,y,z,t) and integrated over a chosen time interval {t-$\tau$ ; t+$\tau$}. The only parameter used in JetLag is the length of that time interval, $\tau$, which can be determined objectively based on the scales of interest.

The M function highlights Lagrangian coherent structures --organizing features of the atmospheric circulation that correspond to maxima in atmospheric transport and that are invariant over the chosen integration interval. JetLag relies on these features to locate jets that are coherent in space and in time, effectively separating jets from underlying waves.

---

**What will JetLag provide?**<br>

We're still working on it, but we expect to release a beta product based on ERA5 in Summer 2024.

Other products will be released over time, including products for CMIP6 model runs.<br>
Contact us if you are interested in a product that is not available.<br>

---

**Can I get involved?**<br>

We'd love to hear your thoughts. You can reach out to us via the mailing list (once you've subscribed, email: jetlag-owner \[replace with at symbol\] lists (dot) fas (dot) harvard (dot) edu) or directly via my professional email (lrivoire \[replace with at symbol\] mit (dot) edu). You can request that JetLag be applied to a model output or reanalysis or your choosing –we want JetLag to be useful to your specific purposes! Subject to computing constraints and demand.
