TESTING SISTEM
Sure, here's a detailed scheme to test your smart glasses with a focus on obtaining numeric results. We'll break down the testing into specific metrics and define how to measure them quantitatively.

### 1. **Functional Testing**

#### Infrared Sensor Accuracy
- **Objective:** Determine the accuracy of the infrared sensor in detecting eye blinks.
- **Procedure:** 
  1. Have a user blink 100 times.
  2. Record the number of blinks detected by the sensor.
- **Metric:** Accuracy percentage = (Detected blinks / Actual blinks) * 100

#### PPG Sensor Accuracy
- **Objective:** Assess the accuracy of the PPG sensor in measuring pulse rate.
- **Procedure:** 
  1. Compare the PPG sensor readings with a standard medical pulse oximeter over 5-minute intervals.
  2. Conduct the test on 10 different users.
- **Metric:** Mean Absolute Percentage Error (MAPE) = (|PPG reading - Oximeter reading| / Oximeter reading) * 100

#### Buzzer Activation Time
- **Objective:** Measure the time taken for the buzzer to activate after drowsiness detection.
- **Procedure:** 
  1. Simulate drowsiness using predefined parameters (e.g., prolonged eye closure).
  2. Record the time from drowsiness detection to buzzer activation.
- **Metric:** Average activation time in seconds over 10 trials.

### 2. **Integration Testing**

#### Data Transmission Accuracy
- **Objective:** Ensure accurate data transmission from the glasses to the mobile app.
- **Procedure:** 
  1. Generate known eye blink and PPG data.
  2. Transmit this data to the app and compare the received data.
- **Metric:** Transmission accuracy = (Correct data points received / Total data points sent) * 100

### 3. **User Testing**

#### Usability Score
- **Objective:** Evaluate user satisfaction and usability.
- **Procedure:** 
  1. Have 20 users wear the glasses for a driving simulation.
  2. Collect feedback using the System Usability Scale (SUS) questionnaire.
- **Metric:** SUS score (out of 100)

#### Effectiveness in Reducing Drowsiness
- **Objective:** Measure the effectiveness of the glasses in reducing drowsiness.
- **Procedure:** 
  1. Have 10 users drive in a simulator with and without the glasses.
  2. Measure the frequency of drowsiness indicators (e.g., prolonged eye closures) in both scenarios.
- **Metric:** Reduction percentage = ((Drowsiness incidents without glasses - Drowsiness incidents with glasses) / Drowsiness incidents without glasses) * 100

### 4. **Performance Testing**

#### Response Time
- **Objective:** Measure the response time of the system from drowsiness detection to buzzer activation.
- **Procedure:** 
  1. Record the time taken for the system to detect drowsiness and activate the buzzer over 10 trials.
- **Metric:** Average response time in seconds

#### Battery Life
- **Objective:** Assess the battery life under normal operating conditions.
- **Procedure:** 
  1. Fully charge the battery.
  2. Record the time until the battery is depleted under continuous use.
- **Metric:** Battery life in hours

### 5. **Reliability Testing**

#### Long-term Reliability
- **Objective:** Determine the long-term reliability of the glasses.
- **Procedure:** 
  1. Operate the glasses continuously for 30 days.
  2. Record any sensor malfunctions or failures.
- **Metric:** Mean Time Between Failures (MTBF) in hours

### 6. **Safety Testing**

#### Electrical Safety
- **Objective:** Ensure the device is safe to use.
- **Procedure:** 
  1. Measure the leakage current.
  2. Ensure it is within safe limits according to relevant standards.
- **Metric:** Leakage current in microamperes (µA)

### Test Plan Execution

1. **Preparation**
   - Define test cases and gather necessary equipment.
   - Prepare testing environment and recruit participants.

2. **Execution**
   - Perform functional, integration, user, performance, reliability, and safety tests.
   - Record data meticulously.

3. **Analysis**
   - Analyze collected data to compute the metrics.
   - Compare results against predefined success criteria.

4. **Reporting**
   - Document results and any identified issues.
   - Provide recommendations for improvements.

5. **Iteration**
   - Implement changes based on test findings.
   - Repeat tests to validate improvements.

### Sample Metrics Table

| Test Type              | Metric                                 | Target Value          |
|------------------------|----------------------------------------|-----------------------|
| Infrared Sensor        | Accuracy (%)                           | ≥ 95%                 |
| PPG Sensor             | MAPE (%)                               | ≤ 5%                  |
| Buzzer Activation      | Average activation time (s)            | ≤ 1 second            |
| Data Transmission      | Transmission accuracy (%)              | ≥ 99%                 |
| Usability              | SUS score (out of 100)                 | ≥ 85                  |
| Effectiveness          | Reduction percentage (%)               | ≥ 70%                 |
| Response Time          | Average response time (s)              | ≤ 1 second            |
| Battery Life           | Battery life (hours)                   | ≥ 12 hours            |
| Reliability            | MTBF (hours)                           | ≥ 1000 hours          |
| Electrical Safety      | Leakage current (µA)                   | ≤ 10 µA               |

This structured approach ensures that you obtain quantifiable results for each aspect of your smart glasses, facilitating objective evaluation and necessary improvements.
