# P300_Speller_VBH_2021

The P300 speller BCI system consisted of electroencephalography acquisition connected to real-time processing software and separate keyboard-display control software. It was first described by Sutton et al.( 1965 ) and has been widely studied since then to explore higher cortical functions in humans (for review see Bashore & Van der Molen, 1991; Donchin, 1981; Duncan et al., 2009; Fabiani et al., 1987; Polich, 2007; Pritchard, 1981 ). Although it often occurs at a latency of about 300 ms relative to the eliciting stimulus (hence the designation of P300), its latency may vary from 250 to 750 ms (Comerchero & Polich, 1999 ; Maglieroet al., 1984; McCarthy & Donchin, 1981; Polich, 2007 ). This variability in latency reflects the fact that the P300 is elicited by the decision, not necessarily conscious, that a rare event has occurred, and the decision latency can and does, vary with the nature (e.g., the difficulty) of the decision (Kutas et al., 1977 ).
The P300 is usually largest over the central parietal scalp and attenuates gradually as the distance from this area increases.

<p align="center">
  <cite>
    @credit: Xiaogang Chen et al./PNAS
  </cite>
  <img width="700" height="350" src="https://www.kurzweilai.net/images/SSVEP-based-BCI-speller.jpg">
</p>

A visual paradigm based P300 speller system consists of several stages:

- Stimulating a subject by presenting a P300 processing;
- Feature extraction; 
- Classification.

During the Hackathon we faced a problem with two different paradigms used to implement the P300 speller: (i) the row/column (RC) speller highlights multiple characters at once and (ii) the single character (SC) speller flashes each character individually (see "How many people are able to control a P300-based brain-computer interface (BCI)?" by Christoph Guger et al. for more details).

We started with 5 matrix of raw data from 5 different patients. Each matrix had a dimension of: 60000 rows and 8 columns (one column for each channel). 
In each folder there are the codes of the two groups that participated in the solution of the problem.
