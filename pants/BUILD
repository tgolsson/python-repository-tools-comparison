python_requirements(
    name="python-default",
    module_mapping={"box2d": ("Box2D",)},
)

python_requirements(
    name="root",
    source="tool-requirements.txt"
)

pex_binary(
    name="gsutil",
    script="gsutil",
    dependencies=[
        ":python-default#gsutil"
    ]
)
