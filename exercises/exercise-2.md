## Session 2 Exercises (10-15 minutes)

Try to complete as many of the exercises below. Use the OpenAI playground for this exercise or the `demo-1.1.ipynb` notebook.


1) Modify the prompt below to include demonstrations. Include this as a `input_variable`. Make sure include some examples and test that it works.

```python
multiple_template = """
You are sentiment classifier. You are given a sentence and you need to classify it as {labels}. 

Classify the following sentence: {sentence}
"""

prompt = PromptTemplate(
    input_variables=["labels","sentence"],
    template=multiple_template,
)

prompt.format(labels=["positive","negative"],sentence="This is splendid!")
```

2) Build a few-shot template that can generate `<sentence, sentiment_label>` pairs. Make sure to use to pass a few demonstrations as part of the prompt.

3)
4)
5)
6)
7)
8)
9)
10)
