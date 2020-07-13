cc_binary(
    name = "callbackMaker",
    srcs = ["demos/CallbackMaker/CallbackMaker.c"],
    deps = ["//freeglut/freeglut:glut"]
)

cc_binary(
    name = "fractals",
    srcs = ["demos/Fractals/fractals.c"],
    deps = ["//freeglut/freeglut:glut"],
    data = [":demos/Fractals/fractals.dat"],
    includes = ["demos/Fractals"],
)

cc_binary(
    name = "fractalsRandom",
    srcs = ["demos/Fractals_random/fractals_random.c"],
    deps = ["//freeglut/freeglut:glut"],
    data = [":demos/Fractals_random/fractals.dat"],
    includes = ["demos/Fractals_random"],
)

cc_binary(
    name = "lorenz",
    srcs = ["demos/Lorenz/lorenz.c"],
    deps = ["//freeglut/freeglut:glut"],
)

cc_binary(
    name = "smoothOpengl3",
    srcs = ["demos/smooth_opengl3/smooth_opengl3.c"],
    deps = ["//freeglut/freeglut:glut"],
)

cc_binary(
    name = "spaceball",
    srcs = [
        "demos/spaceball/spaceball.c",
        "demos/spaceball/vmath.c",
        "demos/spaceball/vmath.h",
        "demos/spaceball/vmath.inl",
    ],
    # includes = ["demos/Fractals_random"],
    deps = ["//freeglut/freeglut:glut"],
)