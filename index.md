---
layout: default
---

  <div style="position: fixed; top: 10px; right: 10px; border: 1px solid black; padding: 10px; background-color: white;">
      <strong>Cell Type Abbreviation Legend:</strong><br>
      <u style="color: blue;">Statin-Sensitive</u><br>
      <b>RC: </b>VHL(+)<br>
      <b>H1: </b>VHL(+), Hif1(-)<br>
      <b>H12: </b>VHL(+), Hif1/2(-)<br>
      <u style="color: red;">Statin-Insensitive</u><br>
      <b>H2: </b>VHL(+), Hif2(-)<br>
      <b>RVN: </b>VHL(-)
  </div>
[Please view on desktop, not mobile]
  
## GSEA Gene Count Index
GSEA Performed using Hallmark, Reactome, GO, and KEGG gene sets.

Click on gene set headings in tables linked below to see which enriched pathways the genes were found in.

### New Comparisons without trop2 (23 total genes)
{RVN vs RC, H2 vs H1, H2 vs H12, H2 vs RFL, RVN vs H12, RVN vs H1}
1. [Upregulated](/LW15-Target-Genes/Common%20Genes/New%20Comparisons/Without%20trop2/Up_GeneTable_interactive.html) (18)
2. [Downregulated](/LW15-Target-Genes/Common%20Genes/New%20Comparisons/Without%20trop2/Down_GeneTable_interactive.html) (5)




<details>
<summary><span style="font-weight: bold; font-size: 1.17em;">Other (click to expand)</span></summary>
<br> <!-- Add an empty line here -->
<div>
  <p style="margin-left: 20px;"><strong>Original Comparisons</strong></p>
  <div style="margin-left: 40px;">
    <p>{RVN vs RC, H2 vs H1, H2 vs H12 , trop2 vs non}</p>
    <ol>
      <li><a href="/LW15-Target-Genes/Common%20Genes/Original%20Comparisons/OriginalComparisons_Up_GeneTable_interactive.html">Upregulated</a> (28)</li>
      <li><a href="/LW15-Target-Genes/Common%20Genes/Original%20Comparisons/OriginalComparisons_Down_GeneTable_interactive.html">Downregulated</a> (16)</li>
    </ol>
  </div>

  <p style="margin-left: 20px;"><strong>New Comparisons</strong></p>
  <div style="margin-left: 40px;">
    <p>{RVN vs RC, H2 vs H1, H2 vs H12, H2 vs RFL, RVN vs H12, RVN vs H1, trop2 vs non}</p>
    <ol>
      <li><a href="/LW15-Target-Genes/Common%20Genes/New%20Comparisons/NewComparisons_Up_GeneTable_interactive.html">Upregulated</a> (12)</li>
      <li><a href="/LW15-Target-Genes/Common%20Genes/New%20Comparisons/NewComparisons_Down_GeneTable_interactive.html">Downregulated</a> (4)</li>
    </ol>
  </div>
</div>
</details>





## PCA Data
<figure>
  <img src="images/PCA Screenshot.png" alt="Sensitive vs resistant separated along PC1" width="600"/>
</figure>
*Note: Sensitive vs resistant separate along PC1 & cell type replicate clusters are marked*

### Interactive PCA plot
<iframe src="images/3D_PCA_Plot.html" width="700" height="600"></iframe>
*sensitive - blue & insensitive - red*

## Volcano Plot (Differential Expression) Data
### Sensitive vs Non-Sensitive
<figure>
  <img src="images/Volc plot screenshot.png" alt="149 significant genes: 114 upregulated & 39 downregulated" width="600"/>
</figure>
*149 significant genes: 114 upregulated & 39 downregulated in sensitive group*

### Significant Volcano Plot Genes
1. [Upregulated](/LW15-Target-Genes/Common%20Genes/Volc%20%26%20PCA%20Data/sensi_vs_non_upregulated_genes.html) (114)
2. [Downregulated](/LW15-Target-Genes/Common%20Genes/Volc%20%26%20PCA%20Data/sensi_vs_non_downregulated_genes.html) (39)

## Combined Analysis
### PCA & Volcano: 
<p><strong style="color: red;">Every Text field in the Venn Diagram is clickable to see gene lists</strong></p>


<!-- Venn Diagram Linked Image -->
<figure>
  <img src="images/Venn Diagram.png" alt="PCA & Volc Plot Venn Diagram" width="700" height="474" usemap="#imagemap">
  <figcaption><i>Click on text fields in venn diagram to see gene lists</i></figcaption>
</figure>

<map name="imagemap">
  <area shape="rect" coords="94,41,293,92" alt="PCA Top 200 Genes" href="Common%20Genes/Volc%20%26%20PCA%20Data/PCA_Top_200_genes.html">
  <area shape="rect" coords="359,42,545,93" alt="Volcano Plots 149 Significant Genes" href="Common%20Genes/Volc%20%26%20PCA%20Data/sensi_vs_non_total_genes.html">
  <area shape="rect" coords="292,170,341,205" alt="46 Common Genes" href="Common%20Genes/Volc%20&%20PCA%20Data/46_Overlapping_Genes.html">
  <area shape="rect" coords="126,158,206,201" alt="PCA Unique Genes" href="Common%20Genes/Volc%20%26%20PCA%20Data/PCA_unique.html">
  <area shape="rect" coords="432,160,516,200" alt="Volcano Unique Genes" href="Common%20Genes/Volc%20%26%20PCA%20Data/volc_unique.html">


<h3>Stitch Networks</h3>
<p>Note: some genes cannot be found on the Stitch database</p>
<ul>
  <li><a href="http://stitch.embl.de/cgi/network.pl?taskId=Bj8Z86TeGiyP" target="_blank">23 GSEA genes &amp; 46 common PCA/Volcano genes</a> (65 Genes on Stitch database)</li>
  <li><a href="http://stitch.embl.de/cgi/network.pl?taskId=IGQz3UZFH7gw" target="_blank">23 GSEA genes &amp; 303 total PCA/Volcano genes</a> (259 Genes on Stitch database)</li>
</ul>

<footer>
  <br>
  <br>
  <!-- other footer content -->

  <!-- Link to GitHub profile -->
  <a href="https://github.com/ebowen19/LW15-Target-Genes" target="_blank">LW15 Target Genes Github Repository</a> with html & csv files
</footer>
