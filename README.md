# BlazeMeter Performance Testing Guide  

## Installation and Setup  

### 1. **Sign Up and Login**  
- Visit [https://www.blazemeter.com/](https://www.blazemeter.com/) and create an account.  
- Log in to access the BlazeMeter dashboard.  

### 2. **Install BlazeMeter Chrome Extension (Optional)**  
- Download and install the BlazeMeter Chrome extension for recording user actions.  
- Link it with your BlazeMeter account for seamless test recording.  

---

## Uploading and Running JMeter Scripts  

### Step 1: Prepare JMeter Script  
- Create a JMeter test plan (.jmx file).  
- Ensure all required CSV data files and plugins are included.  

### Step 2: Upload Script to BlazeMeter  
1. Go to the BlazeMeter dashboard.  
2. Click on **“Create Test”** → **“Performance Test.”**  
3. Upload your .jmx file and configure test parameters.  

### Step 3: Configure Test Parameters  
- **Number of Users:** Define the number of concurrent users.  
- **Ramp-Up Time:** Set the duration to gradually add users.  
- **Test Duration:** Specify how long the test should run.  

### Step 4: Run the Test  
- Click on **“Start Test”** to begin.  
- Monitor real-time results from the **Reports** tab.  
