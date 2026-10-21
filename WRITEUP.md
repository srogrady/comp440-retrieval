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

XXXX

## Part 3: Your own searches

### Your questions, as you typed them

XXXX

### Did the movies you meant come up? What did TF-IDF get right and wrong?

XXXX

## Part 4: The question bank

### Which kind of question did TF-IDF handle best, and which worst? By how much?

XXXX

### The misses you looked at: what do they have in common?

XXXX

## Part 5: Embeddings

### What is a sentence embedding, in your own words?

XXXX

### Where does each method do better, and why?

XXXX

### Your Part 0 predictions: which held, and which would you change?

XXXX

### How might you combine the two methods?

XXXX
