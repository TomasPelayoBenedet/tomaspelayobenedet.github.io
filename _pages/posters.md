---
layout: page
permalink: /posters/
title: Posters
description: Posters by Tomás
nav: true
nav_order: 4
---

## DIMVA'24: Ensuring Reproducibility in AGD Detection: A Model Comparison Framework

<div class="poster-section">
  <div class="poster-container">
    <div class="poster-image">
      <img src="../assets/posters/jpg/dimva24.jpg" alt="DIMVA'24">
    </div>
    <div class="poster-details">
      <p><strong>Abstract:</strong> Domain generation algorithms are commonly used by malware to generate command and control domains to contact during execution, avoiding having to use fixed IP addresses or DNS domains, which are easily blockable. During the last years, many solutions have been proposed for the detection of algorithmically generated domains (AGDs) based on artificial intelligence. However, there is no common umbrella that allows experiments to be replicated under the same conditions, making it difficult to ensure how good one solution is compared to the others. To address the current lack of a common environment for model comparison, in this work we present a framework focused on training and comparing artificial intelligence models for AGDs detection. As a use case, we have implemented and evaluated the models proposed in the latest works in this field, showing its applicability.</p>
      <a href="../assets/posters/pdf/dimva24.pdf" download class="btn" target="_blank">Download in PDF</a>
    </div>
  </div>
</div>
<style>
  .poster-section {
    border-bottom: 2px solid #eee;
    padding-bottom: 20px;
    margin-bottom: 20px;
  }
  .poster-container {
    display: flex;
    align-items: center;
  }
  .poster-image {
    flex: 1;
    max-width: 30%;
    padding-right: 20px;
    position: relative;
    overflow: hidden;
  }
  .poster-image img {
    width: 100%;
    border: 1px solid #ddd;
    padding: 5px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .poster-image img:hover {
    transform: scale(3);
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
    z-index: 10;
    position: relative;
  }
  .poster-details {
    flex: 2;
  }
  .btn {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 10px;
    font-size: 16px;
    text-decoration: none;
    color: white;
    background-color: #007bff;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  .btn:hover {
    background-color: #0056b3;
  }
</style>