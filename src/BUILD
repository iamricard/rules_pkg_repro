load("@rules_pkg_0_6_0//:pkg.bzl", pkg_tar_0_6_0 = "pkg_tar")
load("@rules_pkg_0_7_0//pkg:tar.bzl", pkg_tar_0_7_0 = "pkg_tar")
load("@rules_pkg_git//:pkg.bzl", pkg_tar_git = "pkg_tar")
load("@rules_pkg_0_7_0//pkg:mappings.bzl", "pkg_files", "filter_directory", "pkg_mkdirs")

pkg_tar_0_6_0(
    name = "tar_0_6_0",
    srcs = [
        "dir1",
        "dir2",
    ],
    package_dir = "/go/src/github.com/iamricard/rules_pkg_repro",
    strip_prefix = "."
)

pkg_tar_0_7_0(
    name = "tar_0_7_0",
    srcs = [
        "dir1",
        "dir2",
    ],
    package_dir = "/go/src/github.com/iamricard/rules_pkg_repro",
    strip_prefix = "."
)

pkg_tar_git(
    name = "tar_git",
    srcs = [
        "dir1",
        "dir2",
    ],
    package_dir = "/go/src/github.com/iamricard/rules_pkg_repro",
    strip_prefix = "."
)
