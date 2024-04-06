python_requirement(
    name="pbipy",
    requirements=["pbipy"],
)

python_sources(name="lib")

pex_binary(
    name="bin",
    dependencies=[":lib"],
    complete_platforms=[":docker_python_311_amd64"],
)

python_tests(name="test")

files(
    name="docker_python_311_amd64",
    sources=["python_311_amd64.json"],
)
