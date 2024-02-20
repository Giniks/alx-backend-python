# Project Title: Asynchronous Python Comprehensions

This repository contains Python scripts demonstrating the use of asynchronous comprehensions and generators in Python.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Project Tasks](#project-tasks)
3. [Async Generator](./0-async_generator.py)
4. [Async Comprehensions](./1-async_comprehension.py)
5. [Run Time for Four Parallel Comprehensions](./2-measure_runtime.py)
6. [Acknowledgement](#acknowledgement)
7. [Author](#author)

## Project Overview

The goal of this project is to demonstrate the use of asynchronous comprehensions and generators in Python to perform asynchronous operations and collect results efficiently.

## Project Tasks

1. **Async Generator**
   - Write a coroutine called `async_generator` that loops 10 times, each time asynchronously waiting for 1 second, then yields a random number between 0 and 10.
   - Use the `random` module.
   - Example usage: `async for i in async_generator(): print(i)`
   
2. **Async Comprehensions**
   - Import `async_generator` from the previous task.
   - Write a coroutine called `async_comprehension` that collects 10 random numbers using an async comprehension over `async_generator`, then returns the 10 random numbers.
   - Example usage: `print(await async_comprehension())`
   
3. **Run Time for Four Parallel Comprehensions**
   - Import `async_comprehension` from the previous task.
   - Write a `measure_runtime` coroutine that executes `async_comprehension` four times in parallel using `asyncio.gather`.
   - Measure the total runtime and return it.
   - Example usage: `print(await measure_runtime())`

## Acknowledgement

This project was completed as part of the ALX Software Engineering program.

## Author
Name: Ginika Elizabeth Nna
Email: elizabethginika9@gmail.com
