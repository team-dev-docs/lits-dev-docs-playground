# Custom Vector Index Quickstart

This code tutorial creates a list index and query it. This example also use the LLMRetriever, which will use the LLM to select the best nodes to use when generating answer.

Make sure you are still in the <code>javascript/ltsquickstart</code>

Also just make sure the OPENAI KEY is still exported:

```devdocs_run

echo $OPENAI_API_KEY

```

if not exported again mentioned in prior page for <code>ltsquickstart.js</code>


If all those steps are good run(Note this can take a minute or two)


```devdocs_run

node storagecontext.js
```

If it is your first time running this project you should see a new mini folder called storage.


Create a vector index and query it, while also configuring the the LLM, the ServiceContext, and the similarity_top_k.