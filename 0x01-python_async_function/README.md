# Python Async Function Tasks

This repository contains tasks related to Python asynchronous programming, using the `asyncio` module and coroutines. The tasks are designed to help understand async functions, concurrency, and managing multiple coroutines.

## Task 0: Basic Async Syntax
**File:** `0-basic_async_syntax.py`

This task involves writing an asynchronous coroutine called `wait_random`:
- Accepts an integer `max_delay` (default: `10`).
- Waits for a random delay between `0` and `max_delay` seconds.
- Returns the delay value as a float.

Example:
```python
import asyncio
from 0_basic_async_syntax import wait_random

print(asyncio.run(wait_random()))
print(asyncio.run(wait_random(5)))
print(asyncio.run(wait_random(15)))
Task 1: Concurrent Coroutines
File: 1-concurrent_coroutines.py

This task involves writing an asynchronous routine called wait_n:

Takes two arguments:
n: Number of times to spawn wait_random.
max_delay: Maximum delay for wait_random.
Returns a list of all delays in ascending order (without using sort()).
Example:

import asyncio
from 1_concurrent_coroutines import wait_n

print(asyncio.run(wait_n(5, 5)))
print(asyncio.run(wait_n(10, 7)))
print(asyncio.run(wait_n(10, 0)))
How to Run
To run the provided scripts:

Ensure you have Python 3.7+ installed.
Run the files using python3.
Repository
GitHub Repository: alx-backend-python
Directory: 0x01-python_async_function
Author

