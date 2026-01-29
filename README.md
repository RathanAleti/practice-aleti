# practice-aleti

# RATHAN REDDY ALETI 
###### Imagine Dragons

I like Imagine Dragons because their music is very motivating and easy to connect to. Their songs have strong beats and meaningful lyrics that talk about confidence, struggles, and never giving up. I also like how their music mixes rock and pop, which makes it exciting to listen to while **studying** or **working out**.

---

## Favorite Musicians
1. Kid Cudi
2. Kanye West
3. Imagine dragons

### Favorite Books
- Atomic Habits
- Rich Dad Poor Dad
- Can't Hurt Me

[My Favorite Location](Nyc.jpeg)

---

## Places I Want to Visit

Below is a table of places I would like to visit in the future.

| Place | Reason | Distance | Budget ($) |
|------|--------|----------|------------|
| Tokyo | Technology & culture | 6700 miles | 2500 |
| Paris | History | 4000 miles | 2200 |
| Dubai | Modern city | 7600 miles | 3000 |
| Rome | Ancient history | 4800 miles | 2100 |

---

## Favorite Lyrics

> "I'm waking up to ash and dust, I wipe my brow and I sweat my rust"  
*— Dan Reynolds*

> "Whatever it takes, 'cause I love the adrenaline in my veins"  
*— Dan Reynolds*



---

## Python Code Snippet: Flattening a Nested List

This Python function takes a nested list and recursively flattens it into a single list.  
It checks whether the list is empty and whether the first element is another list, then processes each element until the entire structure is flattened.

```python
def flatten_list(nested_list):
    if not bool(nested_list):
        return []

    if isinstance(nested_list[0], list):
        return flatten_list(nested_list[0]) + flatten_list(nested_list[1:])

    return nested_list[:1] + flatten_list(nested_list[1:])


- 
Here is  my Link : https://python.pieces.cloud/?p=b1fe48bde9
