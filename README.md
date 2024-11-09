# Velociraptor
Velociraptor is a lightweight, open-source endpoint detection and response (EDR) tool often used for cybersecurity monitoring and threat hunting. 

Velociraptor is a powerful, open-source endpoint detection and response (EDR) and threat-hunting tool designed for cybersecurity professionals to gather, analyze, and act on data from endpoints in a fast, efficient, and flexible manner. It was built for both real-time monitoring and forensic analysis, making it highly effective for both proactive threat hunting and post-compromise investigation.

### Key Features and Functions of Velociraptor:

1. **Endpoint Monitoring**:
   - Velociraptor operates as an agent deployed on endpoints (workstations, servers, etc.). Once installed, it can collect a wide range of system data, including process activity, network connections, file system changes, user activity, and more.
   - It provides continuous, real-time monitoring of these systems, helping identify anomalies that may indicate malicious activity or potential security breaches.

2. **Querying and Data Collection**:
   - Velociraptor allows users to define queries written in a custom query language to gather specific data from endpoints. For example, you can query for specific file changes, registry modifications, or even check the presence of particular processes.
   - Queries can be run remotely across multiple endpoints simultaneously, enabling large-scale investigations without manually logging into each machine.

3. **Live Data Acquisition**:
   - It can acquire live data from endpoints, such as capturing memory dumps, executing scripts, or running commands on a machine. This feature is particularly useful for real-time investigation during active security incidents.
   - Velociraptor's live acquisition capabilities are particularly effective in gathering forensic evidence without disrupting the system too much.

4. **Incident Response and Threat Hunting**:
   - It supports advanced incident response capabilities, such as querying for indicators of compromise (IoCs) or collecting detailed system logs and behaviors related to potential threats.
   - Security analysts can actively hunt for threats using the tool’s query engine, which enables efficient and granular searches for specific patterns or events of interest across large numbers of endpoints.

5. **Forensic Data Collection**:
   - Velociraptor is capable of gathering forensic data, such as file integrity monitoring, process execution histories, file metadata, and user activity logs, which can be critical during post-incident investigations.
   - The tool provides a way to capture system snapshots, which can later be analyzed for evidence of compromise, malware, or malicious activities.

6. **Customizable Actions**:
   - It allows security teams to configure automated actions in response to specific queries. For example, Velociraptor can automatically run a script to stop a process, delete a suspicious file, or notify the security team if certain conditions are met.
   - This can significantly speed up the response time to threats and reduce the need for manual intervention.

7. **Lightweight and Low Overhead**:
   - Velociraptor is designed to have minimal impact on system performance, allowing it to operate efficiently on endpoints without consuming significant resources, which is crucial in environments where performance is a concern.
   - It is particularly useful for environments that need continuous monitoring without causing noticeable slowdowns.

8. **Centralized Management**:
   - While the tool operates on individual endpoints, Velociraptor provides a centralized interface for managing and monitoring the entire deployment. Administrators can issue queries and view results across all monitored systems from a single dashboard.
   - It also offers integration with other security tools and SIEM systems, making it part of a broader security ecosystem for detection and response.

9. **Flexible Query Language**:
   - Velociraptor uses a custom query language that allows security professionals to write highly customized queries for gathering system data. The language is designed to be intuitive, enabling users to search for specific behaviors or indicators of compromise.
   - Queries can be saved and reused, making it easy to standardize searches and automate recurring tasks.

10. **Scalability**:
   - Velociraptor is scalable, able to manage a large number of endpoints across different environments. Its distributed architecture ensures that it can handle extensive deployments, from small offices to large enterprises.
   - It is also highly configurable, meaning it can be adapted for specific security needs or use cases, such as monitoring network servers, workstations, or mobile devices.

### Use Cases:
- **Malware Detection**: Detects anomalies in endpoint behaviors that may indicate the presence of malware or ransomware.
- **Post-Incident Forensics**: Collects and analyzes data from compromised systems to understand the extent of a breach and gather evidence for investigations.
- **Threat Hunting**: Active searching for signs of compromise across an enterprise network using custom queries tailored to specific threat models.
- **Compliance Monitoring**: Helps ensure that endpoint systems are configured and operating in compliance with security policies and regulatory requirements.
- **System Health Monitoring**: Tracks system changes, configurations, and user activity, identifying any deviations that could signal a security risk.

### Deployment and Integration:
Velociraptor can be deployed across a variety of environments, from small offices to large enterprise networks. It integrates well with existing SIEMs and other cybersecurity tools, enabling it to augment your existing security monitoring and incident response workflows. It also provides a web interface for easy management and query execution, allowing teams to quickly identify and respond to emerging threats.

Overall, Velociraptor is a versatile and lightweight tool that provides critical endpoint monitoring and forensic capabilities, making it invaluable for proactive security monitoring, threat detection, and incident response efforts in modern cybersecurity operations.


Credentials: 
Ubuntu
password

./velociraptor-v0.6.0-1-linux-amd64 --config /etc/velociraptor.config.yaml frontend -v

Utilising a browser, enter the local host IP address and utilise port 8889.

Look at the documentation for adding new clients.

