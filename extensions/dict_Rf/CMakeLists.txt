# The dict_Rf extension
PROJECT("dict_Rf library generated by FdGen " C)

# Compile as a module
FD_ADD_EXTENSION(dict_Rf dict_Rf.c)


####
## INSTALL section ##

INSTALL(TARGETS dict_Rf
	LIBRARY DESTINATION ${INSTALL_EXTENSIONS_SUFFIX}
COMPONENT freeDiameter-dictionary-RF)



