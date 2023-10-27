# SubQuestionQueryEngine

This code tutorial uses the `SubQuestionQueryEngine`, which breaks complex queries into multiple questions, and then aggreates a response across the answers to all sub-questions.

Make sure you are still in the <code>javascript/ltsquickstart</code>

Also just make sure the OPENAI KEY is still exported: 

```devdocs_run

echo $OPENAI_API_KEY

```

If you do not see export it again like so:

```
export OPENAI_API_KEY=YOUR KEY
```


If all those steps are good run


```devdocs_run

node subquestion.js

```
