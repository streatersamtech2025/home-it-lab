# Troubleshooting Lab

## Overview

This lab demonstrates common troubleshooting techniques performed within a Windows 11 virtual machine running on macOS using UTM.

## Environment

- Host OS: macOS
- Guest OS: Windows 11 Home
- Virtualization Platform: UTM

## Scenario 1: IP Configuration Verification

### Objective

Verify that the system received a valid IP configuration.

### Tool Used

- Command Prompt
- ipconfig

### Result

The system successfully displayed network configuration information including IPv4 address, subnet mask, and default gateway.

### Screenshot

16-ipconfig-results.png

---

## Scenario 2: Internet Connectivity Test

### Objective

Verify internet connectivity using ICMP requests.

### Tool Used

- ping

### Command

```cmd
ping google.com
```

### Result

The system successfully communicated with an external host and received replies.

### Screenshot

17-ping-google-success.png

---

## Scenario 3: Connectivity Failure Test

### Objective

Simulate and identify a connectivity failure.

### Tool Used

- ping

### Command

```cmd
ping fakewebsite12345.com
```

### Result

The request failed because the hostname could not be resolved.

### Screenshot

18-ping-failure.png

---

## Scenario 4: DNS Troubleshooting

### Objective

Verify DNS functionality.

### Tool Used

- nslookup

### Command

```cmd
nslookup google.com
```

### Result

DNS successfully resolved Google's hostname and returned IP addresses.

### Screenshot

19-nslookup-google-results.png

---

## Scenario 5: Resource Usage Investigation

### Objective

Monitor system performance while multiple applications were running.

### Applications Open

- Google Chrome
- Mozilla Firefox
- VLC Media Player

### Tool Used

- Task Manager

### Metrics Reviewed

- CPU Usage
- Memory Usage
- Disk Activity

### Result

Applications operated normally and system resources remained stable.

### Screenshot

20-task-manager-resource-usage.png

---

## Skills Demonstrated

- Network Troubleshooting
- DNS Verification
- Connectivity Testing
- Windows Administration
- System Monitoring
- Technical Documentation

## Conclusion

Successfully performed multiple troubleshooting procedures including IP verification, connectivity testing, DNS resolution testing, and system performance analysis using standard Windows administrative tools.