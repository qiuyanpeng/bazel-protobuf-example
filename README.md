# Examples for bazel + protobuf

- Build [protobuf](https://developers.google.com/protocol-buffers/) with [bazel](https://www.bazel.io/).
- Use extensions in protobuf, comparing to using sub-message.

## C++

Run

```
bazel build //bar:ping_cc_proto && bazel build //baz:pong_cc_proto
```

Compare `bazel-genfiles/bar/ping.pb.h` and `bazel-genfiles/baz/pong.pb.h`.

## Python

Run
```
bazel build //bar:ping_py_proto && bazel build //baz:pong_py_proto
```

Compare `bazel-genfiles/bar/ping_pb2.py` and `bazel-genfiles/baz/pong_pb2.py`.

