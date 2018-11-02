cc_library(
  name = "http_parser",
  srcs = ["http_parser.c"],
  hdrs = ["http_parser.h"],
)

cc_binary(
  name = "bench",
  srcs = ["bench.c"],
  deps = [
    ":http_parser"
  ],
)
