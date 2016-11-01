- Build [protobuf](https://developers.google.com/protocol-buffers/) with [bazel](https://www.bazel.io/).
- Use extensions in protobuf.

Run

```
bazel build //bar:ping_proto
```

and

```
bazel build //baz:pong_proto
```

Compare `bazel-genfiles/bar/ping.pb.h` and `bazel-genfiles/baz/pong.pb.h`.

