To pass this course item, you must receive at least 100%, or 1 out of 1 points, by completing the activity and answering a final quiz question. Once you have completed the activity, review the feedback at the bottom of the page. You can learn more about the graded and practice items in the [course overview](https://www.coursera.org/learn/assets-threats-and-vulnerabilities/supplement/ChT4c/course-5-overview).

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Bj7JfncRS82tZctuOq3hsg_a030f8dbfa6d4ece99dd3ea09b35b4f1_QGihrALZZ0PyKinvbUTTPWGMSFS7ukNkdHoNt7IyAz_kGRO2w-llRgqWrUfBHbUjOXekXsgwd7PXqfr-VXnVZa0maxzWwIouFv-6CdYwEr4DwgZaD-qkktNplyURzjd_WbTxLVrRBcBSw-wJB5lVnafBos22RKhU3V2WGyeDcojx0HV2Q-gH27ONmhEpsA?expiry=1716681600000&hmac=Gc74R8bCOiFQB4NpbWUd0qQ6Kf_V_-6p0WE2GyIm1aA)

## Activity Overview

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/MHO21nJzTRKxg7l5L2rN9w_fdfdd619c8064ede874cf4c5dc8c80f1_XKXIqIxadC-iw2IlzPqJ6iAet-wbTDlW99IvQXMeq5AZiaRVuBBKh89eaRxtvbI_7N2iq79UwA4RKXaIQN1GxzMmT9C9FcPb-urH-9_9hvjx3-NPohCkRip-9KfXS1ttayrElT1CYIag0htES_8Qw2lECIdRF0iyP7rESMPraO6M2oDKVscDnGLTci3obw?expiry=1716681600000&hmac=tWl0tMdsrOKcTUk2MNQYGFEwlGysZwkdPTKl7-BHzr8)

In this activity, you will assess the attack vectors of a USB drive. You will consider a scenario of finding a USB drive in a parking lot from both the perspective of an attacker and a target.

USBs, or flash drives, are commonly used for storing and transporting data. However, some characteristics of these small, convenient devices can also introduce security risks. Threat actors frequently use USBs to deliver malicious software, damage other hardware, or even take control of devices. **USB baiting** is an attack in which a threat actor strategically leaves a malware USB stick for an employee to find and install to unknowingly infect a network. It relies on curious people to plug in an unfamiliar flash drive that they find.

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work.

## Scenario

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/ykVgPbVfQTyHhzY47TDUfA_c6b2d816b1814ad7ac8d4e1b9972c9f1_lIOmSDAl9YSFDhxmRNYptG2vqCBPj8D14NiSx3VrHTO4_3nzyIS1nqH72R0C7ROcXtg3gK4RZIr9A-fdZDiD2iMUjCN9P9mC2bPiHBIegUBco56voUfCRfE96EvP49VjrqpVxbSNn1mNb8nzu4YT-wzVb4zubuf9nRVXGYNcB-16vmpmNIUegpMndAysgQ?expiry=1716681600000&hmac=EFQX2a91B1hHV3e46FgBtU54dLeo4phj5aY42vz77wE)

Review the following scenario. Then complete the step-by-step instructions.

You are part of the security team at Rhetorical Hospital and arrive to work one morning. On the ground of the parking lot, you find a USB stick with the hospital's logo printed on it. There’s no one else around who might have dropped it, so you decide to pick it up out of curiosity.

You bring the USB drive back to your office where the team has virtualization software installed on a workstation. Virtualization software can be used for this very purpose because it’s one of the only ways to safely investigate an unfamiliar USB stick. The software works by running a simulated instance of the computer on the same workstation. This simulation isn’t connected to other files or networks, so the USB drive can’t affect other systems if it happens to be infected with malicious software.

## Step-By-Step Instructions

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/pakIFhsXRcmpyggM5NOhCw_b2d5e6f547484854af18751ba5ab9ef1_lIOmSDAl9YSFDhxmRNYptG2vqCBPj8D14NiSx3VrHTO4_3nzyIS1nqH72R0C7ROcXtg3gK4RZIr9A-fdZDiD2iMUjCN9P9mC2bPiHBIegUBco56voUfCRfE96EvP49VjrqpVxbSNn1mNb8nzu4YT-wzVb4zubuf9nRVXGYNcB-16vmpmNIUegpMndAysgQ?expiry=1716681600000&hmac=Qtlao6A-uylRW3jh97M-IV3CzcAxZQYiX4EqDco7Vko)

Follow the instructions and answer the question below to complete the activity.

