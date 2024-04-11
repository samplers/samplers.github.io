---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: post
# taxonomy: cnf
# toc: true
katex: True

---

The [Meelgroup](https://meelgroup.github.io/) research team has developed and currently maintains model counting tools that handle various input representations as detailed below.


<!-- | Name              | Input             | Type                  | Project Webpage                                       | Note      |
|:---:                |:---:                | :---:                   |:---:                                                    |:---:        | 
| [<span class="special-font">Arjun</span>](https://github.com/meelgroup/arjun/)           | CNF               | Preprocessor          | [Source](https://github.com/meelgroup/arjun/)         | Minimal independent set calculator and CNF minimizer          |
| [<span class="special-font">ApproxMC</span>](https://github.com/meelgroup/approxmc/)        | CNF               | Approximate Counter   | [Source](https://github.com/meelgroup/approxmc/)      | Supports projected model counting |
| [<span class="special-font">ExactMC</span>](https://github.com/meelgroup/KCBox) | CNF | Exact Counter       | [Source](https://github.com/meelgroup/KCBox)      | Supports weighted model counting          |
| [<span class="special-font">GANAK</span>](https://github.com/meelgroup/ganak/)           | CNF               | Exact Counter         | [Source](https://github.com/meelgroup/ganak/)         | Supports projected model counting |
| [<span class="special-font">PBCount</span>](https://github.com/grab/pbcount)         | Pseudo-Boolean Formula   | Exact Counter         | [Source](https://github.com/grab/pbcount)       |           |
| [<span class="special-font">ApproxMC-PB</span>](https://github.com/meelgroup/approxmcpb/)     | Pseudo-Boolean Formula    | Approximate Counter   | [Source](https://github.com/meelgroup/approxmcpb/)    | Supports projected model counting |
| [<span class="special-font">pepin</span>](https://github.com/meelgroup/pepin/)           | DNF               | Approximate Counter   | [Source](https://github.com/meelgroup/pepin/)         |            |
| [<span class="special-font">Crane</span>](https://github.com/dilkas/crane) | First Order Formula (Finite Domain) | Exact Counter       | [Source](https://github.com/dilkas/crane)      | Supports weighted model counting          |
| [<span class="special-font">CSB</span>](https://github.com/meelgroup/csb/)             | SMT (bit vector)               | Approximate Counter   | [Source](https://github.com/meelgroup/csb/)           |          |
| [<span class="special-font">SkolemFC</span>](https://github.com/meelgroup/skolemfc/)        | QBF               | Approximate Counter    | [Source](https://github.com/meelgroup/skolemfc/)      |  Counts number of Skolem functions |
| [<span class="special-font">AMUSIC</span>](https://github.com/jar-ben/amusic) | CNF | Approximate MUS Counter       | [Source](https://github.com/jar-ben/amusic)      | Counts minimal unsatisfiable subsets of CNF          |
| [<span class="special-font">weighted-to-unweighted</span>](https://github.com/meelgroup/weighted-to-unweighted) | Weighted CNF | Utility               | [Source](https://github.com/meelgroup/weighted-to-unweighted)      | Converts weighted CNF to unweighted CNF          |
{:.mbtablestyle} -->


<table class="mbtablestyle">
  <thead>
    <tr>
      <th style="text-align: center">Name</th>
      <th style="text-align: center">Input</th>
      <th style="text-align: center">Type</th>
      <th style="text-align: center">Project Webpage</th>
      <th style="text-align: center">Note</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/arjun/"><span class="special-font">Arjun</span></a></td>
      <td style="text-align: center">CNF</td>
      <td style="text-align: center">Preprocessor</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/arjun/">Source</a></td>
      <td style="text-align: center">Minimal independent set calculator and CNF minimizer</td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/approxmc/"><span class="special-font">ApproxMC</span></a></td>
      <td style="text-align: center">CNF</td>
      <td style="text-align: center">Approximate Counter</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/approxmc/">Source</a></td>
      <td style="text-align: center">Supports projected model counting</td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/KCBox"><span class="special-font">ExactMC</span></a></td>
      <td style="text-align: center">CNF</td>
      <td style="text-align: center">Exact Counter</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/KCBox">Source</a></td>
      <td style="text-align: center">Supports weighted model counting</td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/ganak/"><span class="special-font">GANAK</span></a></td>
      <td style="text-align: center">CNF</td>
      <td style="text-align: center">Exact Counter</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/ganak/">Source</a></td>
      <td style="text-align: center">Supports projected model counting</td>
    </tr>
    <tr class="reduced-row"></tr>
    <tr class="reduced-row"></tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/grab/pbcount"><span class="special-font">PBCount</span></a></td>
      <td style="text-align: center">Pseudo-Boolean Formula</td>
      <td style="text-align: center">Exact Counter</td>
      <td style="text-align: center"><a href="https://github.com/grab/pbcount">Source</a></td>
      <td style="text-align: center"> </td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/approxmcpb/"><span class="special-font">ApproxMC-PB</span></a></td>
      <td style="text-align: center">Pseudo-Boolean Formula</td>
      <td style="text-align: center">Approximate Counter</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/approxmcpb/">Source</a></td>
      <td style="text-align: center">Supports projected model counting</td>
    </tr>
    <tr class="reduced-row"></tr>
    <tr class="reduced-row"></tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/pepin/"><span class="special-font">pepin</span></a></td>
      <td style="text-align: center">DNF</td>
      <td style="text-align: center">Approximate Counter</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/pepin/">Source</a></td>
      <td style="text-align: center"> </td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/dilkas/crane"><span class="special-font">Crane</span></a></td>
      <td style="text-align: center">First Order Formula (Finite Domain)</td>
      <td style="text-align: center">Exact Counter</td>
      <td style="text-align: center"><a href="https://github.com/dilkas/crane">Source</a></td>
      <td style="text-align: center">Supports weighted model counting</td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/csb/"><span class="special-font">CSB</span></a></td>
      <td style="text-align: center">SMT (bit vector)</td>
      <td style="text-align: center">Approximate Counter</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/csb/">Source</a></td>
      <td style="text-align: center"> </td>
    </tr>
    <tr class="reduced-row"></tr>
    <tr class="reduced-row"></tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/skolemfc/"><span class="special-font">SkolemFC</span></a></td>
      <td style="text-align: center">QBF</td>
      <td style="text-align: center">Approximate Skolem function Counter</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/skolemfc/">Source</a></td>
      <td style="text-align: center">Counts number of Skolem functions</td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/jar-ben/amusic"><span class="special-font">AMUSIC</span></a></td>
      <td style="text-align: center">CNF</td>
      <td style="text-align: center">Approximate MUS Counter</td>
      <td style="text-align: center"><a href="https://github.com/jar-ben/amusic">Source</a></td>
      <td style="text-align: center">Counts minimal unsatisfiable subsets of CNF</td>
    </tr>
    <tr>
      <td style="text-align: center"><a href="https://github.com/meelgroup/weighted-to-unweighted"><span class="special-font">weighted-to-unweighted</span></a></td>
      <td style="text-align: center">Weighted CNF</td>
      <td style="text-align: center">Utility</td>
      <td style="text-align: center"><a href="https://github.com/meelgroup/weighted-to-unweighted">Source</a></td>
      <td style="text-align: center">Converts weighted CNF to unweighted CNF</td>
    </tr>
  </tbody>
</table>
