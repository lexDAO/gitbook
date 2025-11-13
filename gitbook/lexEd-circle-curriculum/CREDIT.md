Anderson R., _Security Engineering_ [ISBN 978-1119642787
](https://www.cl.cam.ac.uk/archive/rja14/Papers/SEv3.pdf)

```mermaid
---
title: Anderson (2020) Security Engineering (3rd ed)
---
flowchart TB
00[_Preface]
01[SecEng]
02[Threat]

subgraph Design [Design Thinking]
  direction LR
03[Psych]
04[Protocol]
05[Primitives]
03 -...- 04
03 -...- 05

subgraph Considerations
  direction LR
06[Access]
07[Partition]
08[Economics]
end

04 -.-> Considerations
05 -.-> Considerations
end

subgraph Principles [Design Principles]
  direction LR
09[SecEng-Multilevel]
10[SecEng-Multilayer]
11[SecEng:Multiparty]

09 -.-x 10 -.-x 11 -.-x 09
end
Considerations -.-> Principles

subgraph Domains
  direction LR
12[Banking]
13[SecEng-NoFly]
14[SecEng-NoSpy]
16[SecEng-NoLie]
15[Military_C3]
end

subgraph SecOps
  direction LR
17[SecEng-Authentication]
18[Tamper Resistant]
19[Side Channels]
end

subgraph Examples
  direction LR
20[Examples]
20.1[Disk encryption]
20.2[Signal Protocol]
20.3[Tor Protocol]
20.4[HSM]
20.5[Enclaves]
20.6[Blockchain]
20 ---> 20.1
20 ---> 20.2
20 ---> 20.3
20 ---> 20.4
20 ---> 20.5
20 ---> 20.6
end

21[Network]
22[Device-Phone]

subgraph Sample[Threat Samples]
  direction LR
23[Threat-InfoWar]
24[Threat-Infringement]
25[Threat]
25.1[Threat-Autonomy]
25.2[Threat-AI/ML]
25.3[Threat-Doxing]
25.4[Threat-Rigging]
26[Threat-Panopticon]
end
21 ---> 25

subgraph Operations
  direction LR
27[SecEng-DevOps]
28[SecEng-Assurance]
2x[SecEng-Compliance]
29[SecEng-Sustainability]
2y[SecEng-KillSwitch]
28 -.- 2x
29 -.- 2y
end

30[Biography]

00 -.-> 01
01 --> 02
02 ==> 03
Design ---> Principles ---> 12
Domains ===> SecOps ---> 20
Examples ---> 21
Examples ---> 22

Sample ===> Operations
Operations ---> 30
```

Lessig L., _Code 2.0_ [ISBN 978-0465039142](https://upload.wikimedia.org/wikipedia/commons/f/fd/Code_v2.pdf)

Leveson N.G., _Engineering for a Safer World_ [ISBN 978-0262533690](http://sunnyday.mit.edu/safer-world.pdf)

# Reference

🇺🇸 Opensource Casebook, [link](https://opensourceproperty.org/download/) 

Raymond E.S., The Jargon File, [link](http://www.catb.org/esr/jargon/html/index.html) (v4.4.7)

Systems Engineerng Book of Knowledge (v 2.12), [link](https://sebokwiki.org/wiki/Guide_to_the_Systems_Engineering_Body_of_Knowledge_(SEBoK))

![map](https://sebokwiki.org/w/images/f/fd/WoYFSO.png)

Stanford Encyclopedia of Philosophy, [link](https://plato.stanford.edu/contents.html)

# Tools

cadCAD - macroeconomic modelling of tokenomics

OpenFISCA - mesoeconomic modelling of fiscal policy

machiNations - microeconomic simulation of game microtransactions

![OpenFISCA](https://github.com/digitalaotearoa/rac-guide/blob/gh-pages/rac-architecture.png?raw=true)

# Optional

🇨🇦 Zariskic A. (2014) _Legal Literacy_ [ISBN 978-1927356456]()

```mermaid
mindmap
  root[literacy]
    1[knowledge acquistion]
      1.1[consciousness]
      1.2[rights]
      1.3[obligations]
    2[reasoned judgement]
      2.1[dialectic]
      2.2[socialisation]
      2.3[decision]
    3[legal procedure]
      3.1[mobilisation]
      3.2[institutions]
      3.3[resources]
```

Voshmgir S., _Token Economy_ (3rd ed) [ISBN 978-9899157163](https://github.com/Token-Economy-Book)