### **Step 1: Access the template**

To use the template for this course item, click the link and select _Use Template_.

Link to template: [Parking lot USB exercise](https://docs.google.com/document/d/1jdI0FecPuabVB5ZI7na8C0Jm8J6bFlU76AEKD0T8dSw/template/preview?usp=sharing&resourcekey=0-BnHBngk9keuLxbaDs5koeQ)

### Step 2: Inspect the contents of the USB stick

You create a virtual environment and plug the USB drive into the workstation. The contents of the device appear to belong to Jorge Bailey, the human resource manager at Rhetorical Hospital.

![This screenshot shows the contents of this USB drive which contains a mix of personal and work-related files.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/j63kkSHeTXGfrRT0zr6gcA_9bf3e3007bdf4bea8386db81a87dbaf1_VqgtvoNaBDctd1W-kA6VSkWFn7WHRUmC0DG14qd0_buNljd43qfi-yDo7c4ufxJj9sv0ywxjYg8t274hUQX_Phndaf35kM8NqjgNkKn3LfuZid4DJ6okJf79ZKxDAu8CpVW-6Ol9IePpHO7mz7HKqHnvuiLJxLj-gpzKTU9uhz4yU35j3zY3xEd7HmG4w?expiry=1716681600000&hmac=foV0Nz4Z0CMisOP1OzUzNpn-8r2aUXknMnPh5E2vHaQ)

Jorge's drive contains a mix of personal and work-related files. For example, it contains folders that appear to store family and pet photos. There is also a new hire letter and an employee shift schedule.

Review the types of information that Jorge has stored on this device. Then, in the **Contents** row of the activity template, write **2-3 sentences** (40-60 words) about the type of information that's stored on the USB drive.

_**Note:**_ _USB drives often contain an assortment of personally identifiable information (PII). Attackers can easily use this sensitive information to target the data owner or others around them._

### Step 3: Apply an attacker mindset to the contents of the USB drive

The flash drive appears to contain a mixture of personal and work-related files. Consider how an attacker might use this information if they obtained it. Also, consider whether this whole event was staged.

For example, an attacker could have placed these files on the USB drive as a distraction. They might have targeted Jorge or someone he knows, hoping they would find the device and plug it into their workstation. In doing so, the attacker could establish a backdoor into the company's systems while the unsuspecting target browsed through the files.

In the **Attacker mindset** row of the activity template, write **2-3 sentences** (40-60 words) about how this information could be used against Jorge or the hospital.

_**Pro tip:**_ _The Cybersecurity and Infrastructure Security Agency (CISA) provides some_ [_security tips on using caution with USB drives_](https://www.cisa.gov/news-events/news/using-caution-usb-drives)_, including keeping personal and business drives separate._

### Step 4: Analyze the risks of finding a parking lot USB

You have _not_ opened any of the files on the device, which is best practice. 

Attackers sometimes conduct USB baiting attacks to deliver malicious code that they've crafted.

However, this USB drive was still a security risk even though it did not contain malicious code. It could have easily been found by an attacker who might have used its contents to plan a variety of attacks.

Consider some of the risks associated with USB baiting attacks:

- What types of malicious software could be hidden on these devices? What could have happened if the device were infected and discovered by another employee?
    
- What sensitive information could a threat actor find on a device like this?
    
- How might that information be used against an individual or an organization?
    

In the **Risk analysis** row of the activity template, write **3 or 4 sentences** (60-80 words) describing any technical, operational, or managerial controls that could mitigate USB baiting attacks.

## What to Include in Your Response

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Bf64MyIBQwq0wdFlPObPAA_2bec6b852f814eb9b6579db255c2abf1_MZdm9Oqo0HeGknQppyFj-9UV4aOR3ULbSmjyXDQNkAs2QELmiBz6D0l-4l8BZxUvqNrAFbZ81SrgUH9NPSVDCbEpQMhYK26Ah5qn_00TXLcoYvf5W8bJnOJ01MuXDMh22S3i0PUMqI-t3787MEjqhwvPxOZO6Ch4jM3mqbT6OwmlJncTZ8v4_1LNIVtDdw?expiry=1716681600000&hmac=YHyOYqTIK4qv70jy1rw5pe197HDHzsTaqnsFT514jUk)

Be sure to address the following criteria in your completed activity: 

- 2-3 sentences about the types of information stored on the USB drive
    
- 2-3 sentences about how the information could be used against the owner and/or organization
    
- 3-4 sentences analyzing the risks of USB baiting attacks