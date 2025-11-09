java_library(
    name="utils_lib",
    srcs=glob(["utils/*.java"]),
    visibility=["//visibility:public"],
)

java_binary(
    name="hello_world",
    srcs=["HelloWorld.java"],
    main_class="main.java.com.example.project.HelloWorld",
    deps=[":utils_lib"],

)


