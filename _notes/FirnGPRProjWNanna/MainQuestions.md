---
title: Firn & ice lens observations & implications within dense GPR grid
---

_This project took place between September 21-25, 2020_. 

### Main Questions

1. How are ice lenses distributed, and what drives this distribution?
2. How does the distribution vary given topography, accumulation, and any other microweather/microtopographic signals?
3. Can we use a machine learning algorithm to pick out ice lenses?
4. (How are ice lenses distributed relative to summer surfaces?)

To do this, we looked at two datasets collected by GEUS at Camp Recovery in 2018, as well as the output of MAR, a regional climate model. 

- [Target 5 Snow and Firn Core](/FirnGPRProjWNanna/Target5CoreDensity){: .internal-link} (density validation)
- [Target 5 Radar Grid ](/FirnGPRProjWNanna/radardata){: .internal-link}
- [MAR output](/FirnGPRProjWNanna/MAROutput){: .internal-link}

### Resulting Hypotheses

We ended up straying from these questions a bit when forming the hypothesis. We ended up with a few hypotheses:

1. We can use the cores to trace internal layers and give some estimate in variability of porosity & the effect of this on satellite penetration depth
2. Under the same climate conditions, do low or high accumulation areas have more or less ice lenses? Do high accumulation areas have thicker ice lenses?
3. Summer surfaces can be so hardened that they prevent percolation deeper into the firn pack (protection) and provide a layer for ice lenses to form on – explains some vertical variability of ice lenses? Summer surfaces show continuous strong reflections, so this doesn't explain the lateral variability of ice lenses. The difficulty of identifying ice lenses in the radar data may prevent us from answering this question.

### Day 1

Today, I spent most of my time tagging layers in [OpendTect](https://www.dgbes.com/) and learning to use the software. See [Target 5 radar grid](/FirnGPRProjWNanna/radardata){: .internal-link} for the results of labor on Day 1. 

### Day 2

Today, we looked at the climate outputs of the regional atmospheric model, [MAR](/FirnGPRProjWNanna/MAROutput){: .internal-link}), and plotted the [firn core](/FirnGPRProjWNanna/Target5CoreDensity){: .internal-link} at Target 5.

### Day 3


### Day 4

More ice lens tagging today – lots of ice lenses in the Main Survey; extent is much longer than Target 5. Sadly this data was lost when OpendTect crashed.

### Day 5

Today I looked at the ice percent of the cores available (Target 5, Targets 2 and 3, Camp, and Unknown Loc).

| Core Loc        |  | Ice Fraction |
|-----------------|--|--------------|
| Target 5        |  | 7%           |
| Targets 2 and 3 |  | 9%           |
| Camp            |  | 8%           |
| Unknown         |  | 17% /9%      |

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
1. What causes the accumulation difference? Topo? Wind?
2. Are undulations increasing with depth? Did the meltlayer somehow "cap" the layers below and prevent undulations?


