# MC-Project-AST305

Code for the Monte Carlo project for the AST305 course, where we use this numerical method to compute the Kroupa (2002) IMF, and make simulations for 1e2 - 1e6 number of stars and see how the remnant masses distribute in the different types of remnant objects according to different mass limits given mainly by the Kalirai et al. (2008) and Raithel et al. (2018). 

![flowchart](https://github.com/user-attachments/assets/5ebfca8f-6158-4433-9119-a7fae96bc93e)


First, the IMF is defined and, since we are utilizing the Monte Carlo numerical method, it has applied to it statistical weights according to the mass. As it is necessary, a constant SFR is made up, and then for each mass an age is assigned from this SFR that covers the age of the Milky Way. Later, utilizing the mass-luminosity relation for the MS taken from the guide, we can calculate the lifetime in the MS for each star and, since it depends on its mass, some of them can be catalogued as remnants, and to those, we take the equations from Kalirai et al. (2008) and Raithel et al. (2018) to classify them in the three main groups of remnants: White Dwarfs, Neutron Stars and Black Holes. Finally, a series of graphics and histograms are made to see the proportions and distributions of the masses and ages for these groups.
