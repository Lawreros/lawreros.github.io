---
title: "Autism and Affect"
excerpt: "Studying the relationship between physiological signals and affect in individuals with ASD-3 <br/><img src='/images/custom/PSHR_image.png' width='400' height='300'>"
collection: projects
---

As part of the [Department of Cognitive Neurology](https://web.jhu.edu/cognitiveneurology/) at Johns Hopkins, I've been working with a team of researchers and teachers to explore the relationship between physiological signals (such as heart rate, through ECG) and observable affect (crying, self-injurious behavior, etc.) in individuals with [ASD-3](https://www.verywellhealth.com/what-are-the-three-levels-of-autism-260233). There are two distinct goals for this study:

*Disclaimer: I am not an expert with respect to ASD-3, my responsibilities are mainly technology and analysis*

1. **Practical:** Due to the fact that many individuals with ASD-3 are non-verbal, they are unable to communicate their needs and intentions effectively and are prone to outbursts with little warning. We aim to provide tools which give teachers and other caretakers insight into the emotional state of individuals with ASD-3, as well as warnings about the potential for outbursts in the immediate future. This gives them time to adjust or redirect the individual.
2. **Theoretical:** The ASD-3 population is massively understudied; both due to its relativly small size and due to the difficulty involved in having individuals with ASD-3 perform tasks in a research environment. Most reaserch involving autism studies ASD-1 and extrapolates the findings onto ASD-3 (with little empirical support).

In order to accomplish this, I have created/developed the following tools:
- The [PSHR_iOS app](https://github.com/Lawreros/PSHR_iOS), which can be downloaded on any iPhone running iOS 13 or more recent (contact me for the link). The app pairs with a nearby H10 Polar strap and begins recording heart rate and ECG data transmitted by the strap over Bluetooth Low Energy and appends the data to local text files.
- The [PSHR_pipeline](https://github.com/Lawreros/PSHR_pipeline/tree/main), which is a collection of MATLAB scripts and functions for the processing and statistical analysis of the collected data from the PSHR_iOS app.