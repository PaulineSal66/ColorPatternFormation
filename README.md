# NETLOGO PROJET - Color Pattern Formation with 3 colors

**I do not allow the sharing of my project.**

## Main question
How patterns are formed in animals is still unclear and more specifically those concerning color pattern. 
Here the project aims to understand this question. 
Patterns in animals have been shown to rely on the current reaction diffusion Model proposed by Alan Turing.
Until now, most of the agent based modelling of color pattern formation relies on two type of pigment cells: xanthophores and melanophores.

Here, I propose to add another pigment cell : the pigment which give the white/blue hue in fishes.
The goal is thus too understand how 
	
1) the proportion of each type of these 3 pigment cells, and

2) the distance parameters to trigger short and long range interactions influence the formation of the pattern.

Of course some informations are missing such as cell division, cell death, etc. However, for simplicity, I prefered to understand how a color pattern is formed 
depending only on cell-cell interactions (attraction and repulsion depending on short or long range interactions).

## The project
Let's imagine that we put in a plate the three types of pigment cells (xanthophores, melanophores, iridophores), how the parameters described above 
will influence the formation of the pattern?

## Description of the model
- i created three types of turtles: xanthophores, iridophores, melanophores which respectively correspond to orange, white/blue and black cells 
- The initial grid is empty
- We can initialize: 1) the distance corresponding of the short and long range interactions 2) the number of each pigment cell type
- The SETUP button randomly initializes the coordinates of each cell
- The GO SETUP allows to move each type of pigment cells depending on properties described in Salis et al., 2019 and Patterson et al., 2013 (the interactions are describe within the netlogo code).

## Bibliography
- [Patterson, Parichy. Interactions with Iridophores and the Tissue Environment Required for Patterning Melanophores and Xanthophores during Zebrafish Adult Pigment Stripe Formation. 2013. PLoS Genetics.](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1003561)
- [Salis, Lorin, Laudet, Frédérich. Magic Traits in Magic Fish: Understanding Color Pattern Evolution Using Reef Fish. 2019. Opinion in Trends In Genetics.](https://www.sciencedirect.com/science/article/abs/pii/S0168952519300162)