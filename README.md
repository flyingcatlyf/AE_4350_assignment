===========================================================================                        
                        *** Table of Contents ***
===========================================================================
---------------------------------------------------------------------------
A) DDPG-SCA_Training
    0) Training.py  -Main file for training the flight control system (run to start the training process)
    1) RK.py  -iteratively solves lateral dynamical equations over time with Runge Kutta method
    2) Ref.py -Producecs reference signals
    3) ddpg_torch.py  -Synthesizes all functions of the DDPG-SCA agent

B) DDPG-SDA_Training
    0) Training.py  -Main file for training the flight control system (run to start the training process)
    1) RK.py  -iteratively solves lateral dynamical equations over time with Runge Kutta method
    2) Ref.py -Producecs reference signals
    3) ddpg_torch.py  -Synthesizes all functions of the DDPG-SDA agent

C) DDPG_Training
    0) Training.py  -Main file for training the flight control system (run to start the training process)
    1) RK.py  -iteratively solves lateral dynamical equations over time with Runge Kutta method
    2) Ref.py -Producecs reference signals
    3) ddpg_torch.py  -Synthesizes all functions of the DDPG agent

D) Operation&Plot
    0) Operation.py  -Main file for operating the trained flight control system (run to start the operation process)
    1) RK.py  -iteratively solves lateral dynamical equations over time with Runge Kutta method
    2) Ref.py -Producecs reference signals
    3) Computation_IAE_ITAE  -Computes tracking performance meausres in operation phase 
    4) plot_operation_average_reward.py  -Compares average reward in operation phase
    5) plot_state_comparison.py  -Compares states and actions in operation phase
    6) plot_training.py  -Compares training performance

===========================================================================
                        *** Guide to Use the Code ***
===========================================================================
------------------------------------------------------------------------
A) RUN TRAINING
     0) Install an interpreter environment that includes packages in interpreter_packages.txt
     1) Run Training.py in files 'DDPG-SCA_Training', 'DDPG-SDA_Training', 'DDPG_Training', to start training of the flight controller.  
     2) Save data automatically in file 'tmp/ddpg'

B) RUN OPERATION
     0) Install an interpreter environment that includes packages in interpreter_packages.txt
     1) Run Operation.py in file 'Operation&Plot', to start operation phase. The file 'Actor_ddpg.zip' includes actor weights file and should be uploaded to run operation.
     2) Save data automatically


---------------------------------------------------------------------------

===========================================================================

 

         
