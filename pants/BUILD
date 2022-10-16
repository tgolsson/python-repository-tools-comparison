python_requirement(
    name="torch_gpu",
    requirements=["torch==1.10.2+cu111"],
    resolve="gpu",
)

python_requirement(
    name="torch_cpu",
    requirements=["torch==1.10.2+cpu"],
    resolve="python-default",
)

python_requirements(
    name="cpu",
    module_mapping={"box2d": ("Box2D",)},
    source="requirements.txt",
    resolve="python-default"
)

python_requirements(
    name="gpu",
    module_mapping={"box2d": ("Box2D",)},
    source="requirements.txt",
    resolve="gpu",
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
