![30104573 small](https://user-images.githubusercontent.com/30104573/141884925-8b6e236a-8185-44fd-827a-ac8d72019a13.png)


I wrote this code for the associated book chapter:

Scott B. Lindstrom, (2020) The Art of Modern Homo Habilis Mathematicus, or: What Would Jon Borwein Do?. In: Sriraman B. (eds) Handbook 
of the Mathematics of the Arts and Sciences. Springer, Cham.

Maple's more user-friendly routines have significant drawbacks that can render them unable to plot certain functions. In particular, Maple 
cannot plot the Riemann zeta function over a Riemann sphere with the standard plot3d function. For the sake of simplicity, the larger 
package I developed with Paul Vrbik in 2017 relies on plot3d and similar functions. 

When I wrote the cited book chapter in 2020, I wanted to include a phase portrait of the Riemann zeta function plotted on the Riemann 
sphere. In order to create this image (which has since won an award and is in the gallery page), I wrote this new code. 

In this code, I built the PLOT3D data structure manually without calling the plot3d function. This allowed me to actually plot the Riemann 
zeta function. This bones-up approach comes at the expense of a pleasant interface, but the Maple worksheet is still relatively easy to 
adapt to other functions. 
