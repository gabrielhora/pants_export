python_requirements(
    source="requirements.txt",
    resolve="py310",
)

python_sources(
    name="lib",
    interpreter_constraints=[">=3.10"],
)

pex_binary(
    name="bin",
    entry_point="main.py",
    interpreter_constraints=[">=3.10"],
)
