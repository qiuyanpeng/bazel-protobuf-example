load("@protobuf//:protobuf.bzl", "cc_proto_library")

cc_proto_library(
    name = "base_proto",
    srcs = [
        "base.proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf",
    visibility = [
        "//bar:__pkg__",
    ],
)

