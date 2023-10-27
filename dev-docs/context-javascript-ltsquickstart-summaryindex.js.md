# Chat Engine

This code tutorial creates a list index and queries it. This example also use the LLMRetriever, which will use the LLM to select the best nodes to use when generating answer.

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

node summaryindex.js
```
