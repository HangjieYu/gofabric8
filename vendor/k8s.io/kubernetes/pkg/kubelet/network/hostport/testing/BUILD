package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
    "go_library",
    "go_test",
    "cgo_library",
)

go_library(
    name = "go_default_library",
    srcs = ["fake.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/kubelet/container:go_default_library",
        "//pkg/kubelet/network/hostport:go_default_library",
    ],
)
