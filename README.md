# Man-In-The-Middle-Attack-Detection-Using-Ensemble-Learning
Cyber security is one of the most vital demands about network infrastructure and hence very necessary to protect the information sent and received during data transmission against outside factors trying to intercept systems. Man-In-The-Middle (MITM) attacks can dramatically compromise thesecurity of wireless fidelity network where an attacker eavesdrops and intercepts the communication medium over the wireless communication networks. This kind of attack aims to steal sensitive data such as credit card details, login accounts, and other important financial transactions. Even though, many detection techniques have been proposed to mitigate Man-In-The-Middle attacks, however, this attack still occurs and causes tremendous damages. We propose a systematic approach using Ensemble Learning to detect MITM attack packets in a network. Our Ensemble Learning approach proves to be a valid stratagem for the detection of MITM Attack Packets.

## Architecture of the proposed Ensemble Learning model to detect Man-In-The-Middle Attacks
![architecture-2-2](https://user-images.githubusercontent.com/91937177/211618549-2c4d5383-9d3f-42d3-b591-a2e700a6eaa1.png)
The adaptive ensemble learning model showed mainly includes the following processes:
1) Inputting the IoT intrusion training dataset.
2) Using the pre-processing module to convert the character-type into numbers, standardizing the data, and deleting unnecessary features.
3) Ensemble training of the aforementioned algorithms using pre-processed data.
4) According to the training accuracy of each algorithm, ensemble learning is performed.
5) Each algorithm selected is used to detect the test set, output the preliminary predict classification, and then calculate result using the most accurate algorithm (here Random Forest).

![chart-3](https://user-images.githubusercontent.com/91937177/211621146-a25aa87d-d4bf-40a1-9bc7-7f850adb8def.png)

Paper: https://ieeexplore.ieee.org/document/9984365
Authors: 
Krittika Das, Department of CSE, Techno International New Town, Kolkata, India
Rajdeep Basu, Department of AI & ML, Techno International New Town, Kolkata, India
Raja Karmakar, Department of CSE, Techno International New Town, Kolkata, India
