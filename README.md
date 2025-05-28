# Selected Topics in Visual Recognition using Deep Learning, Spring 2025: Homework 4
Course instructor: 林彥宇<br>
<br>
StudentID: 313540002<br>
Name: Leontieva Mariia, 馬莉亞<br>

### Introduction

In this assignment, we aim to solve image restoration problem using a Faster R-CNN network, using the [dataset](https://drive.google.com/drive/folders/1Q4qLPMCKdjn-iGgXV_8wujDmvDpSI1ul?usp=share_link) that contains 1600 images degraded with snow noise and 1600 images degraded with rain noise and their corresponding 3200 clean images, and 100 test images (without specifying their degradation type).<br>
<br>
To solve this problem, I used PromptIR network.<br>
<br>
<img width="827" alt="image" src="https://github.com/user-attachments/assets/0366fb6a-afdb-42ef-acc7-1b2cf0dab292" />
<br>


## Results
The best results were yielded by using Adam with LR=2e-5 and Cosine Annealing LR Scheduler. Training and validation curves of this model over 77 epochs can be seen below.<br>
<br>
<img width="425" alt="image" src="https://github.com/user-attachments/assets/1a93d46e-8746-4fcc-9510-a78a25b3572c" />

<br>

## Performance
Performance was evaluated using [CodaBench competition](https://www.codabench.org/competitions/7834/?secret_key=3ee0f511-d399-4221-b897-98cb11701cb6).<br>
According to the results of experiments, the best prediction during the test stage is 27.51.

<img width="865" alt="image" src="https://github.com/user-attachments/assets/241aad56-493a-4417-bae8-64e4dd62d3ae" />


