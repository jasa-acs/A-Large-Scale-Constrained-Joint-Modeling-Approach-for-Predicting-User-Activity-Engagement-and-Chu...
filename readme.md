# A Large-Scale Constrained Joint Modeling Approach for Predicting User Activity, Engagement, and Churn With Application to Freemium Mobile Games

# Author Contributions Checklist Form

This README paraphrases some aspects of the complete checklist; for more detailed information, see ACC.pdf. 

The contents of this repo mirror the authors' own repo, found [here](https://github.com/trambakbanerjee/cezij).

## Data

## Abstract

Our primary data is a mobile app gaming data that holds daily player level gaming infor- mation for a free-to-play Robot versus Robot Fighting game based on the movie Real Steel for Windows, iOS and Android devices. The main game-play revolves around fighting and upgrading the robots while the secondary goals are to own as many robots as possible and collect rewards. A key feature of the game is a Lucky Draw which is a card game where players bet on their earnings to earn exciting in-app consumables, virtual currencies for robot upgrades or even robots! There are 38,860 players with first activity date 24-Oct-2014 and for each player, there are 29 variables, apart from the unique player identifier field, across the 60 time points. These variables have been described in table 6 of the supplementary materials. We also have side information about the different retention and promotion strategies that were used across the 60 days. Table 8 and figure 9 in the supplementary materials provide a summary of the 6 different promotion strategies that were used during the 60 days that the players were observed.

## Availability

The primary data is proprietary and not available publicly as the authors have signed a Non-Disclosure Agreement (NDA) with the data provider (henceforth referred to as client). The NDA prohibits the authors to disclose the client name and any level of aggregated /dis- aggregated data that can materially be used to identify players, their game patterns or any other strategies used by the client for marketing, sales or brand development. However, the authors have released a MATLAB implementation of the CEZIJ procedure in GitHub at https://github.com/trambakbanerjee/cezij#what-is-cezij. This repository stores the imple- mentation of the CEZIJ procedure and allows users to test the method on a pseudo data set with similar contents but with the variables holding simulated data rather than the actual observed values. A description of the pseudo data is available below while further details on the pseudo data, instructions to create such data and reproduce setting I of the numerical experiment of section C.2 of the supplementary material is available in cezij help.pdf at the GitHub public repository https://github.com/trambakbanerjee/cezij.

## Code 

### Abstract

The authors have released a MATLAB implementation of the CEZIJ procedure in GitHub at https://github.com/trambakbanerjee/cezij#what-is-cezij. To install this toolbox, simply download cezij.mltbx (available at https://github.com/trambakbanerjee/cezij) in your computer and double click to install it. For a successful installation, please make sure that the following system requirements are met.

* Access to 32GB RAM and at least 8 CPU cores for parallel computing 3
* MATLAB 2016b or higher with the following toolboxes (and their dependencies):
  * Statistics toolbox
  * Optimization toolbox
  * Parallel Computing toolbox – Data Acquisition toolbox
* CVX for MATLAB (version 2.1 or higher)

For detailed descriptions of the code, see ACC.pdf

## Instructions for Use

To install the cezij MATLAB toolbox, simply download cezij.mltbx (available at https: //github.com/trambakbanerjee/cezij) in your computer and double click to install it. For a successful installation, please ensure that your system meets the minimum hardware and software requirements listed in the Code section of this form. Alternatively, see section 2 of cezij help.pdf(https://github.com/trambakbanerjee/cezij).

### Reproducibility

To start using the toolbox, run cezij simulation.m to reproduce the results of simulation experiment I discussed in section C.2 of the supplementary material. For using a different simulation setting or a different dataset altogether, please refer to section 3 of cezij help.pdf.
