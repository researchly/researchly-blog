---
layout: post
title:  "Text mining technological capabilities for innovation discovery"
date:   2020-04-05
description: 'This post describes how to find innovation opportunities using text mining to analyze the core capabilities behind technologies.'
image: 'using-text-mining-to-analyze-technologies-for-innovation-discovery.jpg'
---

Based on a paper by Yoon, Park, et al. a company has three options to create new technologies or products:


1. Develop new technologies by identifying overlapping capabilities between owned technologies and new technologies
2. Produce new products using an owned technology
3. Improve existing products by using a new technology


| ![Overview]({{ "/assets/img/posts/text-mining-innovation-overview.png" | relative_url }}) | 
|:--:| 
| *How companies can innovate by using Text Mining to analyze products and technologies* |


There are two premises to this approach:

1. the company already possess technologies or products
2. the products and technologies must be dissected into their components

Let's look at how products and technologies can be dissected into their components.

## Dissecting products and technologies into components

According to the paper:

- **a product** consists of *core* technologies
- **a technology** is described as a set of functions
- **a function** (or capability) consists of a verb (what the function does) and an object (to what does the function do what it does)


Consider a hot air heater:


- **Product**: hot air heater
- **Technologies**: hot_air_heater_tech_0 (the actual name is irrelevant)
- **Functions of hot_air_heater_tech_0**:
	- configure heat
	- heat air
	- handle heat

| ![Dissecting products and technologies into components]({{ "/assets/img/posts/text-mining-innovation-example-hot-air-heater.png" | relative_url }}) | 
|:--:| 
| *Dissecting products and technologies into components* |



Having said that, let's look at the first possibiliy: 'Develop new technologies by identifying overlapping capabilities between owned technologies and new technologies'.

## Develop new technologies by identifying overlapping capabilities between owned technologies and new technologies
In this scenario, the company owns one technology and develops a new technology by modifying the existing one.

For instance, the company owns the technology hot_air_heater_tech_0. hot_air_heater_tech_0 does these things:

- configure heat
- heat air
- handle heat

The company further knows about a technology called 'automobile_radiator_tech_0'. automobile_radiator_tech_0 does these things:
- configure heat
- heat air
- handle heat
- manage speed differences

By comparing these two technologies (hot_air_heater_tech_0 and automobile_radiator_tech_0) the company identifies that their functions overlap (configure heat, heat air, handle heat).

| ![Overlapping capabilities indicate possible new technologies]({{ "/assets/img/posts/text-mining-innovation-overlapping-capabilities.png" | relative_url }}) | 
|:--:| 
| *Overlapping capabilities indicate possible new technologies* |

Now, by modifying 'hot_air_heater_tech_0' the company can develop 'automobile_radiator_tech_0'. In this fictional scenario (see image above), it means that the company must incorporate "Function D" into 'hot_air_heater_tech_0' to develop 'automobile_radiator_tech_0'.

## Produce new products using an owned technology
In this scenario, the company uses a specific technology to produce a certain product. To innovate, the company wants to use that technology to produce a different product.

For that to work, the company must find products whose technologies do the same things. The only difference between the technologies is how they achieve their output.

Consider 'light_sensor' as the technology that produces light sensors. It does these things:

- detect light
- provide light
- contact sensor

The technologies behind several other products also do these things. For instance, a headlight or an optical switch.

| ![Use existing technology for new products]({{ "/assets/img/posts/text-mining-innovation-one-technology-new-products.png" | relative_url }}) | 
|:--:| 
| *Use existing technology for new products* |

This means, that with their technology 'light_sensor' the company cannot only produce a light sensor but also headlights or optical switches.

Please note that the paper only compares core technologies. There are, of course, technological differences between a light sensor and a headlight. But those technological differences are not considered 'core'.

Of course, the company can also reverse the scenario. The next section describes the reverse case.

## Improve existing products by using a new technology
In this scenario, the company improves its existing product by using a different technology.

For instance, the company's 'GPS receiver' does these things:

- acquire signal
- calculate position
- determine satellite

As expected, several other technologies can do the same. Among them, technologies related to 'Mobile Communication Device' or 'Antenna module'.


| ![Try new technologies for existing products]({{ "/assets/img/posts/text-mining-innovation-new-technologies-existing-product.png" | relative_url }}) | 
|:--:| 
| *Try new technologies for existing products* |


<hr>  

At Researchly we are building tools that help companies do such analysis. If you want to try them yourself (they are free), head over to [Researchly](https://www.researchly.app/?utm_source=528547e2&utm_medium=88682ffa&utm_campaign=144ce602)


Photo by Dominik Vanyi on Unsplash
