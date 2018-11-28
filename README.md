# tf_cotf_signalling_list
The list of TFs, coTFs, signalling, surfaceMarkers, etc for ARACNe
UPDATES:

******************************
November 28, 2018

ZIC4 and FIGLA regulators are not present in our human or mouse tf list. These may have to be added.

******************************
November 01, 2018

Added TF: Brd4

Added coTF: Nf1

Files changed: 
mouse TF and coTF gene-symbol-files

Files not updated: 
mouse TF and coTF gene-EntrezID-files and human files


******************************
October 26, 2018

old_lists folder has been created that contains the lists from lab members and shared folders.


******************************
October 24, 2018

Heeju updated old gene symbols for mouse:

[tf_mus_symbol.txt]

Gm22, Taf4a, Whsc1, Zcchc16, Zcchc5, Zfp191, Znf512b   to   Zfp469, Taf4, Nsd2, Rtl4, Rtl3, Zfp24, Zfp512b


[cotf_mus_symbol.txt]

2210018M11Rik, 2410016O06Rik, Ccdc101, Murc, Ndnl2, Ptrf, Rqcd1, Setd8, Suv420h1, Suv420h2, Tceb1, Whsc1l1   to   Emsy, Riox1, Sgf29, Cavin4, Nsmce3, Cavin1, Cnot9, Kmt5a, Kmt5b, Kmt5c, Eloc, Nsd3


The lists of Entrez IDs for mouse were updated based on Entrez Gene as of 2018-Apr-4.
[tf_mus_Entrez.txt]
TFs removed.
19989: Rpl7
68611: Mrpl28

Not changed:
Mouse coTF gene-EntrezID-files not updated.
Human files not changed.
******************************
October 24, 2018

Ajay removed the following genes from TF and coTF 'symbol' lists for mouse symbols because they are ribosomal genes and not know to have any transcriptional regulatory function. 

Removed TFs:
Rpl7
Mrpl28

Removed coTFs:
Rpl6
Rpl7l1
Rps14
Rps3
Rps6ka4
Rps6ka5
Mrpl12

Added coTFs: Yap1

Changed Files:
The corresponding mouse TF and coTF gene-symbol-files have been changed. 

Not changed:
The mouse TF and coTF gene-EntrezID-files have not been updated.
The human files have not been changed.

******************************
October 19, 2018

These lists were initially created by Ding for scRNAseq:
https://github.com/califano-lab/single-cell-pipeline/tree/master/Modules/ARACNe

Transcriptional Factors:
GO:0003700, ìtranscription factor activityî
GO:0003677, ìDNA bindingî
GO:0030528, ìtranscription regulator activityî
GO:00034677 and GO:0045449, ìregulation of transcriptionî

Transcriptional Co-Factors (manually curated, not overlapping with Transcriptional Factors list):
GO:0003712, GO:0030528 or GO:0045449, ìtranscription cofactor activityî

Surface Proteins (manually curated, not overlapping with Transcriptional Factors/Co-Factors list):
GO:0005886, plasma membrane
