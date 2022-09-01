load("@rules_pkg_0_6_0//:pkg.bzl", pkg_tar_0_6_0 = "pkg_tar")
load("@rules_pkg_0_7_0//pkg:tar.bzl", pkg_tar_0_7_0 = "pkg_tar")
load("@rules_pkg_git//:pkg.bzl", pkg_tar_git = "pkg_tar")
load("@rules_pkg_git_patched//:pkg.bzl", pkg_tar_git_patched = "pkg_tar")
load("@rules_pkg_0_7_0_patched//pkg:tar.bzl", pkg_tar_0_7_0_patched = "pkg_tar")

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

pkg_tar_git_patched(
    name = "tar_git_patched",
    srcs = [
        "dir1",
        "dir2",
    ],
    package_dir = "/go/src/github.com/iamricard/rules_pkg_repro",
    strip_prefix = "."
)

pkg_tar_0_7_0_patched(
    name = "tar_0_7_0_patched",
    srcs = [
        "dir1",
        "dir2",
    ],
    package_dir = "/go/src/github.com/iamricard/rules_pkg_repro",
    strip_prefix = "."
)
