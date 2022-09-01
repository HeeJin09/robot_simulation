# robot_simulation

## robot simulation code
### - sim_robot 
 1) test 1 = 무중력 상태에서 center of mass의 위치를 변경시켜 (x,y,z) 힘을 주었을 때 결과 simulation을 확인
 2) test 2 = 무중력 상태에서 ur10e(UR6) 팔을 부착한 후 접었을 때의 wrench 및 simulation 결과 확인
 3) test 3 = 무중력 상태에서 box.urdf 와 ur10e.urdf를 각각 불러 base 기준으로 resetbasepositionandorientation을 하여 하나의 urdf처럼 이어지도록 만듦
 4) test 4 = 무중력 상태애서 getlinkstate를 통해 end_effector(kuka.urdf)의 pos를 읽어들여와 end_effector에 ur10e resetbasepositionandorientation를 시켜준다
 5) test 5 = test_4와 같은 상황에서 중력을 준 후 중력을 보상하도록 하는 simulation
