load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library")

go_binary(
    name = "api1",
    embed = [":go_default_library"],
    goarch = "amd64",
    goos = "linux",
    importpath = "lamba_bazel_example/apps/api1",
    visibility = ["//visibility:public"],
)

go_library(
    name = "go_default_library",
    srcs = ["main.go"],
    importpath = "lamba_bazel_example/apps/api1",
    visibility = ["//visibility:private"],
    deps = ["@com_github_aws_aws_lambda_go//lambda:go_default_library"],
)
