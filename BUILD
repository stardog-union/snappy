cc_library(
    name = "snappy",
    hdrs = [
    	 "snappy-c.h",
	 "snappy.h",
	 "snappy-sinksource.h",
    	 # Hard-coded snappy-stubs-public.h that will work for most non-Windows systems.
	 # This is a shortcut to get a first Bazel build working.
	 # TODO(james): Specialize this file by system or generate it at build time.
         "snappy-stubs-public.h",
    ],
    srcs = [
    	 # Hard-coded config.h that will work for non-Windows, non-big endian systems.
	 # This is a shortcut to get a first Bazel build working.
	 # TODO(james): Specialize this file by system or generate it at build time.
    	 "config.h",
         "snappy.cc",
         "snappy-c.cc",
	 "snappy-internal.h",
	 "snappy-sinksource.cc",
	 "snappy-stubs-internal.cc",
	 "snappy-stubs-internal.h",
    ],
    visibility = ["//visibility:public"],
)

