# network-monitoring-AI-bot

Final project for the Building AI course

## Summary

AI tool to help monitor &amp; troubleshoot various network domains and topologies.

## Background

The problem is that network engineers get same question on weekly basis that what could be the problem when connection is not working. The situation might be different in network operation centers where they have state-of-the-art network monitoring tools & solutions. But in many smaller companies or teams the only way to troubleshoot the issue is to check current network element configurations and routing status from the routers or switches by network engineer. So the information that is needed to solve the issue is availabe but can't be accessed by normal users. Due that network elements account policies (restricted access for network engineers).

If all this effort that is spent by network engineer (to get data from network and investigate problem) could be handled by machine learning AI - tool, it would eventually leave time for more important issues like network planning, optimatization and willl lead to better network performance. On top of that the problems are almost are identical so it will make the network engineer daily work tasks more interresting which is my personal motivation to use AI solution.

## How is it used?

It would be machine learning based solution because the source data is 100% accurate, since it represent the actual state of the network. The AI tool should provide the corrective solution eg. replace fiber cable if that is broken, configuration change if the issue is there and if it can't solve the issue it should instruct the user to provide more detailed information. The AI tool is planned to run in private network to match the surrounding environment (company, datacenter) security requirements. 

Later phahes the tool could be able to predict for example soon to be breaking connections, if it has learned pattern from logs or statistics when connection has broken. Other import future task would be providing input to the network planning and solutions how to improve network resilience and performance.

## Data sources and AI methods

Data sources are network element configuration, network element status information and IP address management data base. It should be collected periodically from devices to AI which the can always provide latest and current information. It will be collected by network engineers (scripts) and stored locally to internal server.

## Challenges

It doesn't try to solve whole network monitoring area but will be addition to current solutions. I would say that AI tool is extra team member which could help actual network engineers. Challenge is also that the data is constantly changing and how to handle that specially for machine learning purposes.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
At the first phase I'd need understanding how to map existing data to such format that AI solution can read it. After this is done the AI logic should be build and in this phase not sure how this is done. Some neural network, SLM (small language model) with own prorieraty data injected to it or something else  

## Acknowledgments

*  Still waiting
