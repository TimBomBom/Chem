
---



# Choice of Acid

Having attempted HCl + H<sub>2</sub>O<sub>2</sub>, it seems that mostly Iron was dissolved instead of copper (see [[Chalcopyrite Project/Old Procedure|Old Procedure]]). It is possible that some dissolved, but it seemed to be nearly entirely iron due to the strong green colour (though it is difficult to tell due to the variable colour of copper chlorides. See Table 1). It is possible that *some* copper was dissolved, but I believe that it was a negligible amount. It is likely that the A-P mixture was used in dissolving and oxidizing the iron into Fe<sup>3+</sup> ions, leaving little peroxide to oxidize the copper. 

>[!note] 
>Sulfuric acid is also unable to oxidize copper. [[Safety Considerations#- H<sub>2</sub>O<sub>2</sub> (3%)|Peroxide]] or some other oxidizer is still needed for this method. Perhaps consider aeration.


Although sulfuric acid is also unable to dissolve copper on its own, the extraction of CuSO<sub>4</sub> is much easier as: CuCl is very soluble in HCl, CuCl<sub>2</sub> is generally ~twice as soluble as CuSO<sub>4</sub>, and visually it is hard to distinguish from chlorides of iron. 

Furthermore, the chlorides of Cu and Fe are not only quite soluble in general  which would make crystallization difficult, their solubilities are too similar to each other to get good separation in fractional crystallization (Table 1). The sulfates, however, have different enough solubilities and are distinguishable enough in colour (both as a solution and in their crystalline forms) that separating the two should be relatively easier than with their chlorides.


|                  Compound                  | Solubility (g/100mL @0°C) |             Colour              |
| :----------------------------------------: | :-----------------------: | :-----------------------------: |
|     <center>FeCl<sub>2</sub></center>      |           64.4            |          Bright Green           |
|              CuCl<sub>2</sub>              |           70.6            |    Yellowish green* or Blue     |
|              FeSO<sub>4</sub>              |           15.7            | Light greenish blue (turquoise) |
|              CuSO<sub>4</sub>              |           31.6            |            Deep Blue            |
| Fe<sub>2</sub>(SO<sub>4</sub>)<sub>3</sub> |           25.6            |       Orange/Rusty Yellow       |
**Table 1.** Solubilities of relevant iron and copper chlorides & sulfates in water at 0°C, as well as colour of compounds in solution. Data taken from Wikipedia chemical info boxes. 
\*CuCl<sub>2</sub> changes colour depending on the presence of Cl<sup>-</sup> ions. When no chloride is present, solution is a light blue. However, the solution will change from blue to green to yellow in increasing concentrations of Cl<sup>-</sup>.


>[!Note] 
>If oxidized enough, Fe will form Fer<u>ric</u> Sulfate (Fe<sub>2</sub>(SO<sub>4</sub>)<sub>3</sub>) which is closer in solubility in water to CuSO<sub>4</sub>. However, it is insoluble in ethanol and sulfuric acid. It is also a grayish-white crystal that is easily distinguishable from copper sulfate (deep blue) or ferrous sulfate (light green).

>[!summary]
>H<sub>2</sub>SO<sub>4</sub> will be used for this project.


---

# Leaching Kinetics

The leaching of chalcopyrite is slow. REALLY slow. This is likely due to passivation on the surface of the chalcopyrite which dramatically slows the kinetics of the leaching:

>[!quote] 
>The difficulty of leaching chalcopyrite under ambient conditions is generally considered to be surface passivation either from reaction products or adsorbed surface species layers... (Munoz, 1997).
>
>Chalcopyrite leaching is very slow at moderate temperature, which is one of the main limiting factors in copper production in industrial conditions...  The formation of these solid phases could account for the reduction of the available and accessible surface of the mineral and thus severely limits the copper extraction efficiency ([[Dakkoune et al., 2023 - Hydrometallurgical Processing of Chalcopyrite by Attrition-Aided Leaching.pdf#page=1&selection=314,0,316,23|Dakkoune et al., 2023]]).
>
>A major issue with the leaching of chalcopyrite concentrate in an acidic solution of ferric sulphate at atmospheric pressure and temperatures below 110°C, is that copper dissolution typically slows down once approximately 30% of the copper is dissolved, depending on the concentrate ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=19&selection=6,0,10,80|Schaming, 2011, pg. 9.]]).


Below are the various parameters affecting the kinetics of the digestion along with trends and ways to optimize the rate (sections are generally in summary of Schaming's proposal with other sources):

## Acid concentration ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=24&selection=4,0,4,24|§2.2.1]])

>[!quote] 
> The acidity (pH) of the leaching solution applied to the heap is very important. ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=24&selection=6,0,6,80|Schaming, 2011, pg. 24]])


