---
review:
    - questions:
        question: >
            What do you use to specify which ports are open in the Virtual Machine?
        answers:
            - Network Security Group 
            - Azure Firewall
            - Microsoft Firewall
        correct_answer: 1                    
        explanation: >
            Network Security Group is the Azure resource you use to filter newtork traffic: https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview

    - questions:
        question: >
            Which command is used to build and start the .NET app from the command line?
        answers:
            - .net run
            - .net start
            - dotnet run
            - dotnet start

        correct_answer: 3
        explanation: >
            .NET CLI is the command-line tool you use to build and run applications. The tool is accessed by dotnet command. To run the application you use run subcommand. See here to learn more: https://learn.microsoft.com/en-us/dotnet/core/tools/



# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---