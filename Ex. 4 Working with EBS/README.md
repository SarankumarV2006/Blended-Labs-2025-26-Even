# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: Sarankumar.V
* **Register Number**: 212224220089
* **Date of Submission**: 22.05.2026

---

## Objective

The objective of this experiment is to understand how Amazon Elastic Block Store (EBS) provides persistent block-level storage for EC2 instances. This lab focuses on creating and attaching an EBS volume, formatting and mounting it on an EC2 instance, storing data, and verifying data persistence after instance reboot.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing EC2 instance (Amazon Linux 2 preferred)
* Basic knowledge of Linux commands

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Amazon EBS
* SSH Client (Terminal / PuTTY)

---

## Tasks Performed

### Task 1: Explore Amazon EBS

Explore the Amazon EBS service through the EC2 dashboard. Observe different volume types such as General Purpose SSD (gp2/gp3), Provisioned IOPS SSD, Throughput Optimized HDD, and Cold HDD.

---

### Task 2: Create an EBS Volume

Create a new EBS volume in the same Availability Zone as the EC2 instance. Choose an appropriate size and volume type.

---

### Task 3: Attach EBS Volume to EC2 Instance

Attach the created EBS volume to the running EC2 instance as an additional block device.

---

### Task 4: Format the EBS Volume

Connect to the EC2 instance using SSH and format the attached volume with a file system (for example, ext4).

---

### Task 5: Mount the EBS Volume

Mount the formatted volume to a directory in the EC2 instance (for example, /data or /mnt/ebs).

---

### Task 6: Store Data in EBS Volume

Create files and directories inside the mounted EBS volume and store sample data.

---

### Task 7: Verify Data Persistence

Reboot the EC2 instance and verify that the data stored in the EBS volume is still available after reboot.

---

## Workflow (Student Explanation)

Accessed IAM console and reviewed users and groups.
Inspected policy permissions attached to groups.
Assigned users to groups based on their roles.
Logged in as each IAM user using the sign-in URL.
Validated permissions by accessing AWS services.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume Created

<img width="913" height="418" alt="image" src="https://github.com/user-attachments/assets/c1b42206-44e7-4f57-998f-a90aad6b43c3" />


---

### Screenshot 2: EBS Volume Attached to EC2

<img width="940" height="443" alt="image" src="https://github.com/user-attachments/assets/2d6cf774-0d58-4ea5-a474-cd5eab2e4161" />


---

### Screenshot 3: Mounted Volume with Data

<img width="943" height="478" alt="image" src="https://github.com/user-attachments/assets/50e7caa9-a5ac-4627-893d-faa772ff5c48" />

---

## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
