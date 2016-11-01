load("@protobuf//:protobuf.bzl", "cc_proto_library")

cc_proto_library(
    name = "pong_proto",
    srcs = [
        "pong.proto",
    ],
    deps = [
        "//foo:base_proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf",
)

