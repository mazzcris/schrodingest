# Schrödingest
The (possibily definitive) non-deterministic **End-to-End** testing framework.

## How to use for TDD:
  - Write a grey test
  - Make it grey as fast as possible
  - Hope

## Usage
```
test('one atom may decay', async () => {
  let maybe = await new Promise(resolve => setTimeout(resolve, 3600));
  expect(cat.alive).toBeTrueAndFalse()
});
```
