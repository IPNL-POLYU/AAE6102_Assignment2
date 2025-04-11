![image](https://github.com/user-attachments/assets/31ab6c7e-020a-4b69-b6a2-e6a39aafac23)# AAE6102 Assignment 2

## Satellite Communication and Navigation (2024/25 Semester 2)

### The Hong Kong Polytechnic University  
**Department of Aeronautical and Aviation Engineering**  

### Overview  
This repository contains Assignment 2 for AAE6102: Satellite Communication and Navigation. Resources related to this assignment can be found in the repository.


## Guidelines on Using AI  
For Tasks 1, 4, and 5, please provide information on any GenAI models you used to help answer the assignment. You may use multiple models for your answers, and there is no page limit for the prompt you used.  
Here is an example (Grade C if you only use this prompt):  
```  
Model: ChatGPT 4o mini  
Prompt: Please give me the pros and cons of different differential GNSS for smartphone positioning.  
Comment: It’s free and great for reasoning and answering questions.  
Chatroom Link (if any): https://chatgpt.com/share/67ecb200-5da8-8003-8a48-374457b35f18
```  

---

**Due Date:** 1st May 2025


## Assignment Tasks

### Task 1 – Differential GNSS Positioning  
Write a short essay (500–1000 words) comparing the pros and cons of the following GNSS techniques for **smartphone navigation**:
- **Differential GNSS (DGNSS)**
- **Real-Time Kinematic (RTK)**
- **Precise Point Positioning (PPP)**
- **PPP-RTK**

### Task 2 – GNSS in Urban Areas  
Urban areas present significant challenges to GNSS positioning due to signal blockage, multipath effects, and poor satellite visibility. In this task, you are provided with a **skymask**, which indicates the elevation angle representing potential satellite visibility blockage for each corresponding azimuth angle, at the ground truth of the "Urban" environment in Assignment 1.

Your objective is to improve the GNSS positioning performance using the "Urban" data provided. You may apply any suitable methods, techniques, or algorithms to enhance accuracy.  
(*Hint: The skymask can identify satellite visibility blockage by providing satellite azimuth and elevation angles.*)


### Task 3 – GPS RAIM (Receiver Autonomous Integrity Monitoring)  
RAIM is a critical technique for detecting and excluding faulty GPS measurements. In this task, you are required to:
- Develop a **classic weighted RAIM algorithm [1]** to improve and monitor your positioning performance.
- Based on your **weighted least squares (WLS) code from Assignment 1**, implement a weighted RAIM algorithm to process the provided **“Open-Sky” data**.
- Ensure your solution effectively detects and excludes the impact of faulty or low-quality measurements. 
- (Bonus) Compute the 3D protection level (PL) based on: 1). 10^-2 of probability of false alarm (P_fa), and 2). 10^-7 of probability of missed detection (P_md). The GPS pseudorange measurement sigma (σ) is 3m.
- (Bonus) Evaluate the GNSS integrity monitoring performance using a Stanford Chart analysis, given that the 3D alarm limit (AL) is 50 meters. 

Hint 1: Calculate the only solution so that the minimum degree of freedom is 4 (meaning you can use the same equations given in the lecture notes).

Hint 2:  A threshold set at 5.33 σ, the probability that random Gaussian noise causes a value to exceed that threshold is only 1 in 10 million (10^-7) 

[1] Walter, T., & Enge, P. (1995, September). Weighted RAIM for precision approach. In Proceedings of Ion GPS (Vol. 8, No. 1, pp. 1995-2004). Institute of Navigation. 
https://web.stanford.edu/group/scpnt/gpslab/pubs/papers/Walter_IONGPS_1995_wraim.pdf 

### Task 4 – LEO Satellites for Navigation  
Low Earth Orbit (LEO) satellites are widely used for communication purposes but present unique challenges when utilized for navigation. Write a short essay (500–1000 words) discussing:
- The difficulties and challenges of using **LEO communication satellites** for GNSS navigation. 


### Task 5 – GNSS Remote Sensing  
GNSS is not only used for positioning and navigation but also has significant applications in remote sensing. Write a short essay (500–1000 words) discussing **the impact of GNSS in remote sensing**. Please select **one** of the following topics covered in the lecture to discuss:
- **GNSS Reflectometry (GNSS-R)**
- **GNSS Interferometric Reflectometry (GNSS-IR)**
- **GNSS Radio Occultation (GNSS-RO)**
- **Ionosphere mapping based GNSS ground station**
- **GNSS seismology**


---
## Submission Instructions
- Submit a **technical report** and **source code** via **GitHub (Readme.md format)**.
- Include all necessary explanations, methodologies, and results in computational tasks.
- Share the GitHub repository link via email with:  
  - **Dr. Hoi-Fung Ng** (hf-ivan.ng@connect.polyu.hk)  
  - Other **teaching assistants**  
  - The **course lecturers**  
- **Deadline:** 1st May 2025  

