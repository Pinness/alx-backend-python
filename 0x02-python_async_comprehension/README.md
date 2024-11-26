# Python Async Comprehension

This repository contains solutions to tasks related to asynchronous programming in Python. The tasks focus on using async generators and async comprehensions to handle asynchronous operations. The key concepts covered include:

- Async Generators
- Async Comprehensions
- Parallel Async Execution with `asyncio.gather`

## Task Descriptions

### 1. Async Generator

The first task requires creating an `async_generator` coroutine. This coroutine:

- Loops 10 times.
- Asynchronously waits for 1 second on each loop iteration.
- Yields a random number between 0 and 10 using the `random` module.

The expected output will be a list of 10 random numbers generated asynchronously.

### 2. Async Comprehension

The second task involves creating the `async_comprehension` coroutine. This coroutine:

- Uses async comprehension to collect 10 random numbers from the `async_generator`.
- Returns the collected random numbers.

The expected output is a list of 10 random numbers collected using async comprehension.

### 3. Measure Runtime for Four Parallel Comprehensions

The third task requires creating the `measure_runtime` coroutine. This coroutine:

- Executes `async_comprehension` four times in parallel using `asyncio.gather`.
- Measures and returns the total runtime for all four executions.

The expected output is the total runtime of the four parallel executions, which should be close to 10 seconds.

