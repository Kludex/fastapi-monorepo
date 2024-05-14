python_requirements(
    name="root",
    overrides={
        "uvicorn": {"dependencies": [":root#uvloop", ":root#httptools"]},
    },
)

docker_environment(
    name="python_slim", platform="linux_arm64", image="python:3.12.2-slim"
)
