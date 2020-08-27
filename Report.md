

<img src="https://camo.githubusercontent.com/ed508e9c66d718f76333215a139af24f8bb8fa8d/68747470733a2f2f6d75736573636f72652e6f72672f73697465732f6d75736573636f72652e6f72672f66696c65732f4361707475726525323064253237652543432538316372616e253230323031362d30332d303125323030392e34382e31315f302e706e67" align="center"/>

## Google Summer of Code 2020 Final Work Report - 

| **Student** | Rishabh Baghel |
| --- | --- |
| **Github** | [@notabee](http://github.com/notabee)  |
| **Organisation**  | [Robocomp](https://robocomp.github.io/web/)  |
| **Project** | [Efficient acceptable social behaviour using machine learning techniques](https://summerofcode.withgoogle.com/projects/#6339113512337408) |   

## **Aim**
This project was aimed at predicting a robot's path in a social setting, for which we created a data collecting toolkit and trained our models on the data collected.

## **Work Done**

I started out by increasing the speed of graph data generation for training the GNNs, after that was done 
I seperated the GNNs and CNNs code for cleaner and more structured code base. 
I provided better support for both DGL and PG frameworks in the training loop. 
I helped in creating a GUI toolkit for collecting the robotic dataset along with that 
I helped in providing more GNN architectures as a usecase for the data collected from the toolkit.

## **SNGNN: [Github Repository](https://github.com/robocomp/sngnn)**

  * Pull Request : [Link](https://github.com/robocomp/sngnn/pull/12)
  

### **SONATA Toolkit for collecting the data: [Github Repository Link](https://github.com/robocomp/sngnn/tree/master/SONATA)**

### **Graph Neural Networks as a usecase: [Github Repository Link](https://github.com/robocomp/sngnn/tree/master/SONATA/usecase)**

### **Modules to integrate the whole pipeline: [Github Repository Link](https://github.com/robocomp/sngnn/tree/master/SONATA/python)**


## Screenshots
| Simulation starts | Reach the goal | Save data|
|--- | --- | --- |
| <img src="https://raw.githubusercontent.com/notabee/GSoC20-Report/master/gsoc3.png"/> |<img src="https://raw.githubusercontent.com/notabee/GSoC20-Report/master/gsoc1.png" /> | <img src="https://raw.githubusercontent.com/notabee/GSoC20-Report/master/gsoc2.png" />|


## Future Work
A thing that can be added is a second use-case to label interactions by building on top of our toolkit.


## GSoC'20 helped me a lot in learning things like:
1. Using PyTorch to write GNN architectures and ML models in general, I learned about PG and DGL.
2. How to write cleaner code so that everyone in the team can read it and continue help building it.
3. pub/sub communication between two processes.
4. Unix signal handling
5. PyQT and PySide to make GUIs.
6. How to collaborate with a team using git.


## Blog during GSoC
The blogs I wrote during GSoC period can be found here [Blogs](https://robocomp.github.io/web/gsoc/2020/posts/)


## Social

* Video for showing the working of the SONATA toolkit :

[![SONATA toolkit](http://img.youtube.com/vi/i_kkKqTwbBE/0.jpg)](https://www.youtube.com/watch?v=i_kkKqTwbBE "SONATA toolkit")


