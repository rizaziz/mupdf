# Process this file with automake to produce Makefile.in

NULL =
EXTRA_DIST =
SUBDIRS = api shape subset fuzzing

EXTRA_DIST += \
	meson.build \
	$(NULL)

# Convenience targets:
lib:
	@$(MAKE) $(AM_MAKEFLAGS) -C $(top_builddir)/src lib

-include $(top_srcdir)/git.mk
