bin_PROGRAMS=secure-gst-codec2

noinst_HEADERS = \
  crypto.h

secure_gst_codec2_SOURCES = secure-gst-codec2.c crypto.c
secure_gst_codec2_LDFLAGS = -lgstreamer-1.0 -lgobject-2.0 -lglib-2.0 -ldl
secure_gst_codec2_LIBTOOLFLAGS = --tag=disable-static
