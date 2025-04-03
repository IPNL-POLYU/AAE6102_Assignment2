# AAE6102 Assignment 2

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

**Due Date:** 24 April 2025


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


### Task 3 – RAIM (Receiver Autonomous Integrity Monitoring)  
RAIM is a critical technique for detecting and excluding faulty GNSS measurements. In this task, you are required to:
- Develop a **weighted RAIM algorithm** to improve positioning performance and compute the protection level of the WLS solution.
- Based on your **weighted least squares (WLS) code from Assignment 1**, implement a weighted RAIM algorithm to process the provided **“Open-Sky” data**.
- Ensure your solution effectively detects and mitigates the impact of faulty or low-quality measurements.


### Task 4 – LEO Satellites for Navigation  
Low Earth Orbit (LEO) satellites are widely used for communication purposes but present unique challenges when utilized for navigation. Write a short essay (500–1000 words) discussing:
- The difficulties and challenges of using **LEO communication satellites** for GNSS navigation.


### Task 5 – GNSS Remote Sensing  
GNSS is not only used for positioning and navigation but also has significant applications in remote sensing. Write a short essay (500–1000 words) discussing **the impact of GNSS in remote sensing**. Please select **one** of the following topics covered in the lecture to discuss:
- **GNSS Reflectometry (GNSS-R)**
- **GNSS Interferometric Reflectometry (GNSS-IR)**
- **GNSS Radio Occultation (GNSS-RO)**


---
## Submission Instructions
- Submit a **technical report** and **source code** via **GitHub (Readme.md format)**.
- Include all necessary explanations, methodologies, and results in computational tasks.
- Share the GitHub repository link via email with:  
  - **Dr. Hoi-Fung Ng** (hf-ivan.ng@connect.polyu.hk)  
  - Other **teaching assistants**  
  - The **course lecturers**  
- **Deadline:** 24th April 2025  

