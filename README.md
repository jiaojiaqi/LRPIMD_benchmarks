# LRPIMD_benchmarks

Generating process:

Barreto_LRPIMD and Prodhon_LRPIMD are designed based on two traditional LRP benchmarks called Barreto set and Prodhon set with the characteristics of LRPIMD, and the download address for the traditional ones is http://prodhonc.free.fr. The designed instances not only inherit the number of locations, depots, rescue vehicles and tasks, but the distributions of locations and tasks from each instance in both Barreto set and Prodhon set. On this basis, Barreto_LRPIMD and Prodhon_LRPIMD have been expanded in terms of the capacity of transportation platforms, the duration threshold of rescue vehicles, the execution time and importance of tasks.

Files in the Instances_Barreto_LRPIMD and Instances_Prodhon_LRPIMD folders are in.mat format and have 13 and 18 sub-files, respectively. Instances are mainly classified into three types based on the task distribution, including dense, sparse, and uniform。For instances in Prodhon set with the same location and task distributions, only one of them is reserved. The name of each instance in designed benchmarks is prefixed with I_. For example, coordChrist50 is named as I_coordChrist50 in Barreto_LRPIMD.

Parameter description:

data.zone_size indicates the length of the side of the area. data.location and data.location_num indicate the coordinate set and number of locations, respectively. data.depot_num and data.depot_capacity are the number and loading capacity of transportation platforms, respectively. data.agent_num, data.time_threshold, and data.speed indicate the number, endurance threshold, and speed of rescue vehicles, respectively. data.target_pos, data.target_time, and data.target_weight are the set of the positions, execution times, and weights of tasks, respectively.
