set(Caffe2_CONTRIB_DEPTHWISE3x3_CPU_SRC
  "${CMAKE_CURRENT_SOURCE_DIR}/depthwise3x3_conv_op.cc"
)
set(Caffe2_CONTRIB_DEPTHWISE3x3_TEST_CPU_SRC
  "${CMAKE_CURRENT_SOURCE_DIR}/depthwise3x3_conv_op_test.cc"
)

set(Caffe2_CPU_SRCS ${Caffe2_CPU_SRCS} ${Caffe2_CONTRIB_DEPTHWISE3x3_CPU_SRC} PARENT_SCOPE)
set(Caffe2_CPU_TEST_SRCS ${Caffe2_CPU_TEST_SRCS} ${Caffe2_CONTRIB_DEPTHWISE3x3_TEST_CPU_SRC} PARENT_SCOPE)
