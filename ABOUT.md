## Contributors

This guide was put together over the course of several years by (in chronological order):

* Victor Schmidt
* Guillaume Alain
* Tristan Sylvain
* Tegan Maharaj
* Emmanuel Bengio
* Tristan Deleu
* Joey Bose

## Contributing

This is not meant to be a static guide. **You can contribute**.

To do so, just open a PR on the base repository: [`github.com/vict0rsch/tips-research-mila`](https://github.com/vict0rsch/tips-research-mila). You can do so by [forking](https://github.com/vict0rsch/tips-research-mila/fork) the repository.

### Guidelines

* Try to be succinct and explicit
* Put yourself in the shoes of the very diverse crowd of _new_ students: they come from different geographical, social, cultural and educational backgrounds.
* It's ok to have a different opinion from what's already there. If you can explain in a simple sentence why this is the case, it will be more helpful for more junior students.
* The documents are written in Markdown. If you're familiar with Sphinx, know that you'll also be able to use rst.
  * You can use rst-in-markdown with [MyST](https://myst-parser.readthedocs.io/en/latest/index.html).

```{note}
Yes this documentation could be `.rst`-only and not mix Markdown and ReStructuredText. But most people aren't actually familiar with the RST syntax so accessibility to new contributors prevailed.
```

### Building locally

The documentation is built and rendered automatically by ReadTheDocs.io.

If you want to contribute and see results for yourself, there's only 3 simple steps:

```bash
pip install -r requirements.txt
make html
open _build/html/index.html
```
