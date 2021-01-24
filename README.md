### Repurposing a digital kitchen scale for neuroscience research: a complete hardware and software cookbook for PASTA  
## “Living Guidelines”: Ethical considerations and responsible transparent reporting with PASTA 

Modularity of open-source research equipment offers important advantages over commercial black box solutions with limited flexibility. Although this is generally a good thing, it comes at a cost as the same principles that enable novel findings by providing a new set of tools through customization also enable inexperienced researchers to set up an experiment outside of what is considered a mandatory standard in the field. With great power of modularity comes great responsibility in methodology and experimental design. In this supplement, we warn about two critical aspects of this challenge related to PASTA in order to provide strong foundations and assistance for researchers and ensure the obtained results are scientifically sound and in concordance with ethical principles of animal welfare.

Open-source research equipment has many advantages over commercial black box solutions, the most important being low build cost and modularity that allows users to customize equipment in accordance with their specific needs. However, these advantages are also a source of problems. Most obviously, building such an apparatus demands an interdisciplinary approach. It is expected from the researcher to have (at least some) understanding of the functioning of the equipment. This might represent a problem for smaller research groups and put off some of the researchers from building their own equipment. However, the silver lining of this problem is that it forces researchers to learn more about the equipment and enables them to have a better understanding of the results otherwise spawned by the commercial black box solutions. Furthermore, customization allows researchers to tackle research questions specifically but requires careful consideration of the hardware setup and experiment planning instead of blindly following experiment protocols - leaving a larger margin of error. In addition to that, handling of the data and reporting of the results might be inconsistent across the studies making them difficult to compare. To overcome this problem, this “living guidelines” document will be regularly maintained to provide practical information for researchers using PASTA. Additionally, an email with a specific question is always welcome. (-: Authors’ email addresses may be found at the end of this text.

### Ethical considerations regarding PASTA

Acoustic startle used in the experiments can be stressful to the animals. It is thus imperative to consider and apply the same ethical standards that apply to other animal research. The research should, as always, be carefully planned to involve as few animals as possible and avoid inflicting unnecessary pain and discomfort to the animals. The existing guidelines regarding animal ethics are applicable and their use could be helpful regarding the planning and reporting of the experiment. Such guidelines include, but are not limited to, PREPARE<sup>1</sup> and ARRIVE<sup>2</sup> guidelines. 

In this preliminary study, acoustic startle and prepulse inhibition were examined in control and STZ-icv treated rats. Acoustic startle protocol is considered to be stressful for the animals, and although this type of stressful stimuli is commonly used in animal research the researcher should always look for ways to minimize excessive stressfulness of the experimental setup while obtaining relevant results.

### Transparent reporting with PASTA

#### i) Environment

It is paramount that the experimental area is acoustically isolated from areas where test animals are kept so as to avoid sensitising animals to the startling stimulus outside of the experimental environment. This may be achieved with soundproofing the experimental area, by sufficiently displacing the experimental area (e.g. using a room on the far end of the facility from the habitats), or by combining the two techniques. 

We advise thoroughly cleaning the testing area between each animal using a solvent such as ethyl or isopropyl alcohol to prevent previous animals’ hair or excrement from influencing the current animal’s behaviour and test results (e.g. urinary olfactory signalling).

We recommend always supplementing PASTA experimental data with video recordings for validation of PASTA data (e.g. pulse-to-startle latency, see: main text, Supplement 2) and potential identification of novel data that may be gathered from PASTA experiments (e.g. breathing patterns, see: main text, Supplement 4).

#### ii) Experimental design

It is important to tailor the experimental design for every experiment. Main factors to consider are volume, type of acoustic stimulus, acclimation time, pulse/prepulse timing and the total number of pulses/prepulses.  

The target volumes of both pulses and prepulses depend on animal species and the minutiae of their (patho)physiology.  

The acoustic stimulus being applied usually consists of randomly generated white noise, however, this may also be tailored to a specific use as any auditory pattern may be used with PASTA, including pure tones of various patterns (sine, square, sawtooth, etc.) and  any frequency that the sound system is able to reproduce.  

Animals should be allotted some time to get acclimated to the experimental environment before beginning the startle protocol.  

Timing considerations of the startle protocol include the period between each pulse or pulse-prepulse complex, and the period between a prepulse and a pulse. These may be fixed or randomized to some extent (with defined minimum and maximum values).  

Determining the total number of pulses/prepulses is based on a tradeoff. On one hand, it is desirable to have as many startle samples as possible for each animal to demonstrate repeatability of response. On the other, this is limited by practical concerns regarding animal fatigue and total experiment duration, as well as diminishing returns.  

Valsamis, B & Schmid, S provide a sensible design as a template<sup>3</sup>, but extensive literature review on each of these points is recommended to optimally adjust the design for the user’s specific case. More information and examples regarding the startle protocol may also be found in Supplement 1.  

#### iii) Data handling and analysis

The recorded data obtained with ratPASTA is unprocessed (raw) data. Although this complicates the analysis and entails more effort to perform it, it also enables researchers to tailor the analysis to answer specific research questions while accounting for potential confounders that would otherwise be overlooked. Furthermore, exploring the raw data can be of help when choosing appropriate measures to display the effect (mean vs. maximum value vs. area under the curve) and when investigating whether measurement contains artefacts. It is thus imperative to abandon the ridiculous practice of stating “Data is available on (reasonable) request.” and encourage sharing of the raw data (in advance) to fully harness the potential of open-source solutions. Not only it enables the reuse of data for answering other research questions, but enables post-hoc re-analysis (re-evaluation) of the results and conclusions which is especially important when using open source equipment.  

To somewhat simplify the analysis procedure, we made an R package and python wrapper for R package that includes all code used for the analysis of data collected during this proof-of-concept study. We encourage its use and its re-evaluation by fellow colleagues and invite them to collaborate and share their code so it can be incorporated in the package (or at least share it through other venues).

#### iv) Reporting

In accordance with open science and open data principles, we strongly advise that raw data obtained with PASTA setup be made available to other researchers through relevant open-science data repositories. This enables open feedback from other PASTA users regarding any errors that might have been introduced during data processing and analysis, as well as more reliable comparison with other PASTA data (comparison of raw data vs traditional comparison of results) and pooled data analysis.

We strongly advise publication of the experimental protocol which enables iterative refinement of experimental protocols for various groups of use cases. With this rationale, we also strongly encourage open discussion of initial results with the scientific community through preprint servers. 

### Concluding remarks

PASTA is a “living platform” and these are its “living guidelines”. Please check them often as we will update the guidelines as other PASTA-based methods are being developed.

Link to the original paper:  
https://www.biorxiv.org/content/10.1101/2020.04.10.035766v2

If you have any questions or suggestions, please don’t hesitate to contact the authors:  
* Davor Virag \<davor.virag@gmail.com\>
* Jan Homolak \<homolakjan@gmail.com\>
* Ivan Kodvanj \<ikodvanj@gmail.com\>

### Bibliography

1.    Smith, A. J., Clutton, R. E., Lilley, E., Hansen, K. E. A. & Brattelid, T. PREPARE: guidelines for planning animal research and testing. Lab. Anim. 52, 135–141 (2018).  
2.    Percie du Sert, N. et al. The ARRIVE guidelines 2.0: Updated guidelines for reporting animal research. PLOS Biol. 18, e3000410 (2020).  
3.    Valsamis, B. & Schmid, S. Habituation and Prepulse Inhibition of Acoustic Startle in Rodents. J. Vis. Exp. 3446 (2011) doi:10.3791/3446.  
