cc_binary(
    name = "server",
    srcs = ["server.cc"],
    copts = [
        "-Iexternal/boost/include",
        "-Iexternal/asio/include",
        "-Wno-unused-variable",
    ],
   
    #linkopts = ["-pthread"],
    deps = ["@boost//:boost", "@asio//:asio", ":a_proto"],
)

cc_binary(
    name = "client",
    srcs = ["client.cc"],
    copts = [
        "-Iexternal/boost/include",
        "-Iexternal/asio/include",
        "-Wno-unused-variable",
    ],
   
    #linkopts = ["-pthread"],
    deps = ["@boost//:boost", "@asio//:asio"],
)

load("/google/protobuf/protobuf", "cc_proto_library")

cc_proto_library(
    name = "a_proto",
    srcs = ["a.proto", ],
)
