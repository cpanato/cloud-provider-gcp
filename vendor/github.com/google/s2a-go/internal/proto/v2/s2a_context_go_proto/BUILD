load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "s2a_context_go_proto",
    srcs = ["s2a_context.pb.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/s2a-go/internal/proto/v2/s2a_context_go_proto",
    importpath = "github.com/google/s2a-go/internal/proto/v2/s2a_context_go_proto",
    visibility = ["//vendor/github.com/google/s2a-go:__subpackages__"],
    deps = [
        "//vendor/github.com/google/s2a-go/internal/proto/v2/common_go_proto",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl",
    ],
)
