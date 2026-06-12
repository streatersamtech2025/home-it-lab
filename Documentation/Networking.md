# Networking Lab

## Overview

This lab demonstrates basic network troubleshooting and connectivity testing using Windows 11 in a virtual machine environment running on macOS.

## Objective

Learn how to verify network connectivity, identify IP configuration information, and perform DNS lookups using common Windows networking tools.

## Environment

- Host OS: macOS
- Virtualization Software: UTM
- Guest OS: Windows 11 Home
- Computer Name: HELPDESK-LAB

## Commands Executed

### ipconfig

Used to display the IP configuration of the Windows system.

#### Purpose

- Verify network adapter configuration
- View assigned IP address
- View subnet mask
- View default gateway

#### Result

Successfully displayed network configuration information for the virtual machine.

### ping google.com

Used to test connectivity to an external website.

#### Purpose

- Verify internet connectivity
- Confirm DNS resolution is functioning
- Measure network response times

#### Result

Successfully received replies from the destination host, confirming internet connectivity.

### ping 8.8.8.8

Used to test connectivity directly to a public IP address.

#### Purpose

- Verify network connectivity independent of DNS
- Confirm access to external networks

#### Result

Successfully received replies from the destination IP address.

### nslookup google.com

Used to query DNS records for a website.

#### Purpose

- Verify DNS functionality
- Resolve domain names to IP addresses

#### Result

Successfully resolved the domain name and returned associated IP addresses.

## Skills Demonstrated

- Network Troubleshooting
- IP Address Identification
- DNS Testing
- Command Line Usage
- Connectivity Verification
- Technical Documentation

## Screenshots

The following screenshots were captured during this lab:

- IP Configuration Results
- Ping Google Results
- Ping 8.8.8.8 Results
- NSLookup Results

## Lessons Learned

Basic networking tools can quickly identify connectivity issues and help determine whether problems are related to network access, DNS resolution, or system configuration.

## Lab Results

Successfully verified network connectivity and DNS functionality using Windows networking commands.

### Commands Used

| Command | Purpose |
|----------|----------|
| ipconfig | View network configuration |
| ping google.com | Test internet connectivity |
| ping 8.8.8.8 | Test direct IP connectivity |
| nslookup google.com | Verify DNS resolution |

## Conclusion

This lab provided hands-on experience using common networking tools frequently used by help desk and IT support professionals to diagnose and resolve connectivity issues.