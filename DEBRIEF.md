# Hubspot meetings challenge - Debrief

## Code quality and readability

- Code repetition (looping thru results, detect if created/modified). Could be handled in helper methods
- Poor abstraction for concurrency/queue usage
- Unclear names and no comments to clarify
- Passing around objects then looping inside them to find the item from the outer loop

## Performance

- Concurrecy values very high
