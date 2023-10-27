
# This is the Quickstart

This is the first code tutorial of 8.  This code tutorial will allow you to create a vector index and query it. The vector index will use embeddings to fetch the top k most relevant nodes. By default, the top k is 2.


To get started cd into the first sample directory:

`
```devdocs_run

cd javascript/ltsquickstart

```

Now before we can run this project we have to export an <code>OPENAI API_KEY</code>, if you already exported your API_KEY feel free to skip this step.

```

export OPENAI_API_KEY=YOUR OPENAI API KEY

```


Thats it! Now run the project and it will answer questions on the <code>text/essay.txt</code> file which you can even replace with your own contents. Run this command below:

```devdocs_run

node ltsquickstart.js

```
