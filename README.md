# PlasmodiumMuSiC
OUt_pyr: dans ce fichier nous avons les différents sorti de AlphaFold Dhfr-pyrimethamine 
c'est différents fichier on été modifier par des scripte afin d'obttenir le format Prempli ( avoir un Header et un format du liG spécifique voir ci dessous)
Header :
HET    LIG  A  609
HETNAM     LIG   
ATOM      1  N   MET A   1      31.407  26.246   2.881  1.00 60.24           N  
ATOM      2  CA  MET A   1      31.171  26.296   1.423  1.00 66.56           C  
ATOM      3  C   MET A   1      30.315  27.513   1.142

Partie Ligand:
TER    5048      ALA A 608                                                       
HETATM 5049  C1  LIG A 609       1.858  25.673 -20.230  1.00 89.17           C  
HETATM 5050  C2  LIG A 609       3.157  25.550 -20.981  1.00 94.25           C  
HETATM 5051  C3  LIG A 609       4.301  25.316 -20.055  1.00 97.04           C  
HETATM 5052  C4  LIG A 609       5.320  26.254 -19.857  1.00 97.38           C  
HETATM 5053  C5  LIG A 609       6.408  25.875 -19.012  1.00 97.27           C  
HETATM 5054  N1  LIG A 609       6.398  24.679 -18.413  1.00 97.32           N  
HETATM 5055  C6  LIG A 609       5.377  23.825 -18.623  1.00 97.62           C  
HETATM 5056  N2  LIG A 609       4.338  24.123 -19.431  1.00 96.57           N  
HETATM 5057  N3  LIG A 609       5.380  22.615 -18.019  1.00 96.00           N  
HETATM 5058  N4  LIG A 609       7.455  26.713 -18.803  1.00 96.01           N  
HETATM 5059  C7  LIG A 609       5.306  27.595 -20.454  1.00 96.72           C  
HETATM 5060  C8  LIG A 609       6.212  27.929 -21.447  1.00 91.30           C  
HETATM 5061  C9  LIG A 609       6.229  29.196 -21.957  1.00 91.22           C  
HETATM 5062  C10 LIG A 609       5.331  30.151 -21.509  1.00 94.93           C  
HETATM 5063  C11 LIG A 609       4.416  29.827 -20.532  1.00 90.88           C  
HETATM 5064  C12 LIG A 609       4.399  28.541 -20.018  1.00 91.22           C  
HETATM 5065 CL1  LIG A 609       5.384  31.769 -22.179  1.00 93.06          CL  
TER    5066      LIG A 609                                                       
END
OUT_cyclo: dans ce fichier nous avons les résultats de Alphafold Dhfr_cyclo (avec les même spécificité que le fichier OUT_Pyr)
> pour les différents modél obtenue avec alphafold on a calculé le RMS entre les différents model :
> pour DHFR_PYR: le Model4 est le model proposer par AlphaFold
MODEL0/MODEL1
Executive: RMSD =    0.113 (486 to 486 atoms)
MODEL0/MODEL2
RMSD =    0.104 (463 to 463 atoms)
MODEL0/MODEL3
RMSD =    0.090 (470 to 470 atoms)
MODEL0/MODEL4
RMSD =    0.128 (469 to 469 atoms)
MODEL1/MODEL2
RMSD =    0.123 (494 to 494 atoms)
MODEL1/MODEL3
RMSD =    0.100 (489 to 489 atoms)
MODEL1/MODEL4
RMSD =    0.138 (491 to 491 atoms)
MODEL2/MODEL3
 RMSD =    0.092 (474 to 474 atoms)
MODEL2/MODEL4
RMSD =    0.128 (473 to 473 atoms)
MODEL3/MODEL4
RMSD =    0.141 (483 to 483 atoms)
> Pour DHFR_cyclo : le Model4 est le model proposer par AlphaFold
MODEL0/MODEL1
RMSD =    0.111 (482 to 482 atoms)
MODEL0/MODEL2
RMSD =    0.105 (464 to 464 atoms)
MODEL0/MODEL3
 RMSD =    0.090 (469 to 469 atoms)
MODEL0/MODEL4
RMSD =    0.129 (471 to 471 atoms)
MODEL1/MODEL2
RMSD =    0.123 (494 to 494 atoms)
MODEL1/MODEL3
 RMSD =    0.100 (489 to 489 atoms)
MODEL1/MODEL4
RMSD =    0.137 (490 to 490 atoms)
MODEL2/MODEL3
RMSD =    0.091 (472 to 472 atoms)
MODEL2/MODEL4
 RMSD =    0.131 (476 to 476 atoms)
MODEL3/MODEL4
RMSD =    0.143 (486 to 486 atoms)

