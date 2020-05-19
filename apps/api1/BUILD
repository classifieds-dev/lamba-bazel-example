load("@io_bazel_rules_go//go:def.bzl", "go_binary")
go_binary(
    name = "api1",
    srcs = ["main.go"],
    importpath = "lamba_bazel_example/apps/api1",
    goos = "linux",
    goarch = "amd64",
    deps = [
        "@com_github_aws_aws_lambda_go//:go_default_library",
    ],
)