cc_library(
    name = "asio",
    hdrs = glob([
        "include/**/*.hpp",
        "include/**/*.ipp",
        "include/**/*.h",
    ]),
    copts = [
        "-Iexternal/boost/include",
        "-Wno-unused-variable",
    ],
    linkopts = ["-pthread"],
    visibility = ["//visibility:public"],
    deps = ["@boost//:boost"]
)
