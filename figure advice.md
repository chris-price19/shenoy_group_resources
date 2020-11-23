In more detail:

1) Write down a theme for each figure. So figure 1 would be 'schematic for polymer model for heterochromatin with HP1'. This is the figure title. 
2) Next write down what you are going to show in each panel of the figure (a, b, c, etc.) to illustrate the model.  The figures should be able to present themselves without any explanation. So you want someone to be able to figure out what's going on without reading or requiring any explanation. This is also basically what prof. does when he is reviewing figs.
3) Use previous group papers (https://www.biorxiv.org/content/10.1101/2020.04.15.043802v2.full.pdf) which are simulation-only as templates for figures and get ideas on how to display things.

In this model, I think the main point is that you are emphasizing that binder-binder interactions are required along with the polymer potential to correctly model chromatin from a bottom up approach. I think in figure 1 you want to show different types of polymer phase separation - maybe 3 panels. polymer by itself, polymer with binders and no interactions, and polymers with binders and binder-binder interactions. You also need to be specific, 'modified' and 'original' model are too vague. In figure 1 you want to be showing what the components are that contribute to the free energy expression since that is the core of the model.

Then, before you show experimental comparisons, you want to explore the model more thoroughly. Fig 1 should be cartoons about phase separation and how that's relevant to the cell. Fig 2 and 3 should be the phase diagrams for the model, to show in which regions you get phase separation. you might even want to include phase diagrams without the binder - binder interactions to emphasize that these are important, and highlight what is changing and what is new. You can also show convergence plots here but these will probably go to supplemental at the end of the day.

Lastly, figures 4 and 5, you want to compare the observables with experiment. 1D contact probability, 2D contact probability, the coil-globule transition, radius of gyration vs. concentration, etc. I would show how the scaling exponents change as a function of the model parameters, i.e. making another 'phase diagram' in parameter space. Here you could add in the mechanical degrees of freedom, i.e. plotting the contact probability power law exponents as a function of volume and shape of the nucleus.

Tips:
- Make a folder for each figure. Then put an illustrator or inkscape file for each figure in the folder that's specific to that figure. For plots, you can put a separate python script in each folder, or use a jupyter notebook where each cell corresponds to a plot, and then save those plots to the correct folder. The jupyter method is nice because you can use the same data in multiple figures. 

- Sizing: set your document units to be the same as the figure sizes for a journal. When you are making figures, you will make a lot of iterations and it takes a lot of time. You want to minimize the amount of duplicate work that you have to do, so you should set the size of things to be what they will ultimately be in order to publish. Most single column figures are 3.25" wide, and up to 9" high. Full page width figures are 7" by 9".

- Also in the theme of not duplicating work - no powerpoint objects. You should try to make everything in illustrator or inkscape, arrows, text labels, etc. This might be more work up front but it will save you a ton of time in the long run. Every iteration you make, you do not want to be going through several programs to get to the final result. The time spent learning illustrator will be worth it.

- Minimize whitespace. There is a ton of whitespace in all the figures. In matplotlib, use plt.tight_layout() before you print to clean up whitespace. I often end up cropping borders off plots to push them together. In the cartoons, you need to minimize white space as much as possible.

- Use arrows judiciously. In fig 1, you have arrows pointing to labels, you could just place the label next to the object and achieve the same thing. Arrows are necessary sometimes but you need to be really careful about not using too many or it gets confusing.

- In powerpoint, I would also convert your slides to portrait mode so that they display like they will in a paper. Ultimately you are making figures for a journal article so you should set everything up towards this goal.
