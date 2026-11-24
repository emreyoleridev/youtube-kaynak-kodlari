# matplotlib 3.11 — Zero to Pro, in 1 video

Source code for the matplotlib course on the channel. Each notebook is one part of the video and runs on its own (parts 2+ start with a setup cell that repeats what the earlier parts defined).

| # | Notebook | What it covers |
|---|----------|----------------|
| 01 | [Why matplotlib?](01_why_matplotlib.ipynb) | What matplotlib is, the parts of a figure, and checking your version. |
| 02 | [Your First Plot](02_first_plot.ipynb) | Two lists, one line of code: our first line chart, and how plt keeps track of the current plot. |
| 03 | [Figure & Axes](03_figure_axes.ipynb) | The object-oriented style: fig, ax = plt.subplots(), and why we do everything through ax. |
| 04 | [Line Plots](04_line_plots.ipynb) | Colors, line widths, line styles, markers and a legend. |
| 05 | [Titles, Labels & Ticks](05_titles_labels.ipynb) | Titles, axis labels, ticks, limits, grid lines, spines and annotations. |
| 06 | [Scatter Plots](06_scatter.ipynb) | Two numbers per point: scatter, alpha, and a colormap with a colorbar. |
| 07 | [Bar Charts](07_bar_charts.ipynb) | Comparing categories: bar, barh, grouped bars, bar labels and a pie chart. |
| 08 | [Histogram & Box Plot](08_histogram_box.ipynb) | How values are spread out: histograms, bins and box plots. |
| 09 | [Subplots & Layouts](09_subplots.ipynb) | Several charts in one figure: subplots, shared axes and subplot_mosaic. |
| 10 | [Styles & Colors](10_styles_colors.ipynb) | Built-in styles, the default color cycle and colormaps. |
| 11 | [Images](11_images.ipynb) | Showing 2D data as an image with imshow and a colorbar. |
| 12 | [Saving Figures](12_saving.ipynb) | savefig: PNG, SVG and PDF, dpi, tight bounding boxes and a transparent background. |
| 13 | [Common Mistakes](13_common_mistakes.ipynb) | Errors you will hit when copying old tutorials, and how to fix each one. |
| 14 | [Mini Project: Netflix Dashboard](14_mini_project.ipynb) | Four charts, one page: a Netflix overview dashboard from the clean dataset. |

## Requirements

- Python 3.10+
- `pip install -U matplotlib numpy pandas`

The notebooks were run with matplotlib 3.11.2.

## Dataset

From part 7 on we use the clean Netflix table saved at the end of the pandas course: [`data/netflix_clean.csv`](../data/netflix_clean.csv). The notebooks read it straight from the URL, so no download is needed.
