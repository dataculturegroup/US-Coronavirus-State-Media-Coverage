Coronavirus Coverage by State
=============================

A quick investigation into coronavirus coverage by state in the US. This pulls news data by state from 
[Media Cloud](https://mediacloud.org) (using the US [geographic collections](https://sources.mediacloud.org/#/collections/country-and-state)),
and gets coronavirus incidence data from [John Hopkins](https://coronavirus.jhu.edu). It charts the percentage of media attention
in each state being paid to the coronavirus pandemic over time.

## Setup

1. Setup Python 3 and Jupyter Notebooks. This is no small task; if you are new I suggest installing via Conda.
2. Create a `.env` file in this directory and put your Media cloud API key in like this: `MC_API_KEY=12344567890`
3. You need to install a web browser engine for exporting Bokeh charts to SVG. On Mac try this to install [chromedriver](https://chromedriver.chromium.org/downloads):`brew cask install chromedriver`

## Running

All the data from my version is committed here, under the `data` directory. You can run the notebook yourself - just run through
the cells in the `corona-by-state` notebook to regenerate it all, and you'll end up with some CSVs and pretty charts 📉👏🏾.

## Notes

This was created by Rahul Bhargava ([@rahulbot on Twitter](https://twitter.com/rahulbot)).

I was inspired by this [tweet from Tyler Dukes](https://twitter.com/mtdukes/status/1270841633026826246) to compare the new coronavirus 
case rate and the media attention paid to the pandemic.
