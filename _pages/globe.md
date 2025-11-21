---
layout: single
title: "JetLag Globe"
permalink: /globe/
---

<html>
<head>
<style>
.globe-wrap {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 25px;
  margin-top: 25px;
}

.globe-wrap img {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  border: 1px solid #ccc;
}

.globe-text {
  max-width: 500px;
  font-size: 16px;
  line-height: 1.4;
  color: #333;
  text-align: justify;
}

@media only screen and (max-width: 700px) {
  .globe-wrap {
    flex-direction: column;
    text-align: center;
  }
  .globe-text {
    text-align: left;
    max-width: 90%;
  }
}
</style>
</head>

<body>
  <div class="globe-wrap">
    <img src="../images/test_atmos_bday_EGU26.png" alt="JetLag Globe">
    <div class="globe-text">
      The Lagrangian framework identifies jets by their material function rather than
      instantaneous wind maxima. This circular image layout keeps the globe visible and
      the text aligned beside it on wider screens, stacking gracefully on smaller ones.
    </div>
  </div>
</body>
</html>
