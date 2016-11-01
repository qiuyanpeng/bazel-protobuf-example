# Copied from
# https://github.com/google/protobuf/blob/c44ca26fe89ed8a81d3ee475a2ccc1797141dbce/six.BUILD

genrule(
  name = "copy_six",
  srcs = ["six-1.10.0/six.py"],
  outs = ["six.py"],
  cmd = "cp $< $(@)",
)

py_library(
  name = "six",
  srcs = ["six.py"],
  srcs_version = "PY2AND3",
  visibility = ["//visibility:public"],
)

