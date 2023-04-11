load("//tools:cpplint.bzl", "cpplint")
load("@rules_proto//proto:defs.bzl", "proto_library")
load("@rules_cc//cc:defs.bzl", "cc_proto_library")
load("//tools:python_rules.bzl", "py_proto_library")

package(default_visibility = ["//visibility:public"])

proto_library(
    name = "carla_proto_lib",
    srcs = [
        "carla_actor.proto",
        "carla_basic_type.proto",
        "carla_bounding_box.proto",
        "carla_camera_info.proto",
        "carla_clock.proto",
        "carla_control.proto",
        "carla_destroy_object.proto",
        "carla_ego_vehicle.proto",
        "carla_geometry.proto",
        "carla_get_blueprints.proto",
        "carla_marker.proto",
        "carla_object.proto",
        "carla_odometry.proto",
        "carla_spawn_object.proto",
        "carla_status.proto",
        "carla_traffic_light.proto",
        "carla_walker_control.proto",
        "carla_weather_parameters.proto",
        "carla_world_info.proto",
    ],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)


proto_library(
    name = "carla_actor_proto",
    srcs = ["carla_actor.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_actor_pb2",
    deps = [
        ":carla_actor_proto",
    ],
)
proto_library(
    name = "carla_basic_type_proto",
    srcs = ["carla_basic_type.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_basic_type_py_pb2",
    deps = [
        ":carla_basic_type_proto",
    ],
)
proto_library(
    name = "carla_bounding_box_proto",
    srcs = ["carla_bounding_box.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_bounding_box_py_pb2",
    deps = [
        ":carla_bounding_box_proto",
    ],
)
proto_library(
    name = "carla_camera_info_proto",
    srcs = ["carla_camera_info.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_camera_info_py_pb2",
    deps = [
        ":carla_camera_info_proto",
    ],
)
proto_library(
    name = "carla_clock_proto",
    srcs = ["carla_clock.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_clock_py_pb2",
    deps = [
        ":carla_clock_proto",
    ],
)
proto_library(
    name = "carla_control_proto",
    srcs = ["carla_control.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_control_py_pb2",
    deps = [
        ":carla_control_proto",
    ],
)
proto_library(
    name = "carla_destroy_object_proto",
    srcs = ["carla_destroy_object.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_destroy_object_py_pb2",
    deps = [
        ":carla_destroy_object_proto",
    ],
)
proto_library(
    name = "carla_ego_vehicle_proto",
    srcs = ["carla_ego_vehicle.proto"],
    deps = [
        ":carla_geometry_proto",
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_ego_vehicle_py_pb2",
    deps = [
        ":carla_ego_vehicle_proto",
    ],
)
proto_library(
    name = "carla_geometry_proto",
    srcs = ["carla_geometry.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_geometry_py_pb2",
    deps = [
        ":carla_geometry_proto",
    ],
)
proto_library(
    name = "carla_get_blueprints_proto",
    srcs = ["carla_get_blueprints.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_get_blueprints_py_pb2",
    deps = [
        ":carla_get_blueprints_proto",
    ],
)
proto_library(
    name = "carla_marker_proto",
    srcs = ["carla_marker.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_marker_py_pb2",
    deps = [
        ":carla_marker_proto",
    ],
)
proto_library(
    name = "carla_object_proto",
    srcs = ["carla_object.proto"],
    deps = [
        ":carla_geometry_proto",
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_object_py_pb2",
    deps = [
        ":carla_object_proto",
    ],
)
proto_library(
    name = "carla_odometry_proto",
    srcs = ["carla_odometry.proto"],
    deps = [
        ":carla_geometry_proto",
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_odometry_py_pb2",
    deps = [
        ":carla_odometry_proto",
    ],
)
proto_library(
    name = "carla_spawn_object_proto",
    srcs = ["carla_spawn_object.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_spawn_object_py_pb2",
    deps = [
        ":carla_spawn_object_proto",
    ],
)
proto_library(
    name = "carla_status_proto",
    srcs = ["carla_status.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_status_py_pb2",
    deps = [
        ":carla_status_proto",
    ],
)
proto_library(
    name = "carla_traffic_light_proto",
    srcs = ["carla_traffic_light.proto"],
    deps = [
        ":carla_bounding_box_proto",
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_traffic_light_py_pb2",
    deps = [
        ":carla_traffic_light_proto",
    ],
)
proto_library(
    name = "carla_walker_control_proto",
    srcs = ["carla_walker_control.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_walker_control_py_pb2",
    deps = [
        ":carla_walker_control_proto",
    ],
)
proto_library(
    name = "carla_weather_parameters_proto",
    srcs = ["carla_weather_parameters.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_weather_parameters_py_pb2",
    deps = [
        ":carla_weather_parameters_proto",
    ],
)
proto_library(
    name = "carla_world_info_proto",
    srcs = ["carla_world_info.proto"],
    deps = [
        "//modules/common_msgs/basic_msgs:header_proto",
        "//modules/common_msgs/basic_msgs:geometry_proto",
        "//modules/data/proto:frame_proto",
        "//modules/common_msgs/localization_msgs:pose_proto",
    ],
)

py_proto_library(
    name = "carla_world_info_py_pb2",
    deps = [
        ":carla_world_info_proto",
    ],
)