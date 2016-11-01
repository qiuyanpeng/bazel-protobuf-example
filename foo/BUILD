load("@protobuf//:protobuf.bzl", "cc_proto_library", "py_proto_library")

package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "base_cc_proto",
    srcs = [
        "base.proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf",
)

py_proto_library(
    name = "base_py_proto",
    srcs = [
        "base.proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf_python",
)

