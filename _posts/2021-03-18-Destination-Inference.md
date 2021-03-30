---
title: Probabilistic model for destination inference and travel pattern mining from smart card data
author: Zhanhong Cheng
category: research
subtitle:  	Published in Transportation
tags: Post Transit
---

## Authors
Zhanhong Cheng, Martin Trépanier, Lijun Sun 

## Abstract
Inferring trip destination in smart card data with only tap-in control is an important application. Most existing methods estimate trip destinations based on the continuity of trip chains, while the destinations of isolated/unlinked trips cannot be properly handled. We address this problem with a probabilistic topic model. A three-dimensional latent dirichlet allocation model is developed to extract latent topics of departure time, origin, and destination among the population; each passenger’s travel behavior is characterized by a latent topic distribution defined on a three-dimensional simplex. Given the origin station and departure time, the most likely destination can be obtained by statistical inference. Furthermore, we propose to represent stations by their rank of visiting frequency, which transforms divergent spatial patterns into similar behavioral regularities. The proposed destination estimation framework is tested on Guangzhou Metro smart card data, in which the ground-truth is available. Compared with benchmark models, the topic model not only shows increased accuracy but also captures essential latent patterns in passengers’ travel behavior. The proposed topic model can be used to infer the destination of unlinked trips, analyze travel patterns, and passenger clustering.

![](https://smart-transport.github.io/img/projects/Destination_inference.png)

- Cheng, Z., Trépanier, M., & Sun, L. (2020). Probabilistic model for destination inference and travel pattern mining from smart card data. Transportation, 1-19. [(link)](https://doi.org/10.1007/s11116-020-10120-0)



