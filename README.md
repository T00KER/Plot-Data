# Plot-Data
Plots data from CSV-file.
Settings specified in JSON-file.
### UNDER CONSTRUCTION ###

TODO:
1. Program different plot types:
    Most "urgent"/resonable:  plot, **scatter**, bar, contour(f), quiver, hist, **errorbar**, pie, (https://matplotlib.org/devdocs/plot_types/index.html)
2. Program exceptions/raise errors for wrongly configured JSON-files.
3. Program GUI (to choose and possible 'lock': CSV, JSON and output filename and path, to easily change and save JSON and run PlotData.py again to see new plot (or update plot every X seconds or have a refresh button)). Perhaps being able to change things for different yDatasets per subplot and then click save to save the settings to a new JSON file (Optimal: allt är GUI, läsa in CSV och pilla runt allt annat, sen spara konfig till JSON).
4. Small fixes: fix ratio between textsize and figure_width, and also line width and figure_width.


Note:
-JSON must be configured with UTF-8 encoding. Most notably for Swedish words is that 'å', 'ä', and'ö' must be encoded with "\u00e5", "\u00e4", and "\u00f6", respectively.
 -Headers in CSV must be unique (no duplicate headernames)
 -
### UNDER CONSTRUCTION ###
