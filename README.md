import pandas as pd

calls_df, = pd.read_html("https://central.blueplanet.com/quote-ui/#/quotes", header=0, parse_dates=["Call Date"])

print(calls_df)
