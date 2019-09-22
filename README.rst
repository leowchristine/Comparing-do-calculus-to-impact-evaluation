# Comparing-do-calculus-to-impact-evaluation

The goal here is to compare and contrast the causal inference approach between do-calculus and impact evaluation

This is not about codes for conducting casual inference in do-calculus versus impact evaluation. I don't think we are truly there to automate causal inference, especially by just running a set of codes on a dataset.
This is a place to consider how the two disciplines approach causality. What are the similarities and differences?

The causal approach from the impact evaluation perspective is taken from:
The Department of Education What Works Clearinghouse (WWC) - WWC is a well recognized authority on setting the standards for conducting causal studies in education (https://ies.ed.gov/ncee/wwc/)

The causal approach from the do-claculus perspective is taken from various sources:
1. The Book of Why: The New Science of Cause and Effect by Judea Pearl (2018)
2. Microsoft's DoWhy (https://github.com/microsoft/dowhy#installation)
3. Bayesia's Bayesian Networks & BayesiaLab (https://www.bayesialab.com/)

From the WWC and the impact evaluation perspective, randomized controlled trial (RCT) is not the only study design to infer causality. Other causal designs recognized by WWC include 1) quasi-experimental designs such as propensity score, instrumental variable; 2) regression discontinuity design (RDD); and 3) single case design. All of these designs require, at the more baisc level, a comparison group.

Similarly, according to The Book of Why by Judea Pearl, both do-calculus and counterfactuals are the basis for the new science on causality.

Comaprison group and counterfactuals are crucial -- and there are times, with the right situation and the right data, causality can be inferred from one of the causal designs without conducting a RCT. A good example is RDD, which had been most frequently conducted using administrative data. It is a useful design to consider for big data in online platforms.

Other quasi-experimental designs have also been proposed by WWC, The Book of Why, and DoWhy, such as propsensity score matching. But the kind of data needed for quasi-experimental design and propensity score matching might require other types of data than what is normally collected and stored in the platform.
