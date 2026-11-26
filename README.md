*This project has been created as part of the 42 curriculum by tchemin.*

# Python Piscine

My exercises for the 42 Python piscine: eleven modules, from the basics to
object-oriented design and functional programming. Every exercise is typed
and checked with `flake8` and `mypy`.

## Modules

| Module | Theme | Highlights |
|--------|-------|------------|
| [module00](module00) | Python basics | functions, input, loops, recursion |
| [module01](module01) | Classes | encapsulation, inheritance, factories |
| [module02](module02) | Exceptions | built-in errors, custom errors, `finally` |
| [module03](module03) | Collections | lists, tuples, sets, dicts, generators |
| [module04](module04) | Files and streams | reading, writing, `with`, stdout/stderr |
| [module05](module05) | Abstract classes | ABCs, polymorphic data streams, pipelines |
| [module06](module06) | Packages and imports | the `alchemy` package, circular imports |
| [module07](module07) | Design patterns | card game: ABCs, factory, strategy, interfaces |
| [module08](module08) | Environments | virtualenvs, dependencies, `.env` config |
| [module09](module09) | Data validation | pydantic models and enums |
| [module10](module10) | Functional programming | lambdas, closures, `functools`, decorators |

## Run an exercise

Each script runs on its own:

```bash
python3 module00/ex0/ft_hello_garden.py
python3 module03/ex4/ft_inventory_system.py sword:1 potion:5 shield:2
```

module07 exercises are packages: run them from `module07/`:

```bash
cd module07 && python3 -m ex3.main
```

## Lint

```bash
flake8 .
mypy . --warn-return-any --warn-unused-ignores --ignore-missing-imports \
       --disallow-untyped-defs --check-untyped-defs
```
