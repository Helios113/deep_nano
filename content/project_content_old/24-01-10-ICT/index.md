---
title: Realistic fault modelling to enable optimization of low power IoT and Cognitive fault-tolerant computing systems
date: 2023-01-08
#authors: ["Vihar Georgiev"]
---


Partners: University of Glasgow (A. Asenov, V. Georgiev)

EPSRC £450K January 2021 to December 2023


<!--more-->
For future ICT industry, the elephant in the room is Internet of Things (IoT) and Artificial Intelligence (AI). They are driving the fourth industrial revolution that is profoundly changing how we live and interact. The main issues for IoT and AI have been identified as: power, security, and cost. This project is co-created with the industrial partners and focuses on the power issue.

One of the most effective way for reducing power is by lowering the operation voltage, Vg, towards the transistor threshold voltage, Vth. This has motivated recently extensive research in near threshold voltage computing. As Vg approaches Vth, the operation window (Vg-Vth) reduces and the system will be increasingly vulnerable to instability in Vth: a small rise in Vth can effectively switch off a transistor. Instability causes faults in operation, such as read and write errors in SRAM and digital timing errors. It is a limiting factor for how low (Vg-Vth) and, in turn, how much power consumption can be reduced.

One of the critical tasks for low power system optimization is to minimise operation voltage and power consumption that will deliver specified yield 'Y' in 'X' years at a temperature below 'T'. To complete this optimization, designers need a fault analysis model that gives the time evolution of the probability distribution of Vth and driving current, Id, at a given distance from their target values. The further Vth and Id depart from their target values, the more likely a circuit will fail.

Despite of decades of research, a reliable fault model is still not available. Indeed, in a recent review, the lack of realistic fault model tops the list of challenges for Cognitive Computing System design. Although the need for this model is clear, even world-leading EDA suppliers and foundries cannot deliver the model and current SPICE models simply do not include Jitter. This is related to weaknesses of previous research, including statistically inconsistent bottom-up methodology, limited time window, weak model verification criterion, and the neglect of the interaction of different instability sources.

The fabless UK IC-design companies are using foundries for their chip fabrication. Software is the essential bridge between designers and foundries. As there are no generally accepted realistic fault models at present, designers have to rely on adding a guard-band (design margins) obtained from empirical 'worst case guess'. This contributes to the substantial discrepancy between design and Si performance. As CMOS nodes are downscaled to nano-meter range, the stochastic spreading of device parameters increases dramatically this discrepancy, which has been identified as a major challenge for optimizing the design of low power IoT and Cognitive Computing Systems.

The aim of this project is to provide the world first test-proven fault model that enables statistical, dynamic, and quantitative analysis of fault rate and in turn the optimization of low power IoT and Cognitive Computing Systems. Novel techniques and methodologies will be employed to overcome the weakness of early works, including a top-down approach to remove device selection, advanced data acquisition method for long time window, qualifying the model by prediction capability, covering the interactions between different sources of instabilities. The developed model will be tested against Si performance of real circuits together with the industrial project partners. If successful, it will deliver a paradigm shift from one-size-fit-all to application specific fault analysis and optimization, reducing power and time-to-market.

Link to the website:
https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/T023244/1