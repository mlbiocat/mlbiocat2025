---
layout: archive
title: "Workshop Schedule"
permalink: /schedule/
author_profile: true
---



<table>
  <thead>
    <tr>
      <th style="width: 20%;">Time</th>
      <th style="width: 80%;">Session</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>09:00 - 09:30</strong></td>
      <td><strong>Registration</strong></td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>09:30 - 09:45</strong></td>
      <td><strong>Rebecca Buller</strong> (opening)</td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>09:45 - 10:20</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Gustav Oberdorfer</strong> (TU Graz): Computational design of highly active de novo enzymes 
        </div>
        <div class="abstract" style="display: none;">
          Abstract: Reliably introducing function into genetically encodable de novo proteins is still a challenging task. Current design methods mostly produce de novo enzymes with low activities. As a result, they require costly experimental optimization and high-throughput screening to be industrially viable. We developed rotamer inverted fragment finder–diffusion (Riff-Diff), a hybrid machine learning and atomistic modelling strategy for scaffolding catalytic arrays in de novo protein backbones. We show that proficient enzymes can be generated with Riff-Diff while screening as little as 35 designs. The talk will highlight challenges and findings during scaffolding active sites for catalyzing the retro-aldol and Morita Baylis-Hillman reaction, as well as metal cofactors of increasing complexity.
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>10:20 - 10:55</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Sílvia Osuna</strong> (University of Girona): Beyond AlphaFold: How to computationally generate efficient enzymes?
        </div>
        <div class="abstract" style="display: none;">
          Abstract: tba
        </div>
      </td>
    </tr>
    <tr>
      <td><strong>10:55 - 11:10</strong></td>
      <td><strong>Coffee break</strong></td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>11:10 - 11:35</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Mattia Gollub</strong> (Jura Bio)
        </div>
        <div class="abstract" style="display: none;">
          Abstract: tba
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>11:35 - 12:00</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Christian Gruber</strong> (Innophore)
        </div>
        <div class="abstract" style="display: none;">
          Abstract: tba
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>12:00 - 12:25</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Jürgen Pleiss</strong> (University of Stuttgart): Making enzymatic data AI-ready
        </div>
        <div class="abstract" style="display: none;">
          Abstract: tba
        </div>
      </td>
    </tr>
    <tr>
      <td><strong>12:25 - 14:00</strong></td>
      <td><strong>Lunch & poster session</strong></td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>14:00 - 14:25</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Adrian Bunzel</strong> (ETH Zurich)
        </div>
        <div class="abstract" style="display: none;">
          Abstract: tba
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>14:25 - 15:00</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Markus Jeschek</strong> (University of Regensburg)
        </div>
        <div class="abstract" style="display: none;">
          Abstract: tba
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>15:00 - 15:35</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Ditte Hededam Welner</strong> (DTU Biosustain): How we try to use machine learning on limited-size enzymology datasets for prediction and engineering of glycosyltransferases
        </div>
        <div class="abstract" style="display: none;">
          Abstract: Functional prediction from enzyme sequence remains a major challenge in biocatalysis and enzyme engineering. For some enzyme families, sequence-function relationships are particularly elusive, and seem to be governed by complex patterns that escape our elucidation. This is true for glycosyltransferases of family 1. This enzyme family is promiscuous and notorious for escaping elucidation of robust structure-function relationships. It is also an enzyme family with large industrial potential, due to its capability of regioselective and stereoselective glycosylation of a vast array of industrially relevant molecules, including pharmaceuticals, nutraceuticals, and cosmetics.
Machine learning is becoming recognized a powerful tool in enzymology, due to its strength in recognizing patterns in complex data. It is challenged by the limited size and varying quality of many enzymology dataset. We continuously work to develop a robust and versatile predictor for glycosyltransferase prediction and engineering. The current status of this effort will be presented.
        </div>
      </td>
    </tr>
    <tr>
      <td><strong>15:35 - 16:00</strong></td>
      <td><strong>Coffee break</strong></td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>16:00 - 17:00</strong></td>
      <td><strong>Panel discussion</strong></td>
    </tr>
    <tr>
      <td><strong>17:00 - 19:00</strong></td>
      <td><strong>Closing remarks & poster session</strong></td>
    </tr>
  </tbody>
</table>

<script>
  function toggleAbstract(row) {
    const abstract = row.nextElementSibling;
    if (abstract.style.display === "none" || abstract.style.display === "") {
      abstract.style.display = "block";
    } else {
      abstract.style.display = "none";
    }
  }
</script>

<style>
  .clickable-row {
    cursor: pointer;
    color: rgb(73, 78, 82);
    text-decoration: none;
  }
  .clickable-row:hover {
    color: rgb(73, 78, 82);
  }
  .abstract {
    margin-top: 5px;
    font-style: italic;
    background-color: #f9f9f9;
    padding: 10px;
    border-left: 3px solid #007bff;
  }
</style>
