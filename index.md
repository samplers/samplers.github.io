---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: post
# taxonomy: cnf
# toc: true
katex: True

---

The [Meelgroup](https://meelgroup.github.io/) research team has developed and currently maintains model counting tools that handle various input representations as detailed below.


| Name              | Input             | Type                  | Project Webpage                                       | Note      |
|:---:                |:---:                | :---:                   |:---:                                                    |:---:        | 
| `GANAK`           | CNF               | Exact Counter         | [Source](https://github.com/meelgroup/ganak/)         | Supports projected model counting |
| `ApproxMC`        | CNF               | Approximate Counter   | [Source](https://github.com/meelgroup/approxmc/)      | Supports projected model counting |
| `ApproxMC-PB`     | Pseudo-Boolean Formula    | Approximate Counter   | [Source](https://github.com/meelgroup/approxmcpb/)    | Supports projected model counting |
| `PBCount`         | Pseudo-Boolean Formula   | Exact Counter         | [Source](https://github.com/grab/pbcount)       |           |
| `CSB`             | SMT (bit vector)               | Approximate Counter   | [Source](https://github.com/meelgroup/csb/)           |          |
| `pepin`           | DNF               | Approximate Counter   | [Source](https://github.com/meelgroup/pepin/)         |            |
| `Arjun`           | CNF               | Preprocessor          | [Source](https://github.com/meelgroup/arjun/)         | Minimal independent set calculator and CNF minimizer          |
| `SkolemFC`        | QBF               | Approximate Counter    | [Source](https://github.com/meelgroup/skolemfc/)      |            |
| `weighted-to-unweighted` | Weighted CNF | Utility               | [Source](https://github.com/meelgroup/weighted-to-unweighted)      | Converts weighted CNF to unweighted CNF          |
| `ExactMC` | CNF | Exact Counter       | [Source](https://github.com/meelgroup/KCBox)      | Supports weighted model counting          |
| `Crane` | First Order Formula (Finite Domain) | Exact Counter       | [Source](https://github.com/dilkas/crane)      | Supports weighted model counting          |
| `AMUSIC` | CNF | Approximate Counter       | [Source](https://github.com/jar-ben/amusic)      | Counts minimal unsatisfiable subsets of CNF          |
{:.mbtablestyle}
<!-- 

# CNF Model Counters

## Ganak: 

[Project webpage](https://github.com/meelgroup/ganak/)

Supports projected model counting  

## ApproxMC: 
[Project webpage](https://github.com/meelgroup/approxmc/)

Supports projected model counters 

## 

# Pseudo-Boolean (PB) Model Counters

## ApproxMC-PB

[Project webpage](ttps://github.com/meelgroup/approxmcpb/)



## PBCount
[Project webpage] ()

# SMT Model Counters



# DNF Model Counters



# Pre-processors for Model Counting 

## Arjun
[Project webpage]()


# Useful utilities

Weighted to unweighted converter -->
