---
layout: post
title: Easier Representation Translation: using Classifiers from a metamodel!
---

One of important concern when speaking about representation of reality (i.e., models) is the connection to the "real" world (also called system under study).  By real world, I mean the **potential evidences** (e.g., data collected by captors) that could feed/reinforce the model in its relation to the reality of the system under study. Someone could say, the "trueness" of the model...I do not like it since it represent a perspective on system. Someone said to me (maybe taking the sentence from another famous MDE people) a model is always false. True, false these are absolute relation in the relative world of modelling! Of course, a model can embed some error, misconceptions, etc... for sure true or false is not the first qualifier we can apply to models. 

So, modelling is not just about building conceptual models coming from the head (i.e., mental conceptualisation) but also providing representation of **actual source of information**. Ok, depending on the concrete case, this source of information could also be seen as a model expressed in a different modelling language than the one we always use.

Some models are produced from existing artifacts, like Abstract Syntax Trees coming from source code (I see you raising your hand and telling me that a source code is also a model, right!). Let's be factual, there are different supports/formats for knowledge representation. In the literature we can see the notion of technical/technological space, the metaphor of villages (from A. Vallecillo), these are all explaining that some operations are more effective using some support for knowledge representation. As such, a data-base using tables is better for rapid querying of list/properties of elements whereas a graph data-base will be more efficient for highly linked data with few properties. 
We can do the same for modelling in general, targeting a modelling framework (e.g., EMF, JSMF, etc.).

Writting some format conversion is sometime hard requiring to write complex transformation, parsers, etc. This is a two steps approach, it requires first to derive (parse) the source into a modelling format processable, then to transform the raw objects coming from the parsing into a structured model conforms to the metamodel (here, it is a kind of viewpoint) you want to focus on. For instance, think of an excel sheet and covert its data into a structured graph in you environment... For understanding the (accidental) complexity I suggest you to see the [ATL use-cases](https://www.eclipse.org/atl/usecases/SoftwareQualityControlToolsInteroperability/).



Indeed, this could go father and be uselful for **structuring raw data**.


