For Developers
==============

Thank you for your interest in making ``napari-matplotlib`` better!
Contributions are very welcome!

This might be obvious but any contributions to the codebase will be licensed according to XXX

Issues and pull requests
------------------------

If you encounter a bug please `file an issue <>` along with a detailed description and the steps to reproduce the problem.
Please make issues for any bugs even if you know how to fix them: this helps reviewers understand what the problem is.
If you want to suggest a new feature or functionality please also `file and issue` and the maintainers will chat to you.
We've tried to encourage `Third-party plugins` so you might be able to extend the functionality with your own plugin.

For small typos and changes that aren't bugs, please just open a pull request directly.

To open a pull request, `fork <>` the repository, and make your changes to your fork.
If you introduce code, in particular any new functionality, please ensure you've added tests ahd that the `coverage <>` at least stays the same.
Also ensure that you document any new functions (we use XXX style docstrings),


Building and testing the documentation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can test the documentation build locally, we have a `Makefile <>` in the ``docs/`` folder.

```
cd docs/
make html
echo $PWD/_build/html/index.html
```

then browse to the location in your favourite browser.
If you've added a function, please check the function documentation looks ok (navigate to API...).

Tox
~~~

Instructions how to run tox


Pre-commit
~~~~~~~~~~


Changelog
---------

User-facing changes (changes to the way users interact with the plugin) should be noted in the changelog.
We use the "needs changelog" label in GitHub to denote


Release procedure
-----------------

Maintainers with push permission can tag a commit of the ``main`` branch with a tag following `semantic versioning` with the leading ``v``.
