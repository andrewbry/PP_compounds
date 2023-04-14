# PP_compounds
 A **Per Point modification** library of compounds for Bifrost made mainly for use with instances.
 
 Here are a few compounds made already and some yet to be started. This document is a work in progress.

 
 ## Create
 
 #### PP_distribute_linear
 Distributes points in a linear line.
 
 #### pp_distribute_radial
 Distributes points in a radial line
 
 #### pp_distribute_grid - WIP
 Distributes points in a grid pattern.
 
 #### pp_geo - WIP
 Work in progress.
 Uses the input geometry and assigns scale, orientation and id to each. Also find the centriod and moves the geo to world zero.
 Outputs the new geometry for use in the output compound.
 
 
 ## Modify
 
 #### pp_random
 Randomises position, scale and rotations.
 
 #### pp_offset
 Offsets, overwrites or multiplies position, scale and rotation
 
 #### pp_id - WIP
 Assigns and modifies the **point_instance_id** on each point. Can be used with falloffs.
 Currently does linear, random and fixed assignments.
 
 #### pp_falloff - WIP
 Takes an incoming transform and creates a falloff field as a cube, sphere or linear plane to be used as a mask for modifiers.
 
 #### pp_mask - WIP
 Creates mask values baesd of a property like ID. To be used in combination with falloff fields.
 
 ## Dynamics
 
 #### pp_spring - WIP
 A simple spring solver which can effect position, scale and rotation with stiffnes and damping values. Doesn'st use a start
  frame setup, only solves if delta time is less than 1 otherwise uses the incoming values. Can scale the force to a maximum value.
 
 ## Output
 
 #### pp_instance - WIP
 The main instancer compound. Currently is a simplified version of the Bifrost one. Hoping to add other functionality.
 