Typically, the lower the pH (more concentrated the acid), the faster the leaching process. Lower initial pH conditions show significant increase in efficiency ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=25&selection=6,0,7,97|Schaming, 2011, Fig. 2.6]]). Leaching appears to rise quickly and then plateau at some seemingly asymptotic value (perhaps due to passivation). The speed and final height of this initial rise seems to be directly proportional to initial pH/acid concentration ([911metallurgist, 2021, figs. 2, 3;](https://www.911metallurgist.com/blog/sulfuric-acid-leaching-kinetics-chalcopyrite-radiochemical-techniques/))

 ![[Pasted image 20250323201256.png]]
[[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=25&selection=6,0,7,97|Schaming, Figure 2.6:]] *Abiotic Leaching Copper Extractions of Four Chalcopyrite Concentrates at 80°C, the Solid Symbols Tests were Run at a pH of 1 and the Open Symbols were Run at a pH of 1.5. (Vilcaez, 2009)*


![[Leaching-Kinetics-Chalcopyrite.png|550]]
[911metallurgist, Figure 2:](https://www.911metallurgist.com/blog/sulfuric-acid-leaching-kinetics-chalcopyrite-radiochemical-techniques/) *Chalcopyrite extraction over time with variable pH for multiple trials. $\Delta n_{t}$ is the total copper in solution in units of $\mu g / g$ and time is in min. Initial rise increases in slope for first 10 minutes as pH decreases, and final plateau value (and slope) are likewise higher.*

![[Leaching-Kinetics-Initial-Copper-Extraction.jpg|400]]
[911metallurgist, Figure 3:](https://www.911metallurgist.com/blog/sulfuric-acid-leaching-kinetics-chalcopyrite-radiochemical-techniques/) *Graph showing first order kinetics (relative change (C) in plateau concentrations ($\Delta n_{p}$ ) in comparison to the concentration of copper in solution ($\Delta n_{t}$)) versus time in minutes for multiple trials at different pH values.*

In the above Figure 3, relative change (C) is found by rearranging the first order equation $[P]_{t}=[P]_{\infty}(1-e^{-kt})$ for -kt. The first order kinetics follow the expression within the logarithm. Relative change decreases (slope becomes more negative) over time with lower pH values, indicating the difference between the concentration at some time ($\Delta n_{t}$) and the plateau/final value ($\Delta n_{p}$) approaches zero sooner. In other words, the reaction approaches its endpoint sooner at lower pH values, and the smaller final values indicate a higher $\Delta n_{p}$ since $-\log(C)\propto k \implies k\propto C^{-1}$. This equation was a bit confusing in the blog, so I figured I'd explain it with this blurb.


As shown in the figures above, higher concentrations of acid show significantly higher leach efficiencies, though the differences in performance become smaller as acid becomes more concentrated.

### The Existence of an Optimal pH

So, having said all this, the question arises whether it is true that using more concentrated acid will always lead to an increase in efficiency, or if there is some limit where this trend breaks.

Although decreasing pH *generally* increases leaching kinetics, Zhong and Li have shown that a pH of 1.0 yielded a maximum rate of leaching, and further decreasing the pH led to a turnover in the trend, that is, efficiency now decreases as pH < 1 ([[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=3&selection=681,0,710,6|Zhong & Li, 2019, Fig. 3]]).

![[Pasted image 20250324214817.png|500]]
[[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=3&selection=681,0,710,6|Zhong & Li, Figure 3]]: *A graph showing copper recovery over time for various trials of pH 0.5-1.5.*

The above figure shows that pH = 1.0 outperformed both 0.5 and 1.5 by substantial margins. The data from [[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=25&selection=6,0,7,97|Schaming, 2011, Fig. 2.6]], and [911metallurgist, 2021, figs. 2, 3;](https://www.911metallurgist.com/blog/sulfuric-acid-leaching-kinetics-chalcopyrite-radiochemical-techniques/) generally agree with this finding. From this, Zhong and Li concluded that pH ~ 1 is optimal:

>[!quote] 
>It is observed that when pH was decreased from 1.5 to 1.0, Cu extraction was increased from 13% to 32% at 438 h. However, when the solution pH was continuous[ly] decreased to 0.5, Cu extraction was decreased to 23%. This indicated that pH 1.0 was favorable to CuFeS<sub>2</sub> leaching.
>
>...Antonijevic and Bogdanovic [[Antonijevic and Bogdanovic, 2004 - Investigation of the leaching of chalcopyritic ore in acidic solutions.pdf|31]] reported that a pH lower than 0.5 (using H<sub>2</sub>SO<sub>4</sub> as leaching medium) reduced Cu leaching rate due to the competition between Fe<sup>3+</sup> and H<sup>+</sup> , especially when acid concentration was increased to 3–5 M. 
>
>([[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=3&selection=756,0,849,9|Zhong & Li, 2019, pg. 3]])

>[!quote] 
>The lowest rate of chalcopyrite dissolution is at pH = 0.5. At higher pH values, chalcopyrite oxidizes easier by oxygen and iron(III) that are present in leaching solutions ([[Antonijevic and Bogdanovic, 2004 - Investigation of the leaching of chalcopyritic ore in acidic solutions.pdf#page=11&selection=51,47,77,30|Antonijevic and Bogdanovic, 2004, pg. 11]]).

So it is advised not to cross the pH = 0.5 line for effective leaching.


>[!summary]
>Therefore, we can conclude that lower pH generally increases the kinetics of leaching until $pH \lesssim 1$ at which point it begins to decrease again.

## Temperature ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=26&selection=4,0,7,98|§2.2.2]])

Higher temperatures typically mean a faster reaction given the principles of kinetics:
$$
k=e^{-E_{a}/RT}
$$
$$
\therefore k \propto T
$$

In Schaming's proposal, he shows that high leach percentages were reached in lesser time when operated at higher temperatures (see below). 

![[Pasted image 20250323201701.png]]
[[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=26&selection=7,0,7,98|Schaming, Figure 2.7]] *Effect of Temperature on Copper Extraction from a Chalcopyrite Concentrate. (Lu, 2000)*

Schaming does not talk much further on the effect of temperature (at least not in contexts applicable here).

Consistent with these results, Zhong and Li showed that temperature has great impact on copper extraction:

![[Pasted image 20250324224032.png|500]]
[[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=4&selection=46,0,62,11|Zhong & Li, Figure 5]]: *A graph showcasing four trials at different temperatures.*

From the above figure, it is shown that temperature is a great factor in the process of dissolving copper from the ore (about 3%/K).

>[!quote]
> It is clearly showed that Cu extraction was increased with increasing temperature, for example, Cu recoveries of 17%, 34%, and 67% were observed at 318 K, 328 K, and 338 K at 144 h, respectively, with an almost 100% Cu being extracted when temperature was further increased to 348 K, indicating that CuFeS2 leaching was significantly influenced by increased temperature ([[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=4&selection=369,0,487,0|Zhong & Li, 2019, pg. 4]]).

This is further corroborated by Ruiz et al. when they wrote:

>[!quote]
> The results are shown in Fig. 3, where one can see that the dissolution rate of chalcopyrite increases significantly when the temperature is augmented. It can be observed that at 80°C, the copper dissolution is slow and only 20% dissolution was obtained in 180 min, while at 90°C, over 90% of the copper was dissolved in the same time ([[Ruiz et al, 2011, Chalcopyrite leaching in sulfate–chloride media at ambient pressure.pdf#page=3&selection=145,37,152,27|Ruiz et al, 2011, pg. 3]]).

![[Pasted image 20250324224710.png|500]]
[[Ruiz et al, 2011, Chalcopyrite leaching in sulfate–chloride media at ambient pressure.pdf#page=4&selection=147,0,181,9|Ruiz et al, Figure 3]]: *Effect of the temperature on the copper dissolution from chalcopyrite concentrate in H<sub>2</sub>SO<sub>4</sub>–NaCl–O<sub>2</sub> solutions*

>[!summary]
>Overall, it is clear to see from multiple sources that temperature is directly proportional to the leaching kinetics, and is incredibly important, if not one of the most relevant factors. However, note that high temperatures will drive forward the decomposition of H<sub>2</sub>O<sub>2</sub>, making aeration seem more favorable.


## Particulate Size ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=27&selection=2,0,2,19|§2.2.3]])

Another factor affecting kinetics is surface area. It follows then that grinding the ore into smaller pieces should increase efficiency as there is more area available to the acid. This indeed seems to be the case as it is corroborated by all who investigated it ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=27&selection=4,0,5,19|Schaming, 2011, pg. 27]]; [[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=3&selection=313,0,326,4|Zhong & Li, 2019, pg. 3]]).


![[Pasted image 20250324231809.png|500]]
[[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=27&selection=8,0,9,18|Schaming, Figure 2.8]] *Effect of Particle Size on Copper Dissolution from a Chalcopyrite Concentrate. (Fuerstenau, 2005)*

The highest Cu leaching recovery was achieved at −38 μm ([[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=3&selection=329,1,349,1|Zhong & Li, 2019, pg. 3]]) which may be difficult to achieve, but the overall trend is smaller is always better.

>[!summary]
>Particle size is directly tied to the kinetics of leaching. More specifically, smaller = better, so grind the ore as fine as you possibly can. It seems to follow a shrinking core model.


## Additions

### Chloride ions ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=28&selection=2,0,2,24|§2.2.4]])

The addition of Cl<sup>-</sup> ions seems to directly positively impact the rate of leaching, though the mechanism of why they do so is debated. It is somewhat commonly proposed that the Cl<sup>-</sup> ions somehow attack the S<sup>0</sup> passivated surface on the chalcopyrite, making it more porous which allows the acid to penetrate and increases the surface area ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=28&selection=19,0,24,30|Schaming, 2011, pg. 28]]; [[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=4&selection=143,0,284,0|Zhong & Li, 2019, pg. 4]]).

>[!quote]
The leaching of chalcopyrite concentrates with chloride addition has shown faster leaching kinetics than in a sulphate only solution ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=28&selection=4,0,5,29|Schaming, 2011, pg. 28]]). 


> [!quote]
> Generally, Cu extraction was increased with increased NaCl concentration ([[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=3&selection=1072,0,1089,0|Zhong & Li, 2019, pg. 3]]).
> 
> A further increase in NaCl concentration to 0.1 M apparently increased Cu extraction to 32%, with much greater Cu extraction being observed at higher NaCl concentration ([[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=4&selection=93,0,142,14|Zhong & Li, 2019, pg. 4]]).
> 
> Once NaCl was added into the leaching system, Cu extraction was increased dramatically, especially when NaCl concentration was greater than 0.01 M ([[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=6&selection=781,0,822,1|Zhong & Li, 2019, pg. 6]]).


>[!quote]
>  It is clear that in the absence of chloride ions the chalcopyrite dissolution is very small. However, the addition of 17.7 g/l of Cl− (0.5 M) to the leaching solution produced a dramatic increase in the dissolution ([[Ruiz et al, 2011, Chalcopyrite leaching in sulfate–chloride media at ambient pressure.pdf#page=4&selection=55,20,77,28|Ruiz et al, 2011, pg. 4]]).


![[Pasted image 20250326203652.png|500]]
[[Zhong and Li, 2019 - An improved understanding of chalcopyrite leaching kinetics and mechanisms in the presence of NaCl.pdf#page=3&selection=712,0,730,11|Zhong and Li, Figure 4]]: *Effects of NaCl concentration on Cu extraction.*



![[Pasted image 20250326203503.png|500]]
[[Ruiz et al, 2011, Chalcopyrite leaching in sulfate–chloride media at ambient pressure.pdf#page=5&selection=174,0,206,10|Ruiz et al, Figure 7]]: *Effect of chloride concentration on copper dissolution from chalcopyrite concentrate in H<sub>2</sub>SO<sub>4</sub>–NaCl–O<sub>2</sub> solutions.*

For the above figure (Ruiz et al.), the trials of 0.5M, 1M, and 1.5M) show diminishing returns. For values of 0M - 1 M, there is a difference (Zhong & Li), but any higher and it seemingly stops being effective.

>[!note]
>Sodium contamination is  hard to get rid of. Don't add more than 1M because of the diminishing increase in rate and to reduce the sodium in solution that could get trapped in the crystals. No sense in introducing extra impurities for truly negligible improvements in rate.

>[!summary]
>Chloride ions seem to make a big difference to the rate by interfering with passivation and promoting oxidation. It is effective up to ~1M, so aim to add around that much NaCl to the leaching solution.


### Ferric Ions ([[Schaming 2011 LEACHING-CHALCOPYRITE-ORE.pdf#page=30&selection=2,0,2,22|§2.2.5 ish]])

The addition of Fe<sup>3+</sup> ions is sometimes added as an oxidant, though its efficacy is debated. A few of the papers show that ferric ions have little to no positive effect ([[Antonijevic and Bogdanovic, 2004 - Investigation of the leaching of chalcopyritic ore in acidic solutions.pdf#page=9&selection=16,3,18,42|Antonijevic & Bogdanovic, 2004, pg. 9]]), or a downright negative impact on the rate ([[Ruiz et al, 2011, Chalcopyrite leaching in sulfate–chloride media at ambient pressure.pdf#page=4&selection=103,19,106,48|Ruiz et al, 2011, pgs. 4]], [[Ruiz et al, 2011, Chalcopyrite leaching in sulfate–chloride media at ambient pressure.pdf#page=6&selection=61,0,63,45|6]]).


![[Pasted image 20250326214840.png|500]]
[[Ruiz et al, 2011, Chalcopyrite leaching in sulfate–chloride media at ambient pressure.pdf#page=5&selection=258,0,273,6|Ruiz et al, Figure 8]]: *Effect of ferric ion concentration in solution on the copper dissolution from chalcopyrite concentrate in H<sub>2</sub>SO<sub>4</sub>–NaCl–O<sub>2</sub> media.*

As shown above, adding extra ferric ions has barely any effect on the rate of dissolution, and in fact has a negative impact at "higher" concentrations. This is because the iron from the chalcopyrite itself being dissolved and oxidized to Fe<sup>3+</sup> acts as an internal supply of an oxidizer already, and it does not need any external help so to speak:

> [!quote] 
>  It points out that iron presence is enough, released during decomposition of oxidic iron minerals by acid, for leaching of present sulphide copper minerals. This finding is very important because the addition of new iron source for hydrometallurgical ore treatment in Bor is unnecessary ([[Antonijevic and Bogdanovic, 2004 - Investigation of the leaching of chalcopyritic ore in acidic solutions.pdf#page=9&selection=18,42,24,22|Antonijevic and Bogdanovic, 2004, pg. 9]]).
>  
>  Iron (III) concentration in investigated range has no important influence on chalcopyrite leaching rate. It points out that iron presence is enough, released during decomposition of oxidic iron minerals by acid, for leaching of present sulphide copper minerals ([[Antonijevic and Bogdanovic, 2004 - Investigation of the leaching of chalcopyritic ore in acidic solutions.pdf#page=11&selection=85,1,103,9|Antonijevic and Bogdanovic, 2004, pg. 11]]).
>  


>[!summary]
>Overall, the addition of ferric ions *may* help at low concentrations, but the chalcopyrite should supply enough on its own that adding more is not needed. Therefore, don't worry about adding any.

## Summary (Kinetics)

Having read through the papers, I believe that the following should be implemented to try to maximize the rate of leaching:

* Initial pH value of about 1.0 is ideal
* Temperature should be held high (ideally >80-90°C)
	* High temps will decompose H<sub>2</sub>O<sub>2</sub> quickly, so use aeration
* The ore should be ground as fine as possible (small particle size)
* Add enough NaCl such that the initial concentration is around 1.0 M
* Avoid adding extra Fe<sup>3+</sup> ions
* It is a good idea to agitate the mixture every so often, but stirring is not critical

---
# Selective dissolution of Fe
<font color="#7f7f7f">This is still a hypothetical route as this idea just came to me and has not yet been tested. Some attempts at finding supporting research is being made, though experimental verification may be easier </font>

Since copper is not readily dissolved in acids without an oxidizer (at least not sulfuric or hydrochloric), it may be worth investigating a process by which no oxidizer is added to the chalcopyrite in order to dissolve the more reactive iron from the mixture, leaving the copper behind which can then be dissolved in the presence of an oxidizer. 

This process may or may not be affected by the oxidation of Fe ions into Fe<sup>3+</sup> which are then able to oxidize copper as ferric ions are commonly used as oxidizing agents in the leaching of chalcopyrite.





# Apparatus

With the bulk of the theory now out of the way, it is time to find a way to implement all of the considerations in a physical setup to execute the leaching.


## Proposed Apparatus 1:

The old reaction vessel may still be a viable option for this project as it has a way to contain and remove the harmful H<sub>2</sub>S, keep water from escaping, and is suitably large. However, it is not borosilicate and should not be heated. Since heat is an extremely important factor in the kinetics of leaching, this may be a deal-breaker for the old setup.


### <font color="#9bbb59">Pros:</font>
* No new materials needed
* Lid traps moisture
* Big container
### <font color="#c0504d">Cons:</font>
* Cannot heat (not borosilicate)
* Cannot aerate (though may drill another hole)
* Seal not perfect


## Proposed Apparatus 2:

* Main reaction vessel is a 1L, 3-neck RBF with ground glass joints
* Middle neck will have a condenser for containing water (capped off?\*)
* One side neck may have a thermometer or just a stopper
* Other side neck may have a gas line to bubble the H<sub>2</sub>S into a trap 
* Apparatus submerged in hot water\** bath for even heating
* All joints greased


![[Pasted image 20250328125706.png|500]]


\* The condenser may be used to reflux any evaporating water, but leaving it uncapped would allow the H<sub>2</sub>S to escape. Normally, capping a reflux is a terrible idea since you are heating a closed system which builds pressure. However, the gas line running into the NaOH scrubber would allow for any building pressure to escape into the scrubber. 

\** Water should probably be used in place of oil if this is going to be heated for a long time since an oil bath would pose a fire hazard if heating unattended or if there were a spill. The downside to this is the constant replenishing of water. If I had a heating mantle, I would use it here.



# Experimental Observations

Before attempting the project in earnest, I decided to try a small run of "pure" copper and iron in beakers and acid as a microcosm/simulation of the actual conditions of the run to observe the behavior of the kinetics.  


# General Workflow Notes

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ba7wXAbPCXM?si=VL69NoUytqyGYSIN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



