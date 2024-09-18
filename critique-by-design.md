| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Design Critique with Tableau
The following page is a critique of data from the Makeover Monday website that works with given data to create more effective visualizations. The data visualization chosen for this activity was [Global Energy Consumption by Source](https://ourworldindata.org/grapher/global-energy-substitution?time=1800..2023) 


## Step one: the visualization

The following image is the original visualization produced by the [Energy Institute](https://ourworldindata.org/grapher/global-energy-substitution?time=1800..2023) that was used for this critique and redesign process. 

Note that there are features such as the 'play' button that starts the time lapse, the hyperlink-like definitions in the title (In the image below, the definitions are under the visualization instead), as well as the area in which users can hover over and see the total yearly energy use with the breakdown of each source. These are limitations to the redesigned visualization that is presented at the end of this page. 

![](global-energy-substitution.png)

### Citation
Energy Institute - Statistical Review of World Energy (2024); Smil (2017) – with major processing by Our World in Data. “Primary energy from biofuels” [dataset]. Energy Institute, “Statistical Review of World Energy”; Smil, “Energy Transitions: Global and National Perspectives” [original data].


## Step two: the critique

This visualization presents a large amount of data, and at first, one may think that they fully understand what this all is trying to show. The critique below was inspired by the [Data Visualization Effectiveness Profile](https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) by Stephen Few. 

Before starting the redesign process, I critiqued the data myself. The following are observations and questions that I had concerning the 
The first aspect of the visualization that I recognized was the time-lapse button that can be played to display changes in energy source consumption over time. I noticed from here that the title is not indicative of the data, and so I would add the years represented in the title as (1800-2023). Though I appreciate the idea of the time lapse, something that did not work well was how fast the lapse was. At the beginning until 1880, coal and traditional biomass were the only energy sources, but then as soon as it added more, the lapse did not slow down and I had to stop it and move the dial to see what was actually happening. For me, this felt like the lapse was useless and I immediately thought that a line chart might be more useful. In addition to the line chart idea, the use of color here was fine, but the space is an issue because you are barely able to see the less used energy sources such as ‘other renewables.’ Given that this is a visualization with time as its X axis, I would move this to a line chart. The labels of energy sources for the most part are fine, however the use of ‘traditional’ and ‘modern’ biomass are not useful and could be confusing for those not familiar with those energy sources. Given that there is not a lot of space to explain this, something that was useful on the visualization was the use of a hyperlink-like pop-up box that explained the ‘substitution’ method’ for energy and the definition of terra-watt hours. I was surprised that it gave a relatively simple definition of what a watt was, and felt that this was a good addition to have with the data, and I would add definitions for modern and traditional biomass in this way. Lastly, though I might not be able to figure this out, I would define what ‘other renewables’ means.

Generally, this visualization is for those who are interested in global energy trends, with a focus on those working in the energy industry, policy makers, and even environmentalists. As someone that falls into this demographic, I feel that it was relatively easy for me to understand everything, however knowing that I fit the primary audience for this visualization, I was aware of some aspects of it that I knew would not be digested easily by others. Something that made me think about the audience is: who would care what energy consumption looked like in the 1800s? Personally, I think it’s interesting, but from a policy standpoint I was thinking about how it could be used, and I don’t think it’s a necessary or even effective aspect of this visualization given the audience I think it’s supposed to reach.


## Step three: Sketch a solution
The following was created in Tableau and is the first redesign of the original [Energy Institute](https://ourworldindata.org/grapher/global-energy-substitution?time=1800..2023) data 

<div class='tableauPlaceholder' id='viz1726675168198' style='position: relative'><noscript><a href='#'><img alt='Yearly Global Energy Use from 1900-2023 (total energy use per year and source) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;Redesign1&#47;YearlyGlobalEnergyConsumptionbySource&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Redesign1&#47;YearlyGlobalEnergyConsumptionbySource' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;Redesign1&#47;YearlyGlobalEnergyConsumptionbySource&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726675168198');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>




## Step four: Test the solution

This section was used to get critique of the redesign of the original visualization. 

Questions to ask (modify these for your own interviews): 

- What do you think this is? 

- What do you think this visualization is trying to share? 

- Is there anything you find confusing?

- Who do you think the intended audience for this is?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

