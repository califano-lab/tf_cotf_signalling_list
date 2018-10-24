# tf_cotf_signalling_list
The list of TFs, coTFs, signalling, surfaceMarkers, etc for ARACNe
UPDATES:


******************************
October 24, 2018

Heeju updated old gene symbols for mouse:

[tf_mus_symbol.txt]
Gm22 -> Zfp469
Taf4a -> Taf4
Whsc1 -> Nsd2
Zcchc16 -> Rtl4
Zcchc5 -> Rtl3
Zfp191 -> Zfp24
Znf512b -> Zfp512b

[cotf_mus_symbol.txt]
2210018M11Rik -> Emsy
2410016O06Rik -> Riox1
Ccdc101 -> Sgf29
Murc -> Cavin4
Ndnl2 -> Nsmce3
Ptrf -> Cavin1
Rqcd1 -> Cnot9
Setd8 -> Kmt5a
Suv420h1 -> Kmt5b
Suv420h2 -> Kmt5c
Tceb1 -> Eloc
Whsc1l1 -> Nsd3

The lists of Entrez IDs for mouse were updated based on Entrez Gene as of 2018-Apr-4.

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
