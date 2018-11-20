set(COMPONENT_SRCS src/GUIslice.c src/GUIslice_drv_loboris.cpp src/GUIslice_ex.c)# src/GUIslice_drv_adagfx.cpp src/GUIslice_drv_m5stack.cpp)
set(COMPONENT_ADD_INCLUDEDIRS "src")
set(COMPONENT_PRIV_REQUIRES tft)
register_component()