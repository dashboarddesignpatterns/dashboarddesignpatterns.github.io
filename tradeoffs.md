# Design Tradeoffs

Every design process and design problem is unique in that several
parameters must be considered: users, tasks, contexts, devices, etc.
Design tradeoffs are inevitable when no solution is optimal, i.e.,
when the specific parameters of a design problem have contradic-
tory knowledge (e.g., guidelines, heuristics, solutions). Dashboard
designers can use this knowledge to inform their approach, but other
activities (deliberate or otherwise) will be necessary: e.g., reasoning
and logic, experimentation and prototyping, user-centered design
and evaluation. Decisions may likely influence or conflict with other 
decisions, causing further design tradeoffs to be necessary, requiring
constant iteration towards good design. 

## Four Parameters

In dashboard design, there are **four parameters**, mentioned below in no particular order: 
* the **screenspace** you have available for your design
* the number of **pages** that you distribute your information across, given that you can only view one page at a time
* the amount of **abstraction** in your data and information
* the amount of **interactivity** required to access information in your dashboard.

Each of these parameters, you can either **increase** or **decrease**. For example, 
* you **increase screenspace** by showing the dashboard on a larger screen or using an overflow (page scroll)
* you **decrease screenspace** by showing it on a mobile phone or embedding the dashboard into an existing UI
* you **increase the number of pages** by distributing content across more pages. 
* you **decrease the number of pages** by combining content into the same page. 
* you **increase abstraction** by showing aggregated data, single values, or derived values
* you **decrease abstraction** by showing more detail about your data and information. 
* you **increase interactivity** by providing means for exploration, navitation, filter&focus, and personalization
* you **decrease interactivity** by reducing interactive means

Now, ideally, you want to **minimize all of these parameters**.
* **minimize screenspace** because the less space your dashboard takes, the better you can embedd it or show it on mobile.
* **minimize abstraction** to show as much of your data and information to your viewer.
* **minimize the number of pages** because then a viewer sees all the information at a glance and you can 
* **minimize interaction** because a viewer can do other things while observing the dashboard and no information is hidden.


## Balancing Parameters

If your data, information, and context allows you to easily minimize all of these parameter you are good. However, in many cases your data and information are too much to minimize all parameters easily. In that case, you need to **make tradeoffs**

![](docs/assets/figures/tradeoffs2.png)

The above schema shows these tradeoffs you are making by trying minimize one component. These tradeoffs are best explained though the metaphor of **stress**. 
* The more you minimize each of your parameters, the more stress you include upon the other parameters. 
* The more you maximnize your parameters, the less stress you induce.

The goal of the design process is to optimize the balance of parameters in your dashboard by minimizing the stress in your design. 

Let's look how increasing/decreasing one parameter affects the others. 
* if you want to **decrease screenspace**, you must: 
  * **increase the number of pages** (e.g., by moving content to other pages), or 
  * **increase interactivity** (e.g., by providing mechanisms for filtering and detail-on-demand), or
  * **increase abstraction** (e.g., by aggregating your data, or removing details from the visualizations)
* vice-versa, if you can **increase screenspace** (e.g., by switching to a larger screen), you **can** 
  * **decrease the number of pages**, or
  * **decrease interactivity**, or
  * **decrease abstraction**. 

The same holds true for all mutual relationships between these four paramters. Moreover, you can 
* increase a single **same parameter**, e.g., reducing space by increasing interactivity.
* increase mulitple of the **other parameters by some fraction**, e.g., reducing space by adding some interactitity and somewhat increasing abstraction)  

This leads us to the following conclusion

* **Minimizing one parameter, requires increasing one or more of the other parameters**. 



