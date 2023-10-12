---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default

irosVideoId: 1wag5m_uDBRPMmNiLkZLFNsktBMZdmMVH/preview
scitechVideoId: 1uBUFSIgVYbPKJCdrHyqZY6C_G0I2rYps/preview

irosYouTubeId: k-eM6Locyek
scitechYouTubeId: qmoHyJFUxE0
neuripsWorkshop2022YouTubeId: Ft2bozofYM8

---
**[Research](#Research) &ensp; &ensp; [Education](#Education) &ensp; &ensp; [CV](./files/Kyle_Hatch_CV_October_2023.pdf){:target="_blank"} &ensp; &ensp;  [Publications](#Publications) &ensp; &ensp; [Presentations](#Presentations) &ensp; &ensp; [Volunteer Work](#Volunteer)**
<!-- **[Publications](#Publications) &ensp; &ensp; &ensp; [Presentations](#Presentations) &ensp; &ensp; &ensp; [Research](#Research) &ensp; &ensp; &ensp; [Education](#Education) &ensp; &ensp; &ensp; [CV](./files/Kyle_Hatch_CV_October_2023.pdf){:target="_blank"} &ensp; &ensp; &ensp; [Volunteer Work](#Volunteer)** -->
<!-- **[Publications](#Publications) &ensp; &ensp; &ensp; &ensp; [Presentations](#Presentations) &ensp; &ensp; &ensp; &ensp; [Research](#Research) &ensp; &ensp; &ensp; &ensp; [Coursework](#Education) &ensp; &ensp; &ensp; &ensp; [CV](./files/Kyle_Hatch_CV_October_2023.pdf){:target="_blank"} &ensp; &ensp; &ensp; &ensp; [Volunteer Work](#Volunteer)** -->

<!-- <img src="./files/j_tree_portrait_clipped_small.png" alt="drawing" width="200"/> -->
<!-- <img src="./files/j_tree_portrait_clipped_small.png" alt="drawing" width="275"/> -->
<!-- <img src="./files/j_tree_portrait_clipped_small.png" alt="drawing" width="250"/> -->

<img src="./files/j_tree_portrait_clipped_small.png" alt="drawing" align="left" width="275" style="margin: 0px 30px 0px 0px;" />

<!--
I am a master's student at Stanford University studying Computer Science.
I am heavily involved in artificial intelligence research and 
I plan to pursue a PhD in Computer Science, Machine Learning, or Robotics.
My research interests lie primarily within reinforcement learning (RL) and robot learning.
I am especially fascinated with answering the following questions:
  - How can we make RL agents that can generalize quickly and efficiently to new tasks?
  - How can we make RL algorithms that leverage prior knowledge about a task during training instead of training from *tabula rasa?*
<br clear="left"/> -->


I am an AI Resident in the Machine Learning Division at the [Toyota Research Institute](https://www.tri.global/){:target="_blank"} (TRI). 
I plan to pursue a PhD in Computer Science, Machine Learning, or Robotics. 
My research interests lie primarily within robot learning and reinforcement learning (RL). 

I am especially excited about exploring solutions to the following questions:
How can we leverage video data--which exists on a massive scale on the Internet but does not contain action labels--for training robot policies?
What changes do we need to make to current offline RL methods so that they scale to practical robot applications? 
How can we use goal-conditioned/self-supervised RL to learn from random play data or autonomously collected data without reward labels?

I was extremely fortunate to work with many wonderful mentors during my time as a master's and undergraduate student. I worked with Prof. [Chelsea Finn](https://ai.stanford.edu/~cbfinn/){:target="_blank"} in the Stanford [IRIS](https://irislab.stanford.edu/){:target="_blank"} Lab as an undergraduate and master's student. 
As a master's student, I also worked with Prof. [Ben Eysenbach](https://ben-eysenbach.github.io/){:target="_blank"}.
I first started research as an undergraduate student with Prof. [Mykel Kochenderfer](https://mykel.kochenderfer.com/){:target="_blank"} in the Stanford Intelligent Systems Laboratory ([SISL](https://sisl.stanford.edu/){:target="_blank"}).
<!-- , and also completed a research internship at the Johns Hopkins University Applied Physics Laboratory ([APL](https://www.jhuapl.edu/){:target="_blank"}). -->


<html>
 <head>
    <style>
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns*/
    .column {
    float: left;
    width: 50%;
    }

    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    </style>
 </head>
 <body>
    <div class="row">
        <div class="column">
            <h5>Research Interests</h5>
            <p>
              <ul>
                <!-- <li>Leveraging Prior Knowledge in RL</li>
                <li>Generalization in RL</li>
                <li>Offline RL</li>
                <li>Robot Learning</li> -->
                <li>Robot Learning</li>
                <li>Leveraging Internet scale video data</li>
                <li>Offline RL</li>
                <li>Goal-conditioned RL</li>
                
              </ul>
            </p>
        </div>
        <div class="column">
            <h5>Education</h5>
            <p>
              <ul>
                <li>M.S. in Computer Science, Stanford University, 2021 - 2023</li>
                <li>B.S. with honors in Computer Science, Stanford University, 2017 - 2022</li>
              </ul>
            </p>
        </div>
    </div>
 </body>
</html>


<a name="Publications"> </a>
## Publications

#### Under Review
<a name="d5rl"> </a>
Rafailov, R.\*, **Hatch, K. B.\***, Singh, A., Smith, L., Kumar, A., Kostrikov, I., Hansen-Estruch, P., Kolev, V.,
Ball, P., Wu, J., Finn, C., and Levine, S., "D5RL: Diverse Datasets for Data-Driven Deep Reinforcement
Learning,” International Conference on Learning Representations (ICLR), 2024.

#### Published/Accepted
<a name="moto"> </a>
Rafailov, R.\*, **Hatch, K. B.\***, Kolev, V., Martin, J., Phielipp, M., and Finn, C., ”MOTO: Offline to Online
Fine-tuning for Model-Based Reinforcement Learning,” *Conference on Robot Learning (CoRL)*, 2023. &ensp; [PDF](https://openreview.net/pdf?id=cH8XVu9hUV){:target="_blank"}

<a name="laeo"> </a>
**Hatch, K. B.,** Eysenbach, B., Yu, T., Rafailov, R., Salakhutdinov, R., Levine, S., and Finn, C., ”Contrastive
Example-Based Control,” *Learning for Dynamics & Control Conference (L4DC),* 2023. &ensp; [PDF](https://arxiv.org/abs/2307.13101){:target="_blank"} &ensp; &ensp; [Website](https://sites.google.com/view/laeo-rl){:target="_blank"} &ensp; &ensp; [Presentation (NeurIPS workshop version)](#laeo_neurips_video) 

Zhou, G., Dean, V., Srirama, M. K., Rajeswaran, A., Pari, J., **Hatch, K. B.,** Jain, A., Yu, T., Abbeel, P., Pinto, L., Finn, C., and Gupta, A., “Train Offline, Test Online: A Real Robot Learning Benchmark,” *2023 IEEE International Conference on Robotics and Automation (ICRA),* 2023. &ensp; [Website](https://toto-benchmark.org/){:target="_blank"}

<a name="apl_paper"> </a>
Mern, J., **Hatch, K.,** Silva, R., Hickert, C., Sookoor, T., and Kochenderfer, M. J., "Autonomous Attack Mitigation for Industrial Control Systems," *International Conference on Dependable Systems and Networks (DSN'22),* 2022, pp. 28–36.
&ensp; [PDF](https://arxiv.org/abs/2111.02445){:target="_blank"}

<a name="iros_paper"> </a>
Senanayake, R.\*, **Hatch, K.\*,** Zheng, J., and Kochenderfer, M. J., "3D Radar Velocity Maps for Uncertain Dynamic Environments," *IEEE International Conference on Intelligent Robots and Systems (IROS),* 2021. &ensp; [PDF](https://arxiv.org/abs/2107.11039){:target="_blank"} &ensp; &ensp; [Presentation](#iros_video)

<a name="scitech_paper"> </a>
**Hatch, K.,** Mern, J., and Kochenderfer, M. J., "Obstacle Avoidance Using a Monocular Camera," *AIAA SciTech Forum,* 2021. &ensp; [PDF](https://arxiv.org/abs/2012.01608){:target="_blank"} &ensp; &ensp; [Presentation](#scitech_video)

<!-- #### Workshop Papers

**Hatch, K. B.,** Shetty, S. J., Eysenbach, B., Yu, T., Rafailov, R., Salakhutdinov, R., Levine, S., and Finn, C., "Contrastive Example-Based Control," *NeurIPS 2022 Offline RL and Deep RL Workshops,* 2022. &ensp; [PDF](https://openreview.net/pdf?id=QFmjXoxyLR){:target="_blank"} &ensp; &ensp; [Presentation](#laeo_neurips_video)

Mern, J., Krishnan, S., Yildiz, A., **Hatch, K.,** and Kochenderfer, M. J., "Interpretable Local Tree Surrogate Policies,"  *The AAAI Workshop on Artificial Intelligence Safety 2022 (SafeAI),* 2022. &ensp; [PDF](https://arxiv.org/abs/2109.08180){:target="_blank"}

**Hatch, K.\*,**Yu, T.\*, Rafailov, R., and Finn, C., "Example-Based Offline Reinforcement Learning without Rewards," *NeurIPS Offline RL Workshop,* 2021. &ensp; [PDF](https://offline-rl-neurips.github.io/2021/pdf/53.pdf){:target="_blank"} -->




**\* denotes equal contribution**


<a name="Research"> </a>
## Research


<!-- At TRI, I am developing a method to leverage Internet scale video data for robot learning. Videos of humans interacting with objects are available in massive quantity on the Internet, but this type of data does not contain the action labels needed to directly train a robot policy. In order to utilize from this data, I am working on a hierarchical imitation learning-based method that trains a high-level policy on action-free video data to output subgoals that can then be reached by a low-level robot policy. -->
<!-- I am working on a hierarchical imitation learning-based approach to leverage action-free video data for learning robot policies, as well as exploring offline RL-based approaches. -->
At TRI, I am researching how to leverage Internet scale video data for robot learning. Videos of humans interacting with objects are available on a massive scale on the Internet, but this type of data does not contain the action labels needed to directly train a robot policy. In order to utilize this data, I am developing a hierarchical imitation learning-based approach that trains a high-level policy on action-free video data to output subgoals, which can then be reached by a low-level robot policy.


Prior to starting at TRI, I was a master's student in the Computer Science Department at Stanford University and conducted research under Prof. [Chelsea Finn](https://ai.stanford.edu/~cbfinn/){:target="_blank"} in the Stanford [IRIS](https://irislab.stanford.edu/){:target="_blank"} Lab. In Prof. Finn's group, my research focused on addressing three key limitations in scaling offline RL methods to realistic robot applications: 1) learning from play data/autonomously collected robot data without reward labels 2) pretraining on offline data and then finetuning online 3) and developing realistic simulated benchmarks. I published three first/co-first author papers on this research: 

1. [D5RL](#d5rl): a simulated robotics benchmark to evaluate offline RL methods on visually diverse, realistic simulated robotics tasks. Co-first author on paper under review at the International Conference on Learning Representations (ICLR) 2024.
2. [MOTO](#moto): a model-based RL method designed for efficient offline-to-online finetuning for vision-based manipulation tasks. Co-first author on paper in the Conference on Robot Learning (CoRL) 2023.
3. [LAEO](#laeo): an offline reinforcement learning method using contrastive learning for data without reward labels. First author on paper in the Learning for Dynamics & Control Conference (L4DC) 2023 conference.

As an undergraduate student, I worked on research under Prof. [Mykel Kochenderfer](https://mykel.kochenderfer.com/){:target="_blank"} in the Stanford Intelligent Systems Laboratory ([SISL](https://sisl.stanford.edu/){:target="_blank"}). I also interned at the Johns Hopkins University Applied Physics Laboratory ([APL](https://www.jhuapl.edu/){:target="_blank"}). My research focused on using machine learning and RL techniques to improve collision avoidance in autonomous vehicles and UAVs, as well as using RL to autonomously mitigate cybersecurity threats. I published two first/co-first author papers and one second author paper on this research. 
1. A [method](#iros_paper) to learn 3D velocity maps from radar data for use by autonomous vehicles. Co-first author on paper in the IEEE International Conference on Intelligent Robots and Systems (IROS) 2021 conference.
2. A [collision avoidance system](#scitech_paper) for autonomous drones using monocular vision and deep reinforcement learning. First author on paper in the American Institute of Aeronautics and Astronautics (AIAA) SciTech Forum 2021 conference.
3. An [RL-based method](#apl_paper) for autonomously responding to cybersecurity threats on industrial control systems. Second author on paper in the International Conference on Dependable Systems and Networks (DSN’22), 2022.


<a name="Education"> </a>
## Education

#### Master's GPA: 4.05  

#### M.S. in Computer Science, Stanford University, 2021 - 2023
<!-- ##### GPA: 4.05  -->

#### B.S. with honors in Computer Science, Stanford University, 2017 - 2022
<!-- ##### GPA: 3.78 -->



<!-- #### Artificial Intelligence, Machine Learning, and Other Relevant Coursework -->
<!-- ##### Relevant Coursework -->

<html>
 <head>
   <style type="text/css">
    ul {
     list-style-type: none;
    }
   </style>
    <style>
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns*/
    <!-- .col0 {
    float: left;
    width: 70%;
    }

    .col1 {
    float: left;
    width: 13%;
    }

    .col2 {
    float: left;
    width: 14%;
    } -->
    .col0 {
    float: left;
    width: 87%;
    }

    .col1 {
    float: left;
    width: 13%;
    }


    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    </style>
 </head>
 <body>
    <div class="row">
        <div class="col0">
            <h5> Relevant Coursework </h5>
            <p>
              <ul>
                <li>CS 239: Advanced Topics in Sequential Decision Making</li>
                <li>CS 332: Advanced Survey of Reinforcement Learning</li>
                <li>MS&E 338: Reinforcement Learning: Frontiers</li>
                <li>CS 234: Reinforcement Learning</li>
                <li>CS 330: Deep Multi-task and Meta Learning</li>
                <li>CS 228: Probabilistic Graphical Models: Principles and Techniques</li>
                <li>CS 231N: Convolutional Neural Networks for Visual Recognition</li>
                <li>CS 224N: Natural Language Processing with Deep Learning</li>
                <li>CS 224U: Natural Language Understanding</li>
                <li>CS 238: Decision Making Under Uncertainty</li>
                <li>CS 224W: Machine Learning with Graphs</li>
                <li>CS 361: Engineering Design Optimization</li>
                <li>CS 221: Artificial Intelligence: Principles and Techniques</li>
                <li>CS 205L: Continuous Mathematics with an Emphasis on Machine Learning</li>
                <li>MATH 104: Applied Matrix Theory</li>
                <li>CS 110: Principles of Computer Systems</li>
              </ul>
            </p>
        </div>

        <div class="col1">
            <h5>Grade</h5>
            <p>
              <ul>
                <li>A+</li>
                <li>A</li>
                <li>A</li>
                <li>A</li>
                <li>A</li>
                <li>A</li>
                <li>S*</li>
                <li>A</li>
                <li>A</li>
                <li>A</li>
                <li>A-</li>
                <li>A</li>
                <li>A</li>
                <li>A+</li>
                <li>A</li>
                <li>A</li>
              </ul>
            </p>
        </div>

        <!-- <div class="col2">
            <h5>Quarter</h5>
            <p>
              <ul>
                <li>Fall 2022</li>
                <li>Spr 2022</li>
                <li>Win 2022</li>
                <li>Win 2022</li>
                <li>Fall 2021</li>
                <li>Spr 2020</li>
                <li>.</li>
                <li>Win 2020</li>
                <li>Win 2020</li>
                <li>.</li>
                <li>Fall 2019</li>
                <li>Spr 2019</li>
                <li>Fall 2018</li>
              </ul>
            </p>
        </div> -->
    </div>
 </body>
</html>

\* Letter grades not offered during the Spr 2020 quarter due to the COVID-19 pandemic.


<!-- CS 239: Advanced Topics in Sequential Decision Making \textbf{(A+)}; 
CS 332: Advanced Survey of Reinforcement Learning (\textbf{A});  
MS\&E 338: Reinforcement Learning: Frontiers \textbf{(A)}; 
CS 234: Reinforcement Learning \textbf{(A)}; 
CS 330: Deep Multi-task and Meta Learning \textbf{(A)}; 
CS 228: Probabilistic Graphical Models: Principles and Techniques (\textbf{A});  
CS 231N: Convolutional Neural Networks for Visual Recognition \textbf{(S*)}; 
CS 224N: Natural Language Processing with Deep Learning \textbf{(A)}; 
CS 224U: Natural Language Understanding (\textbf{A}); 
CS 238: Decision Making Under Uncertainty \textbf{(A)}; 
CS 224W: Machine Learning with Graphs \textbf{(A-)};
CS 361: Engineering Design Optimization (\textbf{A});  
CS 221: Artificial Intelligence: Principles and Techniques \textbf{(A)}; 
CS 205L: Continuous Mathematics with an Emphasis on Machine Learning \textbf{(A+)}; 
MATH 104: Applied Matrix Theory \textbf{(A)}; 
CS 110: Principles of Computer Systems \textbf{(A}) -->

<a name="Volunteer"> </a>
## Volunteer Work

#### East Palo Alto Stanford Academy ([EPASA](https://haas.stanford.edu/student-programs/education-partnerships/east-palo-alto-stanford-academy-epasa){:target="_blank"})
*October 2018 – March 2020*

*Volunteer Tutor*



[EPASA](https://haas.stanford.edu/student-programs/education-partnerships/east-palo-alto-stanford-academy-epasa){:target="_blank"} is a program run through Stanford University in which undergraduate students tutor middle school students who attend school in East Palo Alto.
As a volunteer tutor at EPASA, I tutored seventh and eighth grade students in math and English.

#### Stanford 1st Ward Volunteer Tutoring Program
*September 2017 – June 2019*

*Volunteer Tutor*

The Stanford 1st Ward Volunteer Tutoring Program is a program run through a local religious organization that provides free tutoring to K-12 students from around the South San Francisco Bay Area.
As a volunteer tutor, I tutored students in math, reading, and English.


<a name="Presentations"> </a>
## Video Presentations

<!-- <details open>
  <summary>Collapse</summary> -->

<a name="laeo_neurips_video"> </a>
**"Offline Example-Based Control," NeurIPS Offline RL and Deep RL Workshops, 2022.**
{% include youtubePlayer.html id=page.neuripsWorkshop2022YouTubeId %}

&nbsp;
&nbsp;
&nbsp;



<a name="iros_video"> </a>
**"3D Radar Velocity Maps for Uncertain Dynamic Environments," IEEE International Conference on Intelligent Robots and Systems (IROS), 2021.**
{% include youtubePlayer.html id=page.irosYouTubeId %}

&nbsp;
&nbsp;
&nbsp;

<a name="scitech_video"> </a>
**“Obstacle Avoidance Using a Monocular Camera,” AIAA SciTech Forum, 2021.**
{% include youtubePlayer.html id=page.scitechYouTubeId %}

<!-- </details> -->
