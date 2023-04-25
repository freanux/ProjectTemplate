AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = executable

# ##############################
#     empty for convenience
# ##############################
executable_SOURCES =
executable_CXXFLAGS =
executable_LDADD =

# ##############################
#     base sources
# ##############################
executable_SOURCES += src/main.cpp

# ##############################
#     includes
# ##############################
executable_CXXFLAGS += -Isrc/include

# ##############################
#     compiler flags
# ##############################
executable_CXXFLAGS += -std=c++11 -pedantic -Wextra -Wno-unused-parameter -Wno-unused-result -Wno-missing-field-initializers

# ##############################
#     linking objects
# ##############################
#executable_CXXFLAGS += -Llib
#executable_LDADD += -llib
