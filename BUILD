python_sources(name="lib")

pex_binary(
    name="bin",
    dependencies=[":lib"],
    complete_platforms=["3rdparty/platforms:docker_python_311_amd64"],
)
