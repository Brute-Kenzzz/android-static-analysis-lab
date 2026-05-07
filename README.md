
# Android Static Analysis Lab

## Overview
This project demonstrates basic static analysis of an Android application in a controlled lab environment. The goal was to understand how application data is structured and how embedded values can be identified through code inspection.

## Objectives
- Analyze application structure using JADX
- Trace data representation within compiled code
- Identify embedded network-related values
- Understand how data is stored and interpreted

## Tools Used
- JADX (Android decompiler)
- Python (for data decoding experiments)

## Approach
1. Decompiled the APK using JADX
2. Navigated application classes and identified relevant components
3. Located byte array / encoded data structures
4. Interpreted numerical values into readable format
5. Identified embedded communication strings within data

## Key Findings
- Observed structured byte data representing encoded strings
- Identified embedded network endpoint within application data
- Understood how numeric arrays map to ASCII-readable values

## Learning Outcomes
- Improved understanding of Android app structure
- Learned basic static analysis workflow
- Gained experience interpreting low-level data representations
- Practiced documenting technical findings

## Disclaimer
This project is based on controlled lab analysis for educational purposes only.
No real-world systems were targeted.
