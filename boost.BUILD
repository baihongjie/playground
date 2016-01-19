cc_library(
    name = "boost",
    srcs = glob(
        ["lib/*.a"],
    ),
    hdrs = glob([
        "include/boost/**/*.hpp",
        "include/boost/**/*.ipp",
        "include/boost/**/*.h",
    ]),
    #copts = [
    #    "-Iexternal/boost/include",
    #],
 
    linkopts = ["-pthread"],
    visibility = ["//visibility:public"],
)
