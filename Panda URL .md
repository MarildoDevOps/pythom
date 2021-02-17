#coleta dados e cria data Set
import pandas as pd
url = pd.read_html('http//endereço alvo')
type(url)
len(url)
df = url[1]
df
