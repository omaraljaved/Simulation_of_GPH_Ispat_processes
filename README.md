# Process Description:
At first the scraps are carried from the scrapyard to the Quantum Electric Arc Furnace (QEAF) by Overhead conveyor (Velocity 1.0 m/s) and AGV (velocity 5 m/s). The heavy scraps are sent to the intermediate scrapyard for further processing (unif(5)). From the QEAF, the metals are sent toward Rolling Mill by a Continuous Casting Machine (const 5 m/s). GPH uses Ladle Furnace (const 5 m/s) for sending the molten metal towards the Rolling Mill. After labeling and further processing, the qualified billets are sent to the warehouse using heavy trucks which are regarded as the disposal of the material in the simulation. And the under-qualified billets are sent to the Scrapyard again for reprocessing. It may be noted that the QEAF is associated with the WTP and ASU which supplies the furnace with relevant gases and water for cooling issues. Here the simulation is done while assuming the replication length is 5, and the number of replication is 1. And the simulation runs for 20 hours per day.
![GPH Process Flow](https://github.com/omaraljaved/Simulation_of_GPH_Ispat_processes/assets/67588258/bf06b848-d018-447d-8412-392f6225be74)
<p align="center"><em><strong>Figure: Overall Process Flow</strong></em></p>

# Recommendations:
We have already seen from the GPH’s process (doe file) that they use separate trucks to take the rebars for the sealing process which we have designated as a waste of time (delay 2hr). So we propose the labeling and sealing processes through an assignment operation & finally dispose of it by using the dispose module. It will reduce their use of a truck and thus time and money will be optimized which will increase productivity and profit.


