cc_binary(
    name = "server",
    srcs = ["server.cc"],
    copts = [
        "-Iexternal/boost/include",
        "-Iexternal/asio/include",
        "-Wno-unused-variable",
    ],
   
    #linkopts = ["-pthread"],
    deps = ["@boost//:boost", "@asio//:asio"],
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

