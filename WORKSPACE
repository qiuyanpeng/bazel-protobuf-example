# See https://www.bazel.io/versions/master/docs/be/workspace.html#git_repository
# for detailed usage.
git_repository(
  name = "protobuf",
  remote = "https://github.com/google/protobuf",
  tag = "v3.1.0",
)

# Copied from
# https://github.com/google/protobuf/blob/3f59452448f2dc555178941c702fbfea6dbc0aa8/WORKSPACE
new_http_archive(
    name = "six_archive",
    build_file = "six.BUILD",
    sha256 = "105f8d68616f8248e24bf0e9372ef04d3cc10104f1980f54d57b2ce73a5ad56a",
    url = "https://pypi.python.org/packages/source/s/six/six-1.10.0.tar.gz#md5=34eed507548117b2ab523ab14b2f8b55",
)

bind(
    name = "six",
    actual = "@six_archive//:six",
)


