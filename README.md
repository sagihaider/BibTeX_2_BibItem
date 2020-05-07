# BibTeX_2_BibItem

Recenely, I wrote a manuscript, luckily, was accepted. The publisher wants the references to provided in '\bibitem' instead of BibTeX. So, I found a simple solution given as follows:

***

Clone the repository "https://github.com/sagihaider/BibTeX_2_BibItem.git" into the desired folder

*** 

Save your references list into a BibTex file name 'refs.bib'. Note: Best way of doing is to copy the bixtex files from GoogleScholar.

*** 

Open terminal on MAC and run command in step 2 and step 3

1. $ latex main
2. $ bibtex main

Now a new file name 'main.blb' will be create that contains your output

*** 
Example:

**Input**: 

@article{chowdhury2017online,
  title={Online covariate shift detection-based adaptive brain--computer interface to trigger hand exoskeleton feedback for neuro-rehabilitation},
  author={Chowdhury, Anirban and Raza, Haider and Meena, Yogesh Kumar and Dutta, Ashish and Prasad, Girijesh},
  journal={IEEE Transactions on Cognitive and Developmental Systems},
  volume={10},
  number={4},
  pages={1070--1080},
  year={2017},
  publisher={IEEE}
}


@article{rathee2019brain,
  title={Brain--Machine Interface-Driven Post-Stroke Upper-Limb Functional Recovery Correlates With Beta-Band Mediated Cortical Networks},
  author={Rathee, Dheeraj and Chowdhury, Anirban and Meena, Yogesh Kumar and Dutta, Ashish and McDonough, Suzanne and Prasad, Girijesh},
  journal={IEEE Transactions on Neural Systems and Rehabilitation Engineering},
  volume={27},
  number={5},
  pages={1020--1031},
  year={2019},
  publisher={IEEE}
}

@article{birbaumer2007brain,
  title={Brain--computer interfaces: communication and restoration of movement in paralysis},
  author={Birbaumer, Niels and Cohen, Leonardo G},
  journal={The Journal of physiology},
  volume={579},
  number={3},
  pages={621--636},
  year={2007},
  publisher={Wiley Online Library}
}

**Output**:

\begin{thebibliography}{1}

\bibitem{birbaumer2007brain}
Niels Birbaumer and Leonardo~G Cohen.
\newblock Brain--computer interfaces: communication and restoration of movement
  in paralysis.
\newblock {\em The Journal of physiology}, 579(3):621--636, 2007.

\bibitem{chowdhury2017online}
Anirban Chowdhury, Haider Raza, Yogesh~Kumar Meena, Ashish Dutta, and Girijesh
  Prasad.
\newblock Online covariate shift detection-based adaptive brain--computer
  interface to trigger hand exoskeleton feedback for neuro-rehabilitation.
\newblock {\em IEEE Transactions on Cognitive and Developmental Systems},
  10(4):1070--1080, 2017.

\bibitem{rathee2019brain}
Dheeraj Rathee, Anirban Chowdhury, Yogesh~Kumar Meena, Ashish Dutta, Suzanne
  McDonough, and Girijesh Prasad.
\newblock Brain--machine interface-driven post-stroke upper-limb functional
  recovery correlates with beta-band mediated cortical networks.
\newblock {\em IEEE Transactions on Neural Systems and Rehabilitation
  Engineering}, 27(5):1020--1031, 2019.

\end{thebibliography}

