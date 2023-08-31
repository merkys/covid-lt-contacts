## Contents

This repository contains protein complex structures containing SARS-CoV-2 spike protein as well as derived data.

Important files:

* `pdb/ACE2/complexes/*.pdb` – SARS-CoV-2 complexes with ACE2 protein

  * `pdb/ACE2/complexes/clusters/clusters.lst` – file listing clusters based on contacts (epitopes), one cluster per line;
  * `pdb/ACE2/complexes/clusters/contacts-..tab` – TSV file listing averaged contact distances for each of the clusters (columns); lines correspond to aminoacid positions in SARS-CoV-2 spike glycoprotein; question marks (`?`) mark absent contacts for the position in question;
  * `pdb/ACE2/complexes/contact-maps/distances/..tab` – TSV file listing all complexes (columns) and their contacts (lines); lines correspond to aminoacid positions in SARS-CoV-2 spike glycoprotein; question marks (`?`) mark absent contacts for the position in question;
  * `pdb/ACE2/complexes/dist-matrices/contact.m` – distance matrix between complexes;

* `pdb/antibodies/complexes/*.pdb` – SARS-CoV-2 complexes with antibodies

  * `pdb/antibodies/complexes/clusters/clusters.lst` – file listing clusters based on contacts (epitopes), one cluster per line;
  * `pdb/antibodies/complexes/clusters/contacts-..tab` – TSV file listing averaged contact distances for each of the clusters (columns); lines correspond to aminoacid positions in SARS-CoV-2 spike glycoprotein; question marks (`?`) mark absent contacts for the position in question;
  * `pdb/antibodies/complexes/contact-maps/distances/..tab` – TSV file listing all complexes (columns) and their contacts (lines); lines correspond to aminoacid positions in SARS-CoV-2 spike glycoprotein; question marks (`?`) mark absent contacts for the position in question;
  * `pdb/antibodies/complexes/dist-matrices/contact.m` – distance matrix between complexes;

* `pdb/pristine/*.pdb` – original PDB files as downloaded from the Protein DataBank

## Acknowledgments

This project has received funding from European Regional Development Fund (project No 13.1.1-LMT-K-718-05-0023) under grant agreement with the Research Council of Lithuania (LMTLT). Funded as European Union's measure in response to Cov-19 pandemic.
