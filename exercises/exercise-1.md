## Session 1 Exercises (Duration: 10-15 minutes)

Use the OpenAI playground to complete the exercise below. Use the slides or notebooks for tips and guidance. 

1) Test the prompt below and try different temperature values. Try with high temperature values and a temperature value of `0`. Do you see any differences in the outputs?

```
The ski is
```

2) Modify the prompt below to instruct the model to explain the paragraph in one sentence like "I am 5". Do you observe any differences in language style?

```
Antibiotics are a type of medication used to treat bacterial infections. They work by either killing the bacteria or preventing them from reproducing, allowing the body's immune system to fight off the infection. Antibiotics are usually taken orally in the form of pills, capsules, or liquid solutions, or sometimes administered intravenously. They are not effective against viral infections, and using them inappropriately can lead to antibiotic resistance. 

Explain the above in one sentence:
```

3) Modify the prompt below to elicit the model to respond that it isn't sure about the answer. 

```
Answer the question based on the context below. Keep the answer short and concise. Respond "Unsure about answer" if not sure about the answer.

Context: Teplizumab traces its roots to a New Jersey drug company called Ortho Pharmaceutical. There, scientists generated an early version of the antibody, dubbed OKT3. Originally sourced from mice, the molecule was able to bind to the surface of T cells and limit their cell-killing potential. In 1986, it was approved to help prevent organ rejection after kidney transplants, making it the first therapeutic antibody allowed for human use.

Question: What was OKT3 originally sourced from?

Answer:
```

4) Modify the prompt below to instruct the model to provide an explanation to the answer selected.

```
Classify the text into neutral, negative or positive.

Text: I think the food was okay.

Sentiment:
```

5) Modify the prompt below to instruct the model to keep AI responses concise and short. 

```
The following is a conversation with an AI research assistant. The assistant tone is technical and scientific.

Human: Hello, who are you?
AI: Greeting! I am an AI research assistant. How can I help you today?
Human: Can you tell me about the creation of blackholes?
AI:
```

6) Use the poem below to create a prompt that instructs the model to extract all the verbs from the abstract, including the number of verbs found. 

```
Deep into that darkness peering,

Long I stood there, wondering, fearing,

Doubting, dreaming dreams no mortals

Ever dared to dream before;

But the silence was unbroken,

And the stillness gave no token,

And the only word there spoken

Was the whispered word, "Lenore!"

This I whispered, and an echo

Murmured back the word, "Lenore!"

Merely this, and nothing more.
```

7) Build a few-shot prompt with 5 demonstrations. The task is to classify a text into either positive or negative. Try using the format below. You can use your own format if you prefer.

```
<instruction>

<sentence 1> // <label>
<sentence 2> // <label>
<sentence 1> // <label>
<sentence 1> // <label>
<sentence 1> // <label>

<sentence to classify>

<output indicator>
```

8) Try to improve the following prompt using chain-of-thought prompting. Feel free to review the slides if you get stuck.

```
Adding all the numbers in odd positions will add up to an even number: 4, 8, 9, 15, 12, 2, 1.
```

9) Test zero-shot CoT prompting, "Let's think step-by-step", on the same prompt above and observe if it helps to elicit an accurate response from the model. Think of any way you can improve the consistency further.

```
Adding all the numbers in odd positions will add up to an even number: 4, 8, 9, 15, 12, 2, 1.
```

10) Below is a description of a made-up event. Prepare a prompts that extracts information like what the event is about, name of event, date, activities, location, etc. Try to elicit the model to extract concise answers like "July 15th to July 16th" when asking for the event date. In addition, format the response as a JSON object in the following format: `[{"key":"value"},{"key":"value"},...{"key":"value"}]`. Use the example in `demo-1.3.ipynb` for inspiration on how to compose your prompt.

```
Summer Beats Festival

The event will be held at the beautiful seaside location of Ocean Park in Miami, Florida.

The festival will take place over two days, from July 15th to July 16th.

The Summer Beats Festival will feature a fantastic lineup of popular musical artists and bands from a variety of genres. Attendees can expect to dance and sing along to live performances from headliners such as Taylor Swift, Bruno Mars, and Post Malone. In addition to the main stage, there will be several smaller stages scattered throughout the park featuring up-and-coming artists and DJs.

The festival will also offer a wide variety of food and drink options for attendees to enjoy. From classic festival fare like hot dogs and funnel cakes to more gourmet offerings like sushi and craft beer, there will be something to suit every taste.

Families with children are welcome, and there will be plenty of activities to keep the little ones entertained. The festival will offer a dedicated children's area with carnival games, face painting, and other fun activities.

For those looking for a more luxurious experience, the Summer Beats Festival will also offer a VIP area with premium viewing of the main stage, private bars, and lounges, and other exclusive perks.

Overall, the Summer Beats Festival promises to be an unforgettable event for music lovers of all ages. With a stunning location, a great lineup of artists, and plenty of activities and amenities, it's sure to be the highlight of the summer!
```