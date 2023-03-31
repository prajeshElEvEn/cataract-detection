# Cataract Detection

This model detects cataract in the eye with an input image and outputs into `name`, `category`,`type`, `grade`.

## To Do

- [x] Read Research Paper
- [ ] design model

## The Problem Description

The labels of this dataset consists of 3 categories, 5 types and 5 grades. It can be 75 multi-labels.

- Category
  - category 0 : point-like corneal ulcers
  - category 1 : point-flaky mixed corneal ulcers
  - category 2 : flaky corneal ulcers
- Types
  - type 0 : No ulcer of the corneal epithelium
  - type 1 : Micro punctuate
  - type 2 : Macro punctuate
  - type 3 : Coalescent macro punctuate
  - type 4 : Patch (>=1 mm)
- Grade
  - grade 0 : No ulcer of the corneal epithelium
  - grade 1 : Corneal ulcers involve only one surrounding quadrant
  - grade 2 : Corneal ulcers involve two surrounding quadrants
  - grade 3 : Corneal ulcers involve three or four surrounding quadrants
  - grade 4 : Corneal ulcers involve the central optical zone of the cornea

## Research

- Multi-label classification: One image can have multiple labels.
- Multi-class classification: One label can have multiple classes.
- Our Model is supposed to be a multi-label multi-class classification model.

## Important Links

- [Dataset](https://drive.google.com/file/d/1y7wpvjf9iF3l2u_epeprl6hQFcfMvH5O/view)
- [Reference Research Paper](https://docs.google.com/document/d/1egDPb-jWgF-L2aUtvdnQ4rqhGasHPn1g/edit?usp=sharing&ouid=107528819754080768862&rtpof=true&sd=true)

## Models

- [model_one.h5](https://youtu.be/jztwpsIzEGc)
- [model_two.h5](https://youtu.be/hraKTseOuJA)

## Reference

[Nicholas Renotte](https://youtu.be/jztwpsIzEGc)
