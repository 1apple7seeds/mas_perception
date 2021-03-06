# C++ Library

## Classes
### `BoundingBox`
Create a 2D bounding box with for vertices given a point cloud and a plane normal. Defined in:
* [`bounding_box.h`](../common/include/mas_perception_libs/bounding_box.h)
* [`bounding_box.cpp`](../common/src/bounding_box.cpp)

### `BoundingBoxWrapper`
Boost Python port of `BoundingBox`. Python interface described in
[documentation for the python package](python_package.md). Defined in:
* [`bounding_box_wrapper.h`](../ros/include/mas_perception_libs/bounding_box_wrapper.h)
* [`bounding_box_wrapper.cpp`](../ros/src/bounding_box_wrapper.cpp)

## Utility functions
### ROS message serialization
Contains method to serialize and deserialize ROS messages, for passing them between C++ and Python
code. Defined in [`ros_message_serialization.hpp`](../ros/include/mas_perception_libs/impl/ros_message_serialization.hpp).