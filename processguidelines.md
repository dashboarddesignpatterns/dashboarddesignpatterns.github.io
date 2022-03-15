# Design Process and Guidelines

## High-level Design Guidelines

Guidelines are numberd for convenience but are **not ordered** by any particular priority.

1. Don’t overwhelm viewers
1. Avoid visual clutter
1. Avoid poor visual design 
1. Carefully chose KPIs
1. Align with existing workflows
1. Don’t add too much data
1. Provide for consistency
1. Provide for interaction affordances
1. Manage complexity
1. Organize charts symmetrically
1. Group charts by attribute
1. Order charts by time
1. Balance data + space 
1. Increase information
1. Avoid redundancy of information
1. Show information, rather than data
1. Design is an iterative process
1. Context is very important
1. State your meta data
1. Use color carefully
1. **Consider the dashboard templates** best suited to the dashboard
audience and their informational needs, and use their characteristic
design patterns as a checklist for design. 
1. Consider [design tradeoffs](tradeoffs.html)

## Design Tradedoffs

![](docs/assets/figures/schema1.png)

## Stage 0: Clarify the context

At this stage, you want to clarify the context in which your dashboard is being used in. This might require making decisions about some of these parameters. The more clearly you can articulate these decisions and parameters, the better you can make design decisions in your dashboard design process. 

* What is your **audience**? 
  * What do they know about your data and visualization? 
  * What do they know about the data? 
  * You can think of real people in your life that might use the dashboard. In design, that is called a [persona](https://www.interaction-design.org/literature/topics/personas).
* What is the **setting** in which they engage with the dashboard? 
  * Is this a computer screen? A mobile screen? A webite?  
  * Can they interaction? 
  * How much time do they have to view/interact with the dashboard? 
  * How frequently will they consult it? 
* What are the **tasks and decisions** your audience wants to perform?
  * what decisions do they want to make with the data? 
  * What information do they need?
  * Do they simply want to look up values? Do they want to compare? Do they want to analyze?   
* What **information** do they need to fulfill these tasks / make these decisions?
  * do they need to see all of the data? 
  * what data is most relevant?   


## Stage 1: Data & Information

**Design Patterns**: [Data Information](patterns.html#11-data-information)

At this stage, you want to clarify which information from the dataset is important for the user in a given task (see Stage 0). This may involve 
* show a detailed data set
* show aggregated data (e.g., by type, by time, by geographic location, etc...)
* show a single value
* show derived values (e.g., means, trends, summaries) 
* show thresholds

**Guidelines**



## Stage 2: Structure and Page fit

**Design Patterns**:  

At this stage, you should think about the overall structure of your information and whether you 
* can display everything a single page (screen), or 
* whether you need multiple pages to show all the information you identified in stage 1.

In case you need multuple pages, here are some options they can be related: 
* hierarchical
* repeated
* semantic

**Guidelines**

1. **Avoid overflow structure in analytic dashboards** to facilitate
comparison;
   * e.g., use flat or paginated dashboards that fit encod-
ings on screen;
			§ A good structure is informed by (i) data (facets, information), and tasks (overview, comparison).
			§ That structure needs to reflect structure in data and task




## Stage 3: Visual Representations

**Design Patterns**:  

At this stage you want to find visual representations for your data and information (for each page). The list of design patterns is long: 
* numbers
* trend arrows
* icons & pictograms
* gauges and progress bars
* miniature charts
* detailed charts
* tables
* lists

**Guidelines** 

1. Where space allows, **provide redundant and complementary views**
(visual encodings) and levels of abstraction (data information) for
your data:
  * e.g., show selected numbers alongside trend-arrows
and signature charts
  * e.g., more abstract encodings can occupy more screen space
to emphasize importance/relevance/etc
  * e.g., use single values , derived values and thresh-
olds to show key data points at a glance;
1. **Minimize repetitive data using abstraction** (to emphasize key data)
and parameterization (to support personalization );
1. Try to ensure a **consistent color scheme** across the entire dash-
board, either by reusing colors for the same data and value, or by
creating a dedicated and clearly distinguishable scheme for each
visualization.



## Stage 4: Page Layout

**Design Patterns:**

At this stage, you develop a layout of your page. You need to organize the individual components (those defined in stage 3) into a meaningful structure. That structure should reflect how the components are related and of which importance they are to the user. The design patterns in this stage include: 
* Stratified layout with a clear top-bottom hierarchy.
* Table layout: your layout has clear semantics of rows and columns
* Open layouts: there is no specific structure in the layout, other than organizing components in a spacefilling form
* Grouped Layout: you components are grouped and potentially nested according the data semantics
* Schematic layout: you aling your components informed by some external property such as a physical lay-
out or other types of schematic relationships

**Guidelines** 

## Stage 5: Interactivity 

**Design Patterns**

At this stage you will think about the specific interaction components you need to support
* exploration 
* focus & filter
* navitation
* personalization

**Guidelines**

1. Interaction can be a powerful means to personalize, explore, navigate, and focus. 
1. Minimize interaction: If you can solve something with minimal or no interaction, go for it.

