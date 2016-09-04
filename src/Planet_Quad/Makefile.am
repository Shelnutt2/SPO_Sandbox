INCLUDES = -I$(top_srcdir)/src/EngineCore
LDADD = -lpthread -lpng -framework OpenGL -lGLEW -lSDL2 -framework Cocoa $(top_builddir)/src/EngineCore/libEngineCore.a

bin_PROGRAMS = Planet_Quad
Planet_Quad_SOURCES = \
GrassFactory.cpp                PlanetaryMap.h \
GrassFactory.h                  PlanetaryMapCoord.cpp \
PlanetaryMapCoord.h \
MixedHeightMapFactory.cpp       PlanetaryMapNode.cpp \
MixedHeightMapFactory.h         PlanetaryMapNode.h \
Planet_Quad.cpp                 PlanetaryObject.cpp \
PlanetaryMap.cpp                PlanetaryObject.h

