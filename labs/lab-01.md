# Lab 1
# Computer Systems In-Class Lab Exercises

## Exercise 1: System Hardware Detective (15-20 minutes)

**Format:** Solo or pairs  
**Objective:** Students will identify and analyze their computer's hardware components using built-in system tools.

### Instructions:

1. **Windows Users:** Open "System Information" (type `msinfo32` in Start menu)
   **Mac Users:** Hold Option key + Apple menu → "System Information"
   **Linux Users:** Open terminal and run `lscpu`, `lshw`, or `inxi -F`
   <img width="1487" height="1042" alt="image" src="https://github.com/user-attachments/assets/22f43fd7-1c12-4bc2-8818-971536748906" />


2. **Find and record the following:**
   - **Processor:** Intel(R) Core(TM) i7-14700K, 3400MHz, 20 cores, 28 threads
     <img width="938" height="28" alt="image" src="https://github.com/user-attachments/assets/301ac8a0-99bb-4923-8184-1272e05ceee9" />
   - **RAM:** 32GB DDR5 - 6000MHz
     <img width="486" height="33" alt="image" src="https://github.com/user-attachments/assets/dbf0e2b2-a134-4c44-bce0-3aca6ceaf59b" />
   - **Storage:** Kingston SNV3S1000G — 1TB NVMe SSD
     <img width="242" height="25" alt="image" src="https://github.com/user-attachments/assets/0947c5a5-80f6-40a5-8196-ad635277af08" />
   - **OS:** Windows 11
     <img width="382" height="20" alt="image" src="https://github.com/user-attachments/assets/9f63db6a-39bd-498d-b190-b494d909fcb6" />

3. **Analysis Questions:**
   - **Based on your CPU cores, how many tasks can your processor theoretically handle simultaneously?**  
     My processor can theoretically handle 28 tasks simultaneously, since it has 28 logical threads.

   - **Is your storage primarily HDD or SSD? What are the performance implications?**  
     I have an NVMe SSD as my primary storage, which is the fastest type of storage available today. Unlike an HDD, which is a mechanical drive whose speed depends on its RPM, the NVMe connects directly to the PCIe bus, resulting in significantly faster read/write speeds.

   - **How does your RAM amount compare to typical requirements for modern applications?**  
     I have 32GB of DDR5 RAM running at 6000MHz. Compared to the standard requirement of ~16GB for modern applications, my specs double it.

### Deliverable:
Complete a simple system specification sheet and answer the analysis questions.

---

(Optional)

## Exercise 2: Operating System Feature Hunt (15-20 minutes)

**Format:** Solo or pairs  
**Objective:** Students will explore and identify key OS functions on their own devices.

### Mission:
Find real examples of the five key OS functions running on your computer right now.

### Tasks:

1. **Process Management:**
   - **5 currently running processes:**
     <img width="659" height="311" alt="image" src="https://github.com/user-attachments/assets/71d5ca72-2021-4d7b-baf4-c37af2f2fed6" />
     
     - ASUS Motherboard Fan Control — 1.2% CPU
     - NVIDIA Container — 0.9% CPU
     - Microsoft Word — 0.7% CPU
     - Adobe Acrobat — 0.6% CPU
     - Armoury Crate Service — 0.5% CPU
   - **Process using the most CPU:** ASUS Motherboard Fan Control (1.2%)

2. **Memory Management:**
    <img width="774" height="297" alt="image" src="https://github.com/user-attachments/assets/c1a18c5a-6654-4816-9790-27930aa69719" />
   - **Total RAM usage:** ~38% in use
   - **Application using the most memory:** Brave Browser (1,672.6 MB)
   - **Available free memory:** 19.6 GB
     <img width="127" height="75" alt="image" src="https://github.com/user-attachments/assets/ce316fcb-c67b-4c72-bf50-f74dc532ab6d" />

3. **File System Management:**
   - **Folder created:** `OS_Lab_Test`
   - **Location:** `C:\Users\Paul\Desktop`
   - **Creation date:** Monday, May 4, 2026
   <img width="350" height="283" alt="image" src="https://github.com/user-attachments/assets/11718ef6-ed85-434c-854f-cf3570d69eb1" />

4. **Device Management:**
   - **GPU:** NVIDIA GeForce RTX 5080
     <img width="350" height="64" alt="image" src="https://github.com/user-attachments/assets/788cb120-713a-4097-8868-4b040cde8595" />
   - **CPU:** Intel(R) Core(TM) i7-14700K
     <img width="322" height="56" alt="image" src="https://github.com/user-attachments/assets/d22769f7-7e66-4779-90b4-22d53506bdfe" />
   - **SSD:** Kingston SNV3S1000G
     <img width="272" height="58" alt="image" src="https://github.com/user-attachments/assets/e99516fc-4304-4f97-aa66-68d6950a955f" />

5. **Security Features:**
   - ✅ Windows Defender is running 
   <img width="73" height="69" alt="image" src="https://github.com/user-attachments/assets/6d3024ae-f589-428c-bbf0-4421af5056b0" />
   - ✅ Automatic updates are enabled
   <img width="886" height="70" alt="image" src="https://github.com/user-attachments/assets/0c4035a1-70b3-4607-b941-988f09dc9ff9" />
   - ✅ Recent security scan completed successfully
   <img width="886" height="417" alt="image" src="https://github.com/user-attachments/assets/15f3e143-2316-407f-9205-323f16f46b70" />

### Challenge Questions:
- **Which process is using the most resources and why might that be?**  
  Brave Browser, because it's a browser and I had around 7 tabs open, which requires a significant amount of RAM.
  <img width="484" height="71" alt="image" src="https://github.com/user-attachments/assets/983ce18d-82f8-4d6a-91fc-8a224406d8e8" />

- **What would happen if your OS didn't manage memory automatically?**  
  It would lead to multiple crashes and the infamous Blue Screen of Death (BSOD) on Windows.

- **How does your OS protect you from security threats?**  
  With real-time protection through Windows Defender, network monitoring, and firewall security.

### Deliverable:
Complete a checklist of found features and answer the challenge questions.

---

## Lab Rubric
**Total Points: 2 marks**

## Requirements for Completion:
* **Exercise 1 (Required):** Complete system specification sheet with all hardware components identified AND answer all three analysis questions with thoughtful responses
* **Exercise 2 (Optional):** If attempted, complete feature checklist for all 5 OS functions AND answer challenge questions

## Lab Rubric:

| Criteria | Poor - 0 mark | Fair - 1 mark | Good - 2 marks |
|---|---|---|---|
| Lab Completion | Missing system specification data OR analysis questions not attempted OR answers lack depth (single sentence, vague responses that don't address the questions) | Successfully identified most hardware components and completed system specification sheet, but analysis questions show minimal effort or understanding | Successfully completed full system specification sheet with accurate hardware identification AND provided thoughtful analysis answers that demonstrate understanding of hardware implications |
