import pandas as pd

tables = pd.read_html("https://central.blueplanet.com/quote-ui/#/quotes")

print(tables[0])
