# Network Troubleshooting Simulation


## 1. Setting Up Virtual Network

- Step 1: Create multiple `VMs` in AWS with two Windows Instances.
  <img width="800" alt="1 ubuntu and 1 windows instance spun up" src="https://github.com/aizhuxue007/active-directory-aws/assets/17282458/14b49057-5e09-4189-9a7c-07f9717ad78c">
  
- Step 2: Configure network settings for each `VM` to simulate a real network environment, ensuring they can communicate. Create a `Virtual Private Cloud`.
  <img width="800" alt="virtual private cloud" src="https://github.com/aizhuxue007/active-directory-aws/assets/17282458/e0115998-d5e0-4a1b-9454-5b41d9755968">

- Step 3: Create security groups to allow `SSH`, `RDP` and `ICMP` traffic inbound and outbound. Add this security group to the VMs.
  <img width="800" alt="Add custom security group to both instances" src="https://github.com/aizhuxue007/active-directory-aws/assets/17282458/c54587f1-87a3-4c63-8300-11d6fe3a9fb6">
  
## 2. Connecting two devices

- Step 1:  `Ping` to Linux using Terminal from Windows
  <img width="800" alt="Screenshot 2024-02-05 at 8 28 59 PM" src="https://github.com/aizhuxue007/active-directory-aws/assets/17282458/96e94f61-1ba6-4fa7-852b-f5e76f9ab1d2">

## 3. Analyzing and Resolving Issues
  
- Step 1: Use `Wireshark` to analyze traffic
  
<img width="800" alt="Using wireshark" src="https://github.com/aizhuxue007/active-directory-aws/assets/17282458/490afe80-a5b1-412b-a2a7-1da097c531f0">

