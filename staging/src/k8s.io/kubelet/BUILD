filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//staging/src/k8s.io/kubelet/config/v1alpha1:all-srcs",
        "//staging/src/k8s.io/kubelet/config/v1beta1:all-srcs",
        "//staging/src/k8s.io/kubelet/pkg/apis:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
