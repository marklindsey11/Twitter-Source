java_library(
    sources = ["**/*.java"],
    platform = "java8",
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/google/code/findbugs:jsr305",
        "3rdparty/jvm/com/google/guava",
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/org/apache/thrift:libthrift",
        "3rdparty/jvm/org/apache/zookeeper:zookeeper-client",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        "src/java/com/twitter/common/base",
        "src/java/com/twitter/common/util:system-mocks",
        "src/java/com/twitter/search/common/config",
        "src/java/com/twitter/search/common/metrics",
        "src/java/com/twitter/search/common/partitioning/snowflakeparser",
        "src/java/com/twitter/search/common/util/date",
        "src/java/com/twitter/search/common/util/zookeeper",
        "src/java/com/twitter/search/earlybird/common/config",
    ],
)
