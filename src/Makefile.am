## Process this file with automake to produce Makefile.in
## Created by Anjuta


uidir = $(pkgdatadir)/ui
ui_DATA = tinatabil.ui \
	app.tinaContabil.python2.db \
	tinatabil.png


## The main script
bin_SCRIPTS = tinatabil.py

## Directory where .class files will be installed
tinatabildir = $(pythondir)/tinatabil


tinatabil_PYTHON = \
	tinatabil.py


EXTRA_DIST = $(ui_DATA)


# Remove ui directory on uninstall
uninstall-local:

	-rm -r $(uidir)

	-rm -r $(pkgdatadir)
