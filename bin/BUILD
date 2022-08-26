package(default_visibility = ["//visibility:public"])
load("@requirements//:requirements.bzl", "requirement")

py_binary (
    name = "main",
    srcs = glob(["main.py"]),
    deps = [
      requirement('flask'),
      requirement('jinja2'),
      requirement('markupsafe'),
      requirement('werkzeug'),
      requirement('itsdangerous'),
      requirement('click'),
    ],
)
