---
title: Firn & ice lens observations & implications within dense GPR grid
---

## Goal for the Week: Generate a hypothesis about ice lens (formation, distribution) in dense survey at Camp Recovery

### Main Questions

1. How are ice lenses distributed, and what drives this distribution?
2. How does the distribution vary given topography, accumulation, and any other microweather/microtopographic signals?
3. Can we use a machine learning algorithm to pick out ice lenses?
4. (How are ice lenses distributed relative to summer surfaces?)

To do this, we looked at two datasets collected by GEUS at Camp Recovery in 2018, as well as the output of MAR, a regional climate model. 

- [Target 5 Snow and Firn Core](/FirnGPRProjWNanna/Target5CoreDensity){: .internal-link} (density validation)
- [Target 5 Radar Grid ](/FirnGPRProjWNanna/radardata){: .internal-link}
- [MAR output](/FirnGPRProjWNanna/MAROutput){: .internal-link}

### Day 1
### Day 2
### Day 3
### Day 4
### Day 5

Today I looked at the ice percent of the cores available (Target 5, Targets 2 and 3, Camp, and Unknown Loc).

| Core Loc        | Ice Fraction |
|-----------------|--------------|
| Target 5        | 7%           |
| Targets 2 and 3 | 9%           |
| Camp            | 8%           |
| Unknown         | 17% /9%      |
The ice fraction percentages at the unkonwn core are much higher than the others. Partly, this is because there is a dense layer around 9.3m – an huge ice lens ~60cm thick! Without this ice lens, the %ice fraction is 9%, so more in line with the other cores. 

**Questions**
1. Does a few percent difference in ice fraction matter for water percolation, firn compaction, or satellite penetration? The next question is – is the depth variability in these ice lenses consistent? 
2. Are there some locations that have many thin lenses, and others that have just a few thick ones? 
3. Can we use these cores to track layer horizons in the radar?

![compareRadarLines.png](compareRadarLines.png)


We also compared radar data from the Main Survey and from Target 5. Target 5 lines were much shorter than the Main Survey lines, so fewer ice lenses would be expected, and the data is much more stretched out in the horizontal. However, **similarities** can be seen between the two radargrams. 
_white boxes_: Around 28-30ms (actually 280-300 ns, but had to adust to plot the data), we see similar patterns – two stacked layers, with broken up strong reflectors on top. These may be ice lenses that form on top of summer surfaces, related to [Qs 1, 2 and 4](#Main-Questions).

Some **differences** include:
- double layers around ~50 in 0196
- very distinct double layers between 45-50 and 55-60 in 0437

We looked at a long line of data (~3km) that connected Target 5 with the Main Survey. In this line (data forthcoming), accumulation is relatively low at target 5 (shallow summer surface) and high at the Main Survey (difference in depth = ~30%). Strong undulations are seen below 25-30 ms, a bright layer exists between 25-30 ms, and above undulations have largely disappeared. 

**Questions**
1. What causes the acccumulation difference?
2. Are undulations increasing with depth? Did the meltlayer somehow "cap" the layers below and prevent undulations?


