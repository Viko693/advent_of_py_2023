# Advent of Code 2023

This repository contains my solutions to the "Advent of Code 2023" challenges, written in Python using only the standard libraries.

## Project Structure

Each day's challenge is organized in its own directory, with a consistent structure for ease of navigation and maintainability:

- `dayXX/` - Contains the solution and input for each day's challenge (`XX` is the day number).
  - `dayXX.py` - Python script with the solution for the day.
  - `input.txt` - Input data for the challenge.
- `utils/` - Contains reusable code modules used across different days.
- `tests/` - Contains unit tests for the daily challenges.
- `main.py` - Main runner script that can execute code for any given day (optional).
- `README.md` - This documentation file.

## Running the Solutions

To run the solution for a specific day, navigate to the corresponding directory and run the Python script. For example, for Day 1:

```bash
cd day01
python day01.py
```

## Tests

Unit tests are written using Python's built-in unittest framework. To run the tests for a specific day:

```bash
python -m unittest tests/test_dayXX.py
```

Replace XX with the day number.

## Contributing

Feel free to explore the solutions and provide feedback or suggestions. If you find any issues or have questions, please open an issue in this repository.

## License

[MIT License](https://opensource.org/license/mit/)

## Acknowledgements

Advent of Code 2023: [https://adventofcode.com/2023](https://adventofcode.com/2023)

Project inspired by the AoC community and my love for problem-solving.

Happy Coding!



