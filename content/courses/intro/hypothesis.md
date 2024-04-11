---
title: Hypothesis Testing
linktitle: Hypothesis Testing
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: true
menu:
  intro:
    parent: Workshop
    weight: 5

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 5

# url_code = "#"
# url_dataset = "#"
# url_project = "#"
# url_slides = "#"
# url_video = "#"

---

## Network Theory – Network variables as explanatory variables
- Networks cause some outcome
- Where a node is positioned impacts what the node does/is influenced by.
- Diffusion of Innovations
- Peer Influence
- Disease transmission
  
## Theory of networks – Network variables as outcome variables
- Attributes cause how a network forms or is maintained
- What attributes impact how a node connects with others in the group
- Social Integration / Selection
- Popularity or structuration

## Descriptive
- Centrality
- Communities
- Composition of networks
- Structural holes
- Triad Census

## Permutation Testing
- Many network analyses use permutation testing or the use of simulated data to test for statistical significance
- Used to properly manage the interdependent nature of social network data 


## Quadratic Assignment Procedure
- Uses matrix math to determine significant associations between matrices
- Reshapes the matrix and conducts associations such as correlation or regression
- The dispersion of a variable throughout the network is significantly associated with the social structure. 
- Example: Are “Played with” and “Friends with” networks significantly associated. 

## Linear Network Autocorrelation Models
- Determine the network effects or spatial autocorrelation of a variable within the network while controlling for other variables
- Determine the associations between variables while controlling for network effects
- Example: MVPA = Self-efficacy+age+Sex+network effects
  - Network effects – the level of association between ego’s MVPA and the MVPA of their connections.

## Exponential Random Graph Modeling
- Determines significant factors associated with tie presence within the network.
- Example: NETWORK= nodefactor(sex) +nodematch(age) +nodecov(MVPA)
  - Are ties significantly more likely in females?
  - Are ties significantly more likely between individuals with the same age?
  - Are ties significantly more likely among individuals with more MVPA?

## Stochastic Actor Oriented Modeling 
- Blend of LNAM and ERGM – determine significant predictors of tie formation/dissolvement and attribute change over time.
- Model significant associations in the manner by which nodes are influenced over time by modeling both network and individual level effects. 
- Longitudinal
- Example: MVPA – do adolescents become more like friends or make friends with those who are similar over time?

## HLM / MLM
- Used in Egocentric analysis
- Determine significant associations between attributes and network composition 
- Determine unique variance explained by network level factors 
- Example – Skill Competency = Age+Sex+MVPA+(# of network members who are active)+ (Structural holes)+(# of network members who help ego be active)

## Software (Analysis)
- SPSS – MLM/HLM *
- UCINET – QAP *
- R – Everything *
- SAS, STATA – Everything
- E-net – Egocentric
- Other applications: Gephi, Pajek, NodeXL

(*) indicates those applications used by Tyler and Megan most often
