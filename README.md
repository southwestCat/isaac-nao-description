# NAO description for IsaacLab environment

The urdf file has been modified so that it can run properly in the isaacsim environment. The source urdf file can be downloaded [here](https://github.com/ros-naoqi/nao_robot/blob/master/nao_description/urdf/naoV50_generated_urdf/nao.urdf).

In NAOV50 dir, the NAO_d.usd is can be loaded using ArticulationCfg. STLs in `meshes/stl` is also modified for origin model file leading self-collision in IsaacSim. We tried to build more elaborate models and simpler models, such as spheres and cuboids, but none of them solved the issue. If you need the origin model files, we recommend you convert the `.dae` files to your needed 3D model format. We use blender to do this.