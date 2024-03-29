Highly dynamic evolution of the chemosensory system driven by gene gain and loss across subterranean beetles

Pau Balart-García, Tessa M. Bradford, Perry G. Beasley-Hall, Slavko Polak, Steven J. B. Cooper & Rosa Fernández

Molecular Phylogenetics and Evolution

SUPPLEMENTARY DATA:

-CSG_DB_Bitacora.zip: Custom chemosensory gene databases used for the annotations with Bitacora (Vizueta et al., 2020) based on previously annotated genes.
The included gene families are the following: odorant receptors (OR), gustatory receptors (GR), ionotropic receptors (IR), ionotropic glutamate receptors (IGluR), sensory neuron membrane proteins (SNMP), odorant-binding proteins (OBP) and chemosensory proteins (CSP).
Databases include sequences of Drosophila melanogaster obtained from flybase.org (i.e., GRs, IGluRs and SNMP) and sequences of several Coleoptera species (ORs, GRs, IRs, SNMPs, CSPs, OBPs) obtained from previous phylogenomic studies (Dippel et al. 2014, 2016; Schoville et al. 2018; Andersson et al. 2019; Zhao et al. 2020).
For each gene family there is a FASTA file (aminoacid sequences) and a HMM file (HMMER domain models).

-Raw_hits.zip: Raw hits for each species (n=41; Balart-García et al., 2023) and gene families (n=7) obtained with Bitacora searhes. Protein IDs in the FASTA files begin with a unique 5 character code corresponding to each species:

Species (ID): Agrilus planipennis (APLA1), Allodessus bistrigatus (ABIS2), Amphizoa insolens (AINS1), Anoplophora glabripennis (AGLA1), Astagobius angustatus (AANG1), Bathysciola ovata (BOVA2), Bathysciola rugosa (BRUG1), Bathysciola zariquieyi (BZAR1), Bathysciomorphus slavkoi (BSLA1), Breuilia triangulum (BTRI1), Calosoma frigidum (CFRI1), Catops fuliginosus (CFUL1), Chrysoperla nipponensis (CNIP1), Clambus nigriclavis (CNIG1), Cybister japonicus (CJAP1), Cyphon laevipennis (CLAE1), Dendroctonus ponderosae (DPON1), Gyrinus marinus (GMAR2), Hydrochus megaphallus (HMEG1), Hydroscapha redfordi (HRED1), Laricobius nigrinus (LNIG1), Leptodirus hochenwarti (LHOC1), Limbodessus amabilis (LAMA1), Limbodessus cueensis (LCUE1), Limbodessus hinkleri (LHIN1), Limbodessus palmulaoides (LPAL1), Mengenilla moldrzyki (MMOL1), Micromalthus debilis (MDEB1), Neobidessodes gutteridgei (NGUT3), Nicrophorus vespilloides (NVES1), Onthophagus taurus (OTAU1), Oryotus schmidti (OSCH1), Paranillochlamys urgellesi (PURG1), Paroster macrosturtensis (PMAC3), Paroster nigroadumbratus (PNIG1), Parvospeonomus canyellesi (PCAN1), Photinus pyralis (PPYR3), Prospelaeobates brelihi (PBRE1), Speonomus longicornis (SLON1), Tribolium castaneum (TCAS1), Troglocharinus ferreri (TFER2).

-Validated_hits.zip: Validated protein hits (FASTA) thought manual curation and phylogenetic inferences for each of the included species (n=41) and each of the selected gene families (n=7).

-Phylogenies.zip: For each of the studied gene families (n=7) there is the code example for all the steps to infer a gene tree (.sh) and the necessary inputs/outputs: the protein sequences (.fasta), the protein sequence aligments (.aln), the trimmed aligments (trimmed_gt04.fasta), the guide trees (guide.treefile), and the consensus trees (.contree).

References:

Andersson, M.N., Keeling, C.I., Mitchell, R.F., 2019. Genomic content of chemosensory genes correlates with host range in wood-boring beetles (Dendroctonus ponderosae, Agrilus planipennis, and Anoplophora glabripennis). BMC Genomics. 20.

Balart-García, P., Aristide, L., Bradford, T.M., Beasley-Hall, P.G., Polak, S., Cooper, S.J.B., Fernández, R., 2023. Parallel and convergent genomic changes underlie independent subterranean colonization across beetles. Nat. Commun. 14, 3842.

Dippel, S., Oberhofer, G., Kahnt, J., Gerischer, L., Opitz, L., Schachtner, J., Stanke, M., Schütz, S., Wimmer, E. A., Angeli, S., 2014. Tissue-specific transcriptomics, chromosomal localization, and phylogeny of chemosensory and odorant binding proteins from the red flour beetle Tribolium castaneum reveal subgroup specificities for olfaction or more general functions. BMC Genomics 15:1141

Dippel, S., Kollmann, M., Oberhofer, G., Montino, A., Knoll, C., Krala, M., Rexer, K.-H., Frank, S., Kumpf, R., Schachtner, J., Wimmer, E.A., 2016. Morphological and Transcriptomic Analysis of a Beetle Chemosensory System Reveals a Gnathal Olfactory Center. BMC Biol. 14, 90.

Schoville, S.D., Chen, Y.H., Andersson, M.N., Benoit, J.B., Bhandari, A., Bowsher, J.H., Brevik, K., Cappelle, K., Chen, M.-J.M., Childers, A.K., Childers, C., Christiaens, O., Clements, J., Didion, E.M., Elpidina, E.N., Engsontia, P., Friedrich, M., García-Robles, I., Gibbs, R.A., Goswami, C., Grapputo, A., Gruden, K., Grynberg, M., Henrissat, B., Jennings, E.C., Jones, J.W., Kalsi, M., Khan, S.A., Kumar, A., Li, F., Lombard, V., Ma, X., Martynov, A., Miller, N.J., Mitchell, R.F., Munoz-Torres, M., Muszewska, A., Oppert, B., Palli, S.R., Panfilio, K.A., Pauchet, Y., Perkin, L.C., Petek, M., Poelchau, M.F., Record, É., Rinehart, J.P., Robertson, H.M., Rosendale, A.J., Ruiz-Arroyo, V.M., Smagghe, G., Szendrei, Z., Thomas, G.W.C., Torson, A.S., Vargas Jentzsch, I.M., Weirauch, M.T., Yates, A.D., Yocum, G.D., Yoon, J.-S., Richards, S., 2018. A model species for agricultural pest genomics: the genome of the Colorado potato beetle, Leptinotarsa decemlineata (Coleoptera: Chrysomelidae). Sci. Rep. 8, 1931.

Vizueta, J., Sánchez-Gracia, A., Rozas, J., 2020. bitacora: A comprehensive tool for the identification and annotation of gene families in genome assemblies. Mol. Ecol. Resour. 20, 1445–1452.

Zhao, Y.-J., Li, G.-C., Zhu, J.-Y., Liu, N.-Y., 2020. Genome-based analysis reveals a novel SNMP group of the Coleoptera and chemosensory receptors in Rhaphuma horsfieldi. Genomics 112:2713–2728.
