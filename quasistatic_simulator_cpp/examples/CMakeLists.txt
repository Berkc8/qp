add_executable(run_planar_hand_ball run_planar_hand_ball.cc)
target_link_libraries(run_planar_hand_ball quasistatic_simulator)
target_include_directories(run_planar_hand_ball PUBLIC ${PROJECT_SOURCE_DIR})

add_executable(run_3link_arm_3d run_3link_arm_3d.cc)
target_link_libraries(run_3link_arm_3d quasistatic_simulator)
target_include_directories(run_3link_arm_3d PUBLIC ${PROJECT_SOURCE_DIR})

add_executable(run_iiwa_box_stacking run_iiwa_box_stacking.cc)
target_link_libraries(run_iiwa_box_stacking quasistatic_simulator)
target_include_directories(run_iiwa_box_stacking PUBLIC ${PROJECT_SOURCE_DIR})

add_executable(run_allegro_hand_jacobian run_allegro_hand_jacobian.cc)
target_link_libraries(run_allegro_hand_jacobian quasistatic_simulator)
target_include_directories(run_allegro_hand_jacobian PUBLIC ${PROJECT_SOURCE_DIR})

add_executable(run_allegro_hand_A run_allegro_hand_A.cc)
target_link_libraries(run_allegro_hand_A quasistatic_simulator)
target_include_directories(run_allegro_hand_A PUBLIC ${PROJECT_SOURCE_DIR})

add_executable(run_two_spheres_yz run_two_spheres_yz.cc)
target_link_libraries(run_two_spheres_yz quasistatic_simulator)
target_include_directories(run_two_spheres_yz PUBLIC ${PROJECT_SOURCE_DIR})
