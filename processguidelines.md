# Dashboard Design Guidelines
# Process & Guidelines

## High-level Design Guidelines

1. Balance data + space (cost) while increasing information
1. Avoid redundancy of information
1. Show information, rather than data
	
	

## Stage 0: Context

Define the context in which your dashboard is being used in. This includesL 

* What is your **audience**? What do they know about your data and visualization? 
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

Design Patterns: [Data Information](patterns.html#11-data-information)

Define the data information from the dataset important for the user in a given task. This may involve calculating trends, choos-
ing specific temporal intervals, etc. Many of these decision will require data processing and abstraction 



## Stage 2: Structure


## Stage 3: Visual Encoding


## Stage 4: Page Layout


## Stage 5: Interactivity 

	
	

1. Where space allows, **provide redundant and complementary views**
(visual encodings) and levels of abstraction (data information) for
your data:
  * e.g., show selected numbers alongside trend-arrows
and signature charts
  * e.g., more abstract encodings can occupy more screen space
to emphasize importance/relevance/etc
  * e.g., use single values , derived values and thresh-
olds to show key data points at a glance;

1. For **transparency**, provide meta information:
  * e.g., state the data source , provide disclaimers
about how data were processed;
  * e.g., use tooltips or pagination if space is con-
strained;

1. **Avoid overflow structure in analytic dashboards** to facilitate
comparison;
   * e.g., use flat or paginated dashboards that fit encod-
ings on screen;

1. **Minimize repetitive data using abstraction** (to emphasize key data)
and parameterization (to support personalization );

1. **Consider the dashboard templates** best suited to the dashboard
audience and their informational needs, and use their characteristic
design patterns as a checklist for design. 

1. Try to ensure a **consistent color scheme** across the entire dash-
board, either by reusing colors for the same data and value, or by
creating a dedicated and clearly distinguishable scheme for each
visualization.

1. **Chose a layout that expresses relations between widgets**; following
a given schema , grouping by type or task , structured in a
table , or stratified to show important information on top


	○ T: Structure
			§ A good structure is informed by (i) data (facets, information), and tasks (overview, comparison).
			§ That structure needs to reflect structure in data and task
		○ Interaction 
			§ Interaction can be a powerful means to personalize, explore, navigate, and focus. 
			§ Minimize interaction: If you can solve something with minimal or no interaction, go for it.
		○ Dashboard templates
			§ Templates provide examples of dashboards in specific scenarios
			§ Use curated dashboards (static dashboard, magazine dashboards, infographic dashbaord) where to goal is to inform your audience without much intervention / interaction from their side.

