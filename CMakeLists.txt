set(COMPONENT_SRCS GUIslice.c GUIslice_drv_loboris.cpp GUIslice_ex.c GUIslice_drv_adagfx.cpp GUIslice_drv_m5stack.cpp)
set(COMPONENT_ADD_INCLUDEDIRS ".")
set(COMPONENT_PRIV_REQUIRES tft)
register_component()