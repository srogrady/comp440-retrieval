# COMP 440: Representing and Retrieving Knowledge

Claude writes your answers here as you say them. A sentence or two is enough for each. Your
Part 0 predictions stay as you first wrote them; Part 5 asks what you would change.

**Name:** Shaylee
**Date:** 2026-10-21

## Part 0: Predictions

### Questions that name a character, place or thing: which method will do better, and why?

The TF-IDF method will do better on this search, because the question has specific key words that matter a lot to the movie

### Vague descriptions: which method will do better, and why?

Embedding search will tackle vague questions a lot better because it can gather some valueable information from very little

## Part 1: Build the TF-IDF model

### The settings you chose, and why

- `REMOVE_STOP_WORDS = True`: because it drops a lot of common low value words.
- `MIN_MOVIES = 2`: that will filter it a bit more, but it feels like that could over filter so I want to avoid that.
- `REPEATS_COUNT_LESS = True`: that will help give words weight which is valueable.

## Part 2: Top terms

### Your movies: what do the top terms get right and wrong about what makes each one distinctive?

They get the situations correct, and specific landmark items that are important to the setting, but they don't explain much about characters and barely have any words about how the movie feels or movie vibes.

## Part 3: Your own searches

### Your questions, as you typed them

1. There is a young orphaned boy who is told that he is a wizard and needs to go to school to learn about his powers and his parents legacy. He is brough to the school where he makes other kind wizard friends and learns more about parts of himself that he always wondered about. He is offered guidance and support but is threatened by evil people.
2. A very angry but funny man who happens to be very aggressive and have anger issues has to retire from his hockey career, but is taught by a kind golfer how to golf in hopes of winning money to pay off debts to save his mom from a bad retirement home. He falls in love with a reporter, and its all very funny but heartwarming.
3. A young girl has grown up on an island with her family who are royality on the island and she loves it there, but she is tired of hearing stories and staying on land when it is really the water and sailing that calls to her. She decides to make a change when she finds out that her island and all the islands are dying!

### Did the movies you meant come up? What did TF-IDF get right and wrong?

It go my first two movies correct (either teh first guess or the second) but my last movie wasn't on it's list. It was very good at getting settings correct. But it wasn't great when my answers were more vague which I had guessed earlier, or when my answers could make sense for a lot of movies.

## Part 4: The question bank

### Which kind of question did TF-IDF handle best, and which worst? By how much?

It does a good job handling detailed questions as that was where it was able to correctly indetify 18 movies first. It handled reworded or vague question worst getting zero right for those at all.

### The misses you looked at: what do they have in common?

The misses seem to be situations where some words are placed as important for the movie when they really don't correlate to that movie, and lead the prediction astray

## Part 5: Embeddings

### What is a sentence embedding, in your own words?

Sentence embedding in my words is the process of turning a word into a numerical list that holds meaning so that similar lists mean similar words. For tangled the words Flynn and theif would have similar lists as they are very closely related.

### Where does each method do better, and why?

the TF-IDF did better with specific recongizable names in movies, but embedding did better with not being lead astray by distinctive words that were incorrect. Embedding also did better more often.

### Your Part 0 predictions: which held, and which would you change?

Both my predictions hold I agree with those statements still and think that they were pretty much correct based on what I have seen.

### How might you combine the two methods?

I would combine them by have TF-IDF prehaps be a filtration for what words the embedding search encodes
