# Lowlevel Modules  

This code tutorial uses several low-level components, which removes the need for an actual query engine. These components can be used anywhere, in any application, or customized and sub-classed to meet your own needs.

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