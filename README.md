# AMSI Optimise 2019 - Optimising Crop Rotation Schedules

### Alysson M. Costa and Simon Bowly

In the first part of this hands-on session, we will present a crop rotation problem in the context of sustainable vegetable production. We will develop a compact mixed-integer programming model, which will be implemented and solved with free online optimisation tools (JuliaBox/JuMP/Cbc).  In the second part, the crop rotation model will be extended to include plot area planning in order to satisfy required demands.  The new formulation has a large number of variables and we will present and implement a delayed column generation method for the efficient obtention of solutions.

We'll go through the formulation and the code in detail during the workshop.
Here we've provided a jupyter notebook which steps through the Julia/JuMP code required to model and solve the problem.

Try it out and follow along using JuliaBox:

1. Go to https://juliabox.com/
2. Log in/Create an account
3. At the JuliaBox Dashboard, click on Git
4. Add the repository url: `http://github.com/simonbowly/AMSI-2019-Crop-Rotation.git`
5. Click the + sign (add to JuliaBox, takes a little while)
6. Close the dialog and click Launch
7. In Jupyter, go to newly created directory `AMSI-2019-Crop-Rotation`
8. Open `Crop Rotation Tutorial.ipynb`

You can follow through the formulation we are presenting by running each code cell in sequence.
Use Shift+Enter to run each cell.
