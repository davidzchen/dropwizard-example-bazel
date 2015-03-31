java_binary(
    name = "helloworld",
    srcs = glob(["java/**/*.java"]),
    resources = glob(["resources/**/*.*"]),
    main_class = "com.example.helloworld.HelloWorldApplication",
    deps = [
        "//external:dropwizard-core-jar",
        "//external:dropwizard-auth-jar",
        "//external:dropwizard-assets-jar",
        "//external:dropwizard-spdy-jar",
        "//external:dropwizard-hibernate-jar",
        "//external:dropwizard-migrations-jar",
        "//external:dropwizard-views-freemarker-jar",
        "//external:dropwizard-views-mustache-jar",
        "//external:h2-jar",
    ],
)
