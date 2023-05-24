Condorcet Voting Open Source Ecosystem Map
=========================================
A detailed index of free _(open-source)_ software around preferential voting.  

**Rules:** The entries must be significant, free, and documented. They must be currently maintained, tested, and must have received a minimum of recognition for their seriousness and reliability.  

**_Pull request welcome!_**

## Formats & Standards
  #### [Condorcet Election Format](https://github.com/CondorcetVote/CondorcetElectionFormat)
  > Specification of a free format, representing an Election an her data (parameters, candidates, votes). The objective of this format is to be easily written and read by a human, with the rigor and precision necessary for ingestion by a program.
  
  
## Command-line applications
  #### [Condorcet](https://github.com/julien-boudry/Condorcet)
  > *Documentation:* [www.condorcet.io](https://www.condorcet.io)  
  > *Main technologies:* PHP 8  
  > *Methods:* ```Condorcet / Borda (+ Nauru variant) / Copeland / Dodgson (2 Approximations) / FTPT / Instant-runoff (alternative vote) / Kemeny–Young / Minimax (+ variants) / Ranked Pairs (+ variants) / Schulze (+ variants) / Single Transferable Vote (STV) / Comparison of Pairs of Outcomes by the Single Transferable Vote (CPO-STV) / Highest Averages Methods (Sainte-Laguë, Jefferson/D'Hondt, and variants) / Largest Remainder Methods (with different quotas)```  
  >
  > Command line interface including an interactive mode, complete statistics and the management of huge elections on a modest hardware. Various installation method including Docker, Github codespace or PHP (Phar, Composer).
  
  #### [Debian Devotee](https://salsa.debian.org/debian/devotee)
  > *Main technologies:* Perl  
  > *Methods:* ```Schulze```
  >
  > Official voting system processor of the Linux Debian project.
  
  



## Web GUI application
  #### [Belenios](https://github.com/glondu/belenios/)
  > *Methods:* ```Schulze / STV ```  
  > *Main technologies:* OCaml  
  > *Online version*: [vote.belenios.org/admin](https://vote.belenios.org/admin)  

  #### [Condorcet.Vote](https://github.com/julien-boudry/Condorcet.Vote)
  > *Methods:* ```Condorcet / Schulze (+ variants) / Kemeny-Young / Ranked Pairs (+ variants) / Minmax (+variants) / Borda / FTPT / Copeland / Dodgson / Dowdall / Instant-Runoff (alternative vote)```  
  > *Main technologies:* PHP / Mysql / Docker  
  > *Online version*: [www.condorcet.vote](https://www.condorcet.vote)  
  >
  > An open-source demo for a web ovting application based on [Condorcet](#condorcet-1) as backend.

  #### [Condorcet Internet Voting System (Civs)](https://github.com/andrewcmyers/civs)
  > *Main technologies:* Perl  
  > *Online version*: [civs1.civs.us](https://civs1.civs.us/).

  #### [Pollen](https://gitlab.nuiton.org/chorem/pollen)
  > *Methods:* ```Cumulative / Condorcet / Borda / Instant-Runoff (alternative vote) / Coombs / Majority judgment / FTPT```  
  > *Main technologies:* Java  
  > *Online version*: [pollen.cl](https://pollen.cl/)  

## Software Components (libraries)
### PHP
  #### [Condorcet](https://github.com/julien-boudry/Condorcet)
  > *Documentation:* [www.condorcet.io](https://www.condorcet.io)  
  > *Methods:* ```Condorcet / Borda (+ Nauru variant) / Copeland / Dodgson (2 Approximations) / FTPT / Instant-runoff (alternative vote) / Kemeny–Young / Minimax (+ variants) / Ranked Pairs (+ variants) / Schulze (+ variants) / Single Transferable Vote (STV) / Comparison of Pairs of Outcomes by the Single Transferable Vote (CPO-STV) / Highest Averages Methods (Sainte-Laguë, Jefferson/D'Hondt, and variants) / Largest Remainder Methods (with different quotas)```  
  >
  > Condorcet PHP provides an election engine with a high-level interface to manage all aspects of an election and to run simulations. It's supporting many input methods and various tools & helpers.
  > The modular architecture is easy to extend. It supports simple elections with ease or billions of votes in low resource environment.
  > Condorcet is intensively tested (1500+ tests), documented, and highly polyvalent. 
  
  #### [Pivot-Libre: Tideman](https://github.com/pivot-libre/tideman)
  > *Methods:* ```Ranked Pairs```

### PERL
  #### [PrefVote](https://github.com/ikluft/prefvote)
  > *Methods:* ```Condorcet / Schulze / Ranked Pairs / STV```
### RUST
### Ruby
  #### [Vote-Schulze](https://github.com/asaaki/vote-schulze)
  > *Methods:* ```Schulze```
### Python
### Javascript / Typescript
### C / C++
### Java


## Software GUI applications
*To fill*
