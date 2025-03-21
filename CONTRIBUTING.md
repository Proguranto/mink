# Contributing

Some ways to contribute to mink:

- Try out the [examples](examples) and report any issue.
- Pick something you want to do with one of the many [robot descriptions](https://github.com/robot-descriptions/robot_descriptions.py) and write a new example.
- Find a use case that is not covered and write a unit test for it.
- Improve the documentation.
- Implement new tasks or constraints.

If any of those sound interesting, open an [issue](https://github.com/kevinzakka/mink/issues) and say you're on it!

## Documentation

If you're adding new functionality to `mink` and want to update the documentation, you can build it and visualize it locally using the following:

```bash
uv pip install -r docs/requirements.txt
sphinx-build docs _build -W
open _build/index.html
```
