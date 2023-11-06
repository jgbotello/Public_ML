# Clustering Analysis

**Jhon G. Botello** <sup>**Ph.D. Student in Computer Science, Old Dominion University, Virginia, USA. jbote001@odu.edu**

In this document, I seek to provide mathematical and coding insights about cluster analysis. This approach is based on the review of various papers and websites. Primarily, I share my perspective and acquired knowledge with the goal of providing a useful tool to those interested in the subject.

## What is Clustering Analysis
Cluster analysis is a technique within the field of Pattern Recognition. Basically, Its main objective is to group a set of data into groups or "clusters" based on similarities or common patterns among the elements [1]. In other words, it seeks to identify groups of data that are more similar to each other than to data outside their group. The cluster approach is useful in a variety of application fields, such as market research, astronomy, psychiatry, genomics, social network analytics and many other areas where patterns or hidden structures can be found in unlabeled data [2]. In general, cluster analysis helps us to reveal valuable information and simplify the understanding of complex data sets by organizing data into more manageable and meaningful groups. It also allows us to label data as it is an unsupervised learning technique as well as to generate profiles of the observations.

## A First Approach to Cluster Analysis
There are several ways to take initial steps in cluster analysis. This involves conducting a thorough exploratory analysis of our data before applying a specific model. When embarking on projects that involve data clustering, one approach is to identify patterns using tools such as histograms, scatterplots, scatterplot matrices, and other visualization techniques. However, this approach is most useful when the number of variables is relatively small. When dealing with datasets that have a large number of variables, the situation becomes more complex because it's not easy to perceive the structures when considering all dimensions simultaneously. In such cases, it becomes necessary to employ approaches that reduce the data's dimensionality first. This way, the visualization techniques mentioned earlier can once again become relevant and useful. There are several options to reduce dimensionality but the most common and the one to which I will refer in this paper is principal component analysis.

### Principal Component Anlysis 
$x^2$



Idiom: Multiple Bar Chart / Mark: Bar
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Year | key, categorical | Horizontal spatial region (X-axis) |
| Total Women Who Had Children | value, quantitative | Vertical position on a common scale (Y-axis) |
| Category of age | key, categorical | Hue |

<img src="bar_chart.png" height="400" alt="">


## References
* [1] <https://link.springer.com/chapter/10.1007/978-3-642-96303-2_3>
* [2] <https://cicerocq.files.wordpress.com/2019/05/cluster-analysis_5ed_everitt.pdf>
