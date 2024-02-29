# How to add new features:

## 在侧边栏中新增条目
STEP1: 在_config.yml 文件中找到menu条目，添加:

menu:<br>
  \- title:             <Name of the menu>
  \- url:               <name of the file>

STEP2: 在_featured_categories 文件夹中添加<name of the file.md> 文件夹，并编写网页。


Computation: 66568 steps/s (collection: 1.983s, learning 0.180s)
               Value function loss: 0.0117
                    Surrogate loss: -0.0034
             Mean action noise std: 0.75
                       Mean reward: 2.96
               Mean episode length: 604.86
Episode Reward/track_lin_vel_xy_exp: 0.2339
Episode Reward/track_ang_vel_z_exp: 0.2066
       Episode Reward/lin_vel_z_l2: -0.0260
      Episode Reward/ang_vel_xy_l2: -0.0978
     Episode Reward/dof_torques_l2: -0.0426
         Episode Reward/dof_acc_l2: -0.0434
     Episode Reward/action_rate_l2: -0.0871
      Episode Reward/feet_air_time: -0.0003
Episode Reward/flat_orientation_l2: 0.0000
     Episode Reward/dof_pos_limits: 0.0000
         Curriculum/terrain_levels: 1.4556
Metrics/base_velocity/error_vel_xy: 0.8234
Metrics/base_velocity/error_vel_yaw: 0.7730
      Episode Termination/time_out: 2.7917
  Episode Termination/base_contact: 5.2917




