---
title: Java issues for Niagara
date: 2017-01-26 20:56:55
tags: Java Niagara

---
### Step 1 Download Java 7 update 21
- download and install java 7
- Step 2 Download unlimited strength policy

### Install the unlimited strength policy

-Download the files and instructions for UnlimitedJCEPolicyJDK7 as above
-Locate the jre\lib\security directory for the Java instance. For example, this location might be: C:\Program Files\Java\jre7\lib\security.
-Remove the following .jar files from this directory: local_policy.jar and US_export_policy.jar.
-Replace these two files with the .jar files included in the JCE Unlimited Strength Jurisdiction Policy Files download.

Optional step 1 Disable Java 7 updates
Disable java update service on Windows Vista or Windows 7


## Also clear temporary files
By defult the files are hidden. To find you need to unhide the files
