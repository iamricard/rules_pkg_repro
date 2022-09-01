workspace(name = "rules_pkg_repro")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "rules_pkg_0_6_0",
    urls = [
        "https://mirror.bazel.build/github.com/bazelbuild/rules_pkg/releases/download/0.6.0/rules_pkg-0.6.0.tar.gz",
        "https://github.com/bazelbuild/rules_pkg/releases/download/0.6.0/rules_pkg-0.6.0.tar.gz",
    ],
    sha256 = "62eeb544ff1ef41d786e329e1536c1d541bb9bcad27ae984d57f18f314018e66",
)
load("@rules_pkg_0_6_0//:deps.bzl", rules_pkg_0_6_0_deps = "rules_pkg_dependencies")
rules_pkg_0_6_0_deps()

http_archive(
    name = "rules_pkg_0_7_0",
    urls = [
        "https://mirror.bazel.build/github.com/bazelbuild/rules_pkg/releases/download/0.7.0/rules_pkg-0.7.0.tar.gz",
        "https://github.com/bazelbuild/rules_pkg/releases/download/0.7.0/rules_pkg-0.7.0.tar.gz",
    ],
    sha256 = "8a298e832762eda1830597d64fe7db58178aa84cd5926d76d5b744d6558941c2",
)
load("@rules_pkg_0_7_0//:deps.bzl", rules_pkg_0_7_0_deps = "rules_pkg_dependencies")
rules_pkg_0_7_0_deps()
