# Custom Vector Index Quickstart

This code tutorial creates a vector index and queries it, while also configuring the the LLM, the ServiceContext, and the similarity_top_k.

Make sure you are still in the <code>javascript/ltsquickstart</code>

Also just make sure the OPENAI KEY is still exported:

```devdocs_run

echo $OPENAI_API_KEY

```

If you do not see export it again like so:

```
export OPENAI_API_KEY=YOUR KEY
```


If all those steps are good run(Note this can take a minute or two)


```devdocs_run

node customizedvectorindex.js

```
