workspace(name = "sudoku_solver")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "rules_python",
    sha256 = "778197e26c5fbeb07ac2a2c5ae405b30f6cb7ad1f5510ea6fdac03bded96cc6f",
    urls = ["https://github.com/bazelbuild/rules_python/releases/download/0.2.0/rules_python-0.2.0.tar.gz"],
)

load("@rules_python//python:pip.bzl", "pip_install")

pip_install(
    name = "requirements",
    requirements = "//:requirements.txt",
)
