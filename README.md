# PyMem
PyMem a powerful graphical user interface (GUI) tool for neuro-memristive hardware-software co-designthat uses Keras Python to implement multiple Memristor models on multiple neural architectures that can be used to analyze their working under a wide range of hardware variability. 
P. team. (2023) PyMem python memristor. [Online]. Available: http://13.127.213.216:8501/

**GETTING STARTED**

The landing page of PyMem is shown in the figure 

Figure S1

![image](https://github.com/ajiiit/PyMem/assets/63901666/3a858f04-9136-4db4-96e7-fd14580b64fe)

Start with specifying the type of neural network. Select whether going to build a software
neural network or hardware neural network S2.
Then click on "Make It" button S3.
If you want to build SNN click on the "Yes" button and make the answer True near the question
"Are you going to build a SCNN?". If you don’t want to make a SNN and the answer is Yes,
simply click on the "No" button and make it False S4.

**LOAD DATASET**

From the sidebar select a dataset from the dropdown list and click on "Load" S5.
The details of the loaded dataset will be dispalyed on the main page after successfully loading
the dataset S6.
If SNN is selected then after loading the dataset the options for generating spiking dataset will
appear under loaded dataset section S7. Provide the parameters for generating spiking dataset
and click on "Generate spiking dataset" button.

**BUILD MODEL**

Now Start adding layers to the neural network from the sidebar. Customize the parameters
according to your requirements and submit the layers one by one S8.

Figure S2 Option for selecting the type of Neural Network

![image](https://github.com/ajiiit/PyMem/assets/63901666/a7f99fb7-81fa-4565-ba0e-120b744e290a)
 
Figure. S3. Make It button

![image](https://github.com/ajiiit/PyMem/assets/63901666/d84f29fc-1cd7-48d8-a313-90fbe97715d4)

The added layers and parameters will be dispalyed on the main page as shown in figure S9.
Using "Reset" button the neural network can be reset to the initial state.
After adding the last layer to the neural network we can go for the compile and fit options
under the added layer section. Click on "Submit all" button after setting up the optimizer, loss
function, epochs and batch size S10.
After the training process the loss and accuracy graph will be shown under Results section S11.
The options for downloading the trained weights and restoring them (after mapping process) are
also provided.

**SET UP MEMRISTOR**

The setting up of memristor is the next step. Select the appropriate window functions and other
parameters and click on "Set Up Memristor" button S12.
The mapped weights can be reviewed from the displayed mapped weights section S13.

**EVALUATE**

Finally click on the "Evaluate" button to see the performance of the network. The performance
table will display the network’s performance, with the initial row representing the network’s performance before the mapping process 

Fig. S4. SNN section

![image](https://github.com/ajiiit/PyMem/assets/63901666/d1647acb-ca8c-4525-9498-6267c94b15d5)

Fig. S5. Dataset loading section from sidebar

![image](https://github.com/ajiiit/PyMem/assets/63901666/553ebb1e-ae9a-48af-a184-ec7e20e44f83)

Fig. S6. Loaded dataset details

![image](https://github.com/ajiiit/PyMem/assets/63901666/ea0faef7-db17-4ac0-884d-7febdbc35a07)

Fig. S7. Spiking dataset section

![image](https://github.com/ajiiit/PyMem/assets/63901666/fc4cd430-1dd2-42bd-85b5-c490159d7fdf)

Fig. S8. Layer adding section

![image](https://github.com/ajiiit/PyMem/assets/63901666/7330cf25-92c4-4136-ae07-5b81c0f3e5be)

Fig. S9. Added layers section

![image](https://github.com/ajiiit/PyMem/assets/63901666/1ddf317e-a618-4877-a2bd-ee37d87d2fe8)

Fig. S10. Compile and Fit section

![image](https://github.com/ajiiit/PyMem/assets/63901666/fba5537b-e0ae-4a48-a3c5-d8bacaf4e3f0)

Fig. S11. Results section

![image](https://github.com/ajiiit/PyMem/assets/63901666/e73f80e1-71df-4de4-bca1-9bf1f683dd25)

Fig. S12. Set up memristor section

![image](https://github.com/ajiiit/PyMem/assets/63901666/acc93667-c282-44cb-ba85-1f0056c72d79)

Fig. S13. Mapped weights section

![image](https://github.com/ajiiit/PyMem/assets/63901666/7be554d5-e37e-4659-bb6d-4481a7a06700)


