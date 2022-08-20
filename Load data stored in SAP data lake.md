Create a `Pandas` DataFrame consisting of the loaded dataset stored in the data lake of `SAP DI`

```python
client = hdfs.InsecureClient('http://datalake:50070')
with client.read('worm/clean.csv', encoding='utf-8') as reader:
    df = pd.read_csv(reader, sep=',')
```
