####Marikina Road Network with Variable Line Widths

The goal of this micro-project is to plot the road network of Marikina City in Metro Manila, Philippines.
However, instead of having a uniform line width for all roads, I wanted to vary the line width according
to the number of lanes for each given street. 

To implement this, I first had to convert all NaN and list values in the 'lanes' column of the street
geodataframe into integer values. Next, I had to map each lane number to a line width (via a simple scale).
Finally, I grouped the geodataframe by lane number, then plotted each group in a for loop with the
appropriate line width.

This micro-project was also a chance for me to tinker with `pyplot` functionalities, particularly in
customizing axis properties, particularly the background color, title, and legend.

Hope you enjoy!
