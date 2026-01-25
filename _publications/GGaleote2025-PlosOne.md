---
title: "Time series segmentation for recognition of epileptiform patterns recorded via microelectrode arrays in vitro"
collection: publications
permalink: /publication/GGaleote2025-PlosOne
excerpt: 'Researchers have addressed the challenge of detecting and classifying events from ongoing brain activity with computationally inexpensive implementations by developing two algorithms: ZdensityRODE and AMPDE. These algorithms utilize time series segmentation (TSS) to extract different levels of information from LFPs and identify relevant events.'
date: 2025-01-01
venue: 'Plos one, 20(1), e0309550'
---
Epilepsy, a neurological disorder affecting approximately 1% of the global population, presents a significant challenge as 30-40% of patients do not respond to pharmacological treatments. In response to this, closed-loop deep brain stimulation (DBS) is being explored as a promising alternative for individuals with drug-resistant epilepsy. A crucial aspect of effective seizure control using DBS is the development of algorithms that can identify relevant electrographic biomarkers from local field potentials (LFPs) to precisely time stimulation.

Researchers have addressed the challenge of detecting and classifying events from ongoing brain activity with computationally inexpensive implementations by developing two algorithms: ZdensityRODE and AMPDE. These algorithms utilize time series segmentation (TSS) to extract different levels of information from LFPs and identify relevant events. Time series segmentation involves dividing a continuous signal into discrete segments that share common characteristics, with the goal of identifying patterns, states, or behaviors within the data.

The algorithms were validated using epileptiform activity induced by 4-aminopyridine in mouse hippocampus-cortex (CTX) slices, recorded via microelectrode arrays. The ZdensityRODE algorithm demonstrated a precision and recall of 93% for ictal event detection, and 42% precision for interictal event detection. The AMPDE algorithm achieved 96% precision and 90% recall for ictal event detection, and 54% precision for interictal event detection. While initially trained for ictal activity, these algorithms can be fine-tuned for improved interictal detection, potentially aiding in seizure prediction.
