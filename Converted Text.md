**_PROTEIN-PROTEIN NETWORK ANALYSIS_**

** **

**Author** - NARENDRAN MAYILVAGANAN **(@Naren037)**

** **

**INTRODUCTION:**

**<!--[if gte vml 1]><v:shapetype id="_x0000_t75" coordsize="21600,21600"
 o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f"
 stroked="f">
 <v:stroke joinstyle="miter"/>
 <v:formulas>
  <v:f eqn="if lineDrawn pixelLineWidth 0"/>
  <v:f eqn="sum @0 1 0"/>
  <v:f eqn="sum 0 0 @1"/>
  <v:f eqn="prod @2 1 2"/>
  <v:f eqn="prod @3 21600 pixelWidth"/>
  <v:f eqn="prod @3 21600 pixelHeight"/>
  <v:f eqn="sum @0 0 1"/>
  <v:f eqn="prod @6 1 2"/>
  <v:f eqn="prod @7 21600 pixelWidth"/>
  <v:f eqn="sum @8 21600 0"/>
  <v:f eqn="prod @7 21600 pixelHeight"/>
  <v:f eqn="sum @10 21600 0"/>
 </v:formulas>
 <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"/>
 <o:lock v:ext="edit" aspectratio="t"/>
</v:shapetype><v:shape id="image1.png" o:spid="_x0000_i1025" type="#_x0000_t75"
 style='width:451.5pt;height:278.25pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="file:///C:/Users/NARENM~1/AppData/Local/Temp/msohtmlclip1/01/clip_image001.png"
  o:title=""/>
</v:shape><![endif]--><!--[if !vml]-->![](file:///C:/Users/NARENM~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.gif)<!--[endif]-->**

**Fig 1. Schematic representation of PPI Network analysis**

** **

** **

Protein-Protein Interaction (PPI) network is the analysis of Protein interactions at the cellular level to represent the physical or functional interactions between proteins using mathematical models and graphs. These interactions take place between the binding regions that are present in the proteins, and they are attributed to a specific biological function.

**Topological analysis** - The maximum number of proteins in a network have very minimal interactions whereas only a few key proteins (Hub proteins) contain high interactions, and due to this variation, no single node can be used as a scale to generalize all the other nodes of the network and are hence called “scale-free”(Albert, 2005).

**Modular analysis** - Breakdown of a complex biological network into simpler closely related modules, mainly based on functional similarities (Luo et al., 2007).

 

**PROTEIN-PROTEIN INTERACTION DETECTION:**

**Biophysical methods** - Mass spectrometry, affinity chromatography, co-immunoprecipitation, protein microarrays, protein fragment completion, phage display, X-ray crystallography, and NMR spectroscopy (Rao et al., 2014a).

**High-throughput methods**

<!--[if !supportLists]-->●        <!--[endif]-->Yeast two-hybrid system - Predicting binding of two target proteins by fusing them with the DNA binding domain and transactivating domain of a transcription factor (Walhout & Vidal, 2001).  

<!--[if !supportLists]-->●        <!--[endif]-->Co-expression - Genes of proteins involved in an interaction are co-expressed to enable the products’ interaction.

<!--[if !supportLists]-->●        <!--[endif]-->Synthetic lethality - Introducing mutations in genes that are viable on their own but become lethal when combined - indirect; can predict functional interactions.

**Computational methods - **The generation of valuable experimental data led to the development of several _in silico_ methods for predicting new protein-protein interactions, such as sequence-based approaches, structure-based approaches, chromosome proximity, gene fusion, _in silico_ 2 hybrid, mirror tree, phylogenetic tree, gene ontology, and gene expression-based approaches (Rao et al., 2014).

** **

**Protein interaction database** - The predicted protein-protein interaction data are stored in databases such as MINT and STRING (Calderone et al., 2020; Szklarczyk et al., 2023)

**Construction and visualization tools** - SNOW, POINET, BIANA, etc.

 

**PPI NETWORK IN CANCER:**

Protein interaction networks give insight into the molecular mechanisms behind diseases and can aid in the prevention, diagnosis, and treatment of cancer by creating a pipeline (Sanz-Pamplona et al., 2012). This study uses human protein-protein interaction networks to identify target genes by establishing sub-networks for respective cancer types (Amala & Emerson, 2019).

.

**REFERENCES:**

Albert, R. (2005). Scale-free networks in cell biology. _Journal of Cell Science_, _118_(21), 4947–4957. https\://doi.org/10.1242/jcs.02714

Amala, A., & Emerson, I. A. (2019). Identification of target genes in cancer diseases using protein–protein interaction networks. _Network Modeling Analysis in Health Informatics and Bioinformatics_, _8_(1), 2. https\://doi.org/10.1007/s13721-018-0181-1

Calderone, A., Iannuccelli, M., Peluso, D., & Licata, L. (2020). Using the MINT Database to Search Protein Interactions. _Current Protocols in Bioinformatics_, _69_(1). https\://doi.org/10.1002/cpbi.93

Luo, F., Yang, Y., Chen, C.-F., Chang, R., Zhou, J., & Scheuermann, R. H. (2007). Modular organization of protein interaction networks. _Bioinformatics_, _23_(2), 207–214. https\://doi.org/10.1093/bioinformatics/btl562

Rao, V. S., Srinivas, K., Sujini, G. N., & Kumar, G. N. S. (2014a). Protein-Protein Interaction Detection: Methods and Analysis. _International Journal of Proteomics_, _2014_, 1–12. https\://doi.org/10.1155/2014/147648

Rao, V. S., Srinivas, K., Sujini, G. N., & Kumar, G. N. S. (2014b). Protein-Protein Interaction Detection: Methods and Analysis. _International Journal of Proteomics_, _2014_, 1–12. https\://doi.org/10.1155/2014/147648

Sanz-Pamplona, R., Berenguer, A., Sole, X., Cordero, D., Crous-Bou, M., Serra-Musach, J., Guinó, E., Pujana, M. Á., & Moreno, V. (2012). Tools for protein-protein interaction network analysis in cancer research. _Clinical and Translational Oncology_, _14_(1), 3–14. https\://doi.org/10.1007/s12094-012-0755-9

Szklarczyk, D., Kirsch, R., Koutrouli, M., Nastou, K., Mehryary, F., Hachilif, R., Gable, A. L., Fang, T., Doncheva, N. T., Pyysalo, S., Bork, P., Jensen, L. J., & von Mering, C. (2023). The STRING database in 2023: protein–protein association networks and functional enrichment analyses for any sequenced genome of interest. _Nucleic Acids Research_, _51_(D1), D638–D646. https\://doi.org/10.1093/nar/gkac1000

Walhout, A. J. M., & Vidal, M. (2001). High-Throughput Yeast Two-Hybrid Assays for Large-Scale Protein Interaction Mapping. _Methods_, _24_(3), 297–306. https\://doi.org/10.1006/meth.2001.1190

 
