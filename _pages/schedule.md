---
layout: archive
title: "Workshop Schedule"
permalink: /schedule/
author_profile: true
---



<p>Click to view abstracts.</p>

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
          <strong>Silvia Osuna</strong> (University of Girona): Beyond AlphaFold: How to computationally generate efficient enzymes?
        </div>
        <div class="abstract" style="display: none;">
          Enzymes are essential for supporting life by accelerating chemical reactions in a biologically compatible timescale. These remarkable catalysts possess unique features like high specificity and selectivity, and they function under mild biological conditions. These extraordinary characteristics make the design of enzymes for industrially relevant targets highly appealing. 
Enzymes exist as an ensemble of conformational states, and the populations of these states can be altered through substrate binding, allosteric interactions, and even by introducing mutations into their sequence. These conformational states can be altered through mutations, which facilitates the evolution of enzymes towards acquiring novel activities.[1] Interestingly, many laboratory-evolved enzymes exhibit a common pattern—a significant impact on the catalytic activity is often observed due to remote mutations located distal from the catalytic center.[2] Similar to allosterically regulated enzymes, distal mutations play a role in regulating enzyme activity by stabilizing pre-existing conformational states that are crucial for catalysis.
In this talk, the rational approaches we have developed for enzyme design along the years will be discussed. These approaches rely on inter-residue correlations derived from microsecond time-scale Molecular Dynamics (MD) simulations, enhanced sampling techniques, and more recently, the development and application of a template-based AlphaFold2 based approach for rational enzyme design.[1-4] Over the years, our research on various enzyme systems has provided compelling evidence that the current challenge of predicting distal active sites to enhance functionality in computational enzyme design can ultimately be addressed.[2, 5]
<br><br>
1. Maria-Solano, M. A.; Serrano-Hervás, E.; Romero-Rivera, A.; Iglesias-Fernández, J.; Osuna, S. Role of conformational dynamics for the evolution of novel enzyme function, Chem. Commun. 2018, 54, 6622-6634.<br>
2. Osuna, S. The challenge of predicting distal active site mutations in computational enzyme design, WIREs Comput Mol Sci. 2020, e1502.<br>
3. Casadevall, G.; Duran, C.; Osuna, S. AlphaFold2 and Deep Learning for Elucidating Enzyme Conformational Flexibility and Its Application for Design, JACS Au 2023, 3, 1554.<br>
4. Casadevall, G.; Duran, C.; Estévez-Gay, M.; Osuna, S. Estimating conformational heterogeneity of tryptophan synthase with a template-based AlphaFold2 approach, Prot. Sci. 2022, 31, e4426.<br>
5. Duran, C.;  Kinateder, T.; Hiefinger, C.; Sterner, R.; Osuna, S. Altering Active-Site Loop Dynamics Enhances Standalone Activity of the Tryptophan Synthase Alpha Subunit, ACS Catal., 2024, 14, 16986–16995<br>
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
          <strong>Mattia Gollub</strong> (Jura Bio): Synthesizing Biological Sequences Designed by Generative Models at Petascale
        </div>
        <div class="abstract" style="display: none;">
          Abstract: Generative modeling offers a powerful paradigm for designing novel functional DNA, RNA and protein sequences. We introduce a method to efficiently synthesize designs from generative models in the real world. The method consists of an integrated machine learning and wet lab procedure, which implements generative sampling algorithms physically through controlled stochastic chemical reactions. We demonstrate synthesizing ~10<sup>16</sup> designs from a generative model of human antibodies, at a level of realism and diversity comparable to state-of-the-art protein language models, and a cost of ~$10<sup>3</sup>. The library yields hundreds of therapeutic scFv CAR candidates against HLA-presented intracellular tumor antigens. Using previous methods, a library of the same size and quality would cost roughly ~$10<sup>15</sup>.
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
          <strong>Jürgen Pleiss</strong> (University of Stuttgart): Making enzymatic data FAIR and AI-ready
        </div>
        <div class="abstract" style="display: none;">
          Abstract: Data management has become a bottleneck to progress in biocatalysis. In order to take advantage of the rapid progress in experimental and computational technologies, biocatalytic data should be     findable, accessible, interoperable, and reusable (FAIR), and data analysis should be scalable and reproducible.[1] The EnzymeML framework (https://github.com/EnzymeML) provides reusable tools and a standardized data exchange format for FAIR and scalable data management in biocatalysis.[2] An EnzymeML document contains information about reaction conditions and the measured time course of substrate or product concentrations, and about the rate equation and the estimated kinetic parameters of the subsequent modelling step.[3] The final EnzymeML document is entered into a local database or is uploaded to a public repository. The workflow of a project is encoded as Jupyter Notebook, which can be re-used or extended. Machine-readable data enable the application of AI tools at different stages of the data life cycle: upon parsing of data and metadata and for modelling of reaction kinetics, where machine learning approaches complement ODE-based mechanistic modelling.[4] The FAIRification of data and software and the digitalization of biocatalysis improve the efficiency of research by automation, guarantee the scientific quality by reproducibility, and enable the application of novel modelling strategies. 
<br><br>
1.	Pleiss, J. FAIR data and software: improving efficiency and quality of biocatalytic science. ACS Catal 14, 2709-2718 (2024).<br>
2.	Lauterbach, S. et al. EnzymeML: seamless data flow and modeling of enzymatic data. Nat Methods 20, 400-402 (2023).<br>
3.	Range, J. et al. EnzymeML—a data exchange format for biocatalysis and enzymology. FEBS J 289, 5864-5874 (2022).<br>
4.	Pleiss, J. Modeling enzyme kinetics: current challenges and future perspectives for biocatalysis. Biochemistry 63, 2533-2541 (2024).
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
          <strong>Adrian Bunzel</strong> (ETH Zurich): AI.zymes: A Modular Platform for Evolutionary Enzyme Design
        </div>
        <div class="abstract" style="display: none;">
          Abstract: The ability to reliably create novel enzymes would transform biomedicine and the chemical industry. While enzymes can be designed computationally, their activities often remain limited. To address this challenge, our group integrates protein design with directed evolution to engineer biocatalysts exhibiting enzyme-like activity [1]. Moreover, evolution provides key insights into fundamental principles of biocatalysis [2], such as conformational dynamics [3,4] and electrostatic catalysis [5].<br>
A major limitation of current enzyme design algorithms is their focus on protein stability, making it difficult to design properties specific to enzyme catalysts. To overcome this limitation and harness the lessons learned during enzyme evolution, we developed AI.zymes, a modular platform for evolutionary enzyme design [6]. AI.zymes bridges this gap by integrating cutting-edge protein design tools—including Rosetta, ESMFold, ProteinMPNN, and FieldTools—in an evolutionary design framework comprising iterative rounds of design and selection. Notably, evolutionary selection allowed the optimization of enzyme properties, such as electrostatic catalysis, that were not targeted by the employed design programs. We validated AI.zymes by optimizing the promiscuous Kemp eliminase activity of ketosteroid isomerase (KSI), achieving a 7.7-fold increase in activity after testing only seven variants.<br>
Reliable enzyme design will likely require a holistic framework that accounts for the dynamic and electrostatic effects essential to biocatalysis. AI.zymes provides such a framework by integrating cutting-edge design algorithms within an evolutionary pipeline to optimize enzyme-specific features.<br><br>
References<br>
[1] Bunzel HA et al., J Am Chem Soc, 2019.<br>
[2] Bunzel HA et al., Curr Opin Struct Biol, 2021.<br>
[3] Otten R et al., Science, 2020.<br>
[4] Bunzel HA et al., Nat Chem, 2021.<br>
[5] Jabeen H et al., ACS Catal, 2024.<br>
[6] Merlicek LP et al., bioRxiv, 2025.
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>14:25 - 14:50</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Julian Englert</strong> (Adaptyv Bio): Adaptyv - The cloud lab for protein designers
        </div>
        <div class="abstract" style="display: none;">
          Abstract: Thanks to advances in AI tools such as AlphaFold, RFdiffusion & co, protein design has become the fastest growing area of biotechnology. But what good is a computationally designed protein if you can't actually test it in the lab? At Adaptyv, we're running an automated lab that allows protein designers to get high-quality experimental data to see how their proteins perform. They can simply upload their designs to our web portal, choose the type of assay they want to run, and our lab completes the experiments in just a couple weeks for them. In this talk we'll present some of the infrastructure (lab automation, molecular biology and software) that we had to build to make this work at scale to run smoothly on a daily basis with dozens of customers from the best protein design companies in the world.  
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>14:50 - 15:25</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Markus Jeschek</strong> (University of Regensburg/EPFL): From sequence to function and back – Data-driven engineering of synthetic microbes for sustainable bioproduction
        </div>
        <div class="abstract" style="display: none;">
          Abstract: The pressing ecological issues of our time impose an urgent need for sustainable solutions to maintain our life standards. Synthetic microbes engineered to produce value-added chemicals based on renewables are an attractive means to replace petrochemical production. However, their engineering remains intricate and prone to unsatisfying outcomes, such as insufficient productivity or the incapability to access many non-natural compounds.
In my talk, I will show how we combine high-throughput experimental technology with machine learning to overcome some of the shortcomings of our “engineering toolbox”. I will showcase how such data-driven approaches can streamline the engineering of microbes such as Escherichia coli on all levels of the central dogma to tweak gene regulation, enzymatic activity and metabolic flux [1-4]. Further, I will introduce different techniques to improve model performance through active learning and rational training set design.<br><br>
[1] Vornholt, Mutný, Schmidt, Schellhaas, Tachibana, Panke, Ward, Krause, Jeschek. ACS Central Sci. 2024 10 (7), 1357-1370.<br>
[2] Höllerer & Jeschek. Nucl. Acids Res. 51:2377-2396 (2023).<br>
[3] Vornholt, Christoffel, Pellizzoni, Panke, Ward, Jeschek. Sci. Adv. 7:eabe4208 (2021).<br>
[4] Höllerer, Papaxanthos, Gumpinger, Fischer, Beisel, Borgwardt, Benenson, Jeschek. Nat. Commun. 11:3551 (2020).
        </div>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>15:25 - 16:00</strong></td>
      <td>
        <div class="clickable-row" onclick="toggleAbstract(this)">
          <strong>Ditte Hededam Welner</strong> (DTU Biosustain): How we try to use machine learning on limited-size enzymology datasets for prediction and engineering of glycosyltransferases
        </div>
        <div class="abstract" style="display: none;">
          Abstract: Functional prediction from enzyme sequence remains a major challenge in biocatalysis and enzyme engineering. For some enzyme families, sequence-function relationships are particularly elusive, and seem to be governed by complex patterns that escape our elucidation. This is true for glycosyltransferases of family 1. This enzyme family is promiscuous and notorious for escaping elucidation of robust structure-function relationships. It is also an enzyme family with large industrial potential, due to its capability of regioselective and stereoselective glycosylation of a vast array of industrially relevant molecules, including pharmaceuticals, nutraceuticals, and cosmetics.<br>
Machine learning is becoming recognized a powerful tool in enzymology, due to its strength in recognizing patterns in complex data. It is challenged by the limited size and varying quality of many enzymology dataset. We continuously work to develop a robust and versatile predictor for glycosyltransferase prediction and engineering. The current status of this effort will be presented.
        </div>
      </td>
    </tr>
    <tr>
      <td><strong>16:00 - 16:15</strong></td>
      <td><strong>Coffee break</strong></td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>16:15 - 17:15</strong></td>
      <td><strong>Panel discussion</strong></td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td><strong>17:15 - 17:30</strong></td>
      <td><strong>Andreas Krause</strong> (closing remarks)</td>
    </tr>
        <tr>
      <td><strong>17:30 - 19:00</strong></td>
      <td><strong>Poster session and apéro</strong> (sponsored by Innophore)</td>
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




  <h2>How to Get to the Workshop - ETH Zurich HG Building</h2>
  
  <div class="info">
      <h3>From Zurich Airport (ZRH):</h3>
      <ul>
          <li>Take the train (S-Bahn) from Zurich Airport to <strong>Zurich HB (Main Station)</strong>. Trains run frequently, and the journey takes about 10-15 minutes.</li>
          <li>From Zurich HB, follow the directions below.</li>
      </ul>
  </div>
  
  <div class="info">
      <h3>From Zurich HB (Main Train Station):</h3>
      <ul>
          <li>Take tram number <strong>6</strong> (direction Zoo) or <strong>10</strong> (direction Flughafen) and get off at <strong>ETH/Universitätsspital</strong>.</li>
          <li>Alternatively, walk from Zurich HB to ETH Zurich, which takes about 10-15 minutes uphill.</li>
          <li>Use the <strong>Polybahn</strong> (funicular) from Central station to reach ETH Zurich easily.</li>
      </ul>
  </div>
  
  <p>Once at ETH Zurich, follow the signs to the <strong>HG Building (Main Building)</strong>. The workshop location will be indicated inside.</p>
  
  <div class="image-container">
      <h3>ETH Zurich HG Building Location:</h3>
      <img src="/files/main-map-eth.jpg" alt="ETH Zurich Location Map">
  </div>

  <div class="image-container">
      <h3>Workshop Floor Plan:</h3>
      <img src="/files/event-map-room-locatiojn-2.jpg" alt="ETH Zurich Workshop Map">
  </div>
  
  <h2>Poster Setup</h2>
  <div class="info">
      <p>Attendees are advised to set up their posters upon arrival on any available poster board (highlighted in green in the map above). There is no designated order; it is first-come, first-served. There should be enough poster boards for everyone.</p>
  </div>


