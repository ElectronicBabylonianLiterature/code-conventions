# eBL Coding Standards

## General

- Write [clean code](https://www.amazon.de/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882). Use linters and analysers to find code smells.
- Use up to date technologies. E.g. Python 3 instead of Python 2.
- Use a deterministic package manager. E.g. [yarn](https://yarnpkg.com/lang/en/) or [pipenv](https://docs.pipenv.org/).
- Write tests for your code. Test Driven Development is recommended but not mandatory. There is no hard requirement for code coverage but it should improve over time.
- Prefer a single branch workflow. If branches are needed use [GitHub Flow](https://guides.github.com/introduction/flow/).
- Implement a proper domain model. Avoid passing data around in dictionaries.
- Prefer immutable value objects. [attrs](https://attrs.readthedocs.io/) and [Immutable](https://immutable-js.github.io/immutable-js) make the task easier.
- Update this documentation if an issue which is not covered arises.
- When contributing to projects outside eBL adhere to their standards.

## JavaScript

- Use [JavaScript Standard Style](https://standardjs.com/).
- Stick to the [good parts](https://smile.amazon.de/JavaScript-Parts-Working-Shallow-Grain/dp/0596517742).

## Python

- Use [PEP 8 style](https://pep8.org).

## HTML/CSS

- Try to use semantic HTML.
- Use [BEM](http://getbem.com/) naming convention. 
