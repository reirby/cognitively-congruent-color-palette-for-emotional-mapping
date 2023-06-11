This is the code that runs at the backend of the color picker app at https://colors4emotions.tk/

It uses linear programming solver from the 'pulp' library to generate an optimal assignment of colors based on the built in weighted data for the received list of emotions.
It then returns the resulting color palette in 2 formats.
