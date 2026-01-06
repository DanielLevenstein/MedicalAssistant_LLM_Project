# Medical Assistant LLM Project Summary

## Problem Statement
The healthcare industry is evolving rapidly, presenting professionals with the challenge of managing vast medical data while striving for timely and accurate diagnoses. Quick access to reliable, up-to-date medical knowledge is critical for enhancing patient outcomes and supporting informed decision-making, particularly in emergency situations where time is of the essence.

Healthcare professionals often face information overload, making it difficult to sift through extensive research for accurate diagnoses and treatment plans. This challenge necessitates an efficient integration of systems that streamline access to medical knowledge and support quick decision-making. Ensuring that healthcare providers have constant access to trustworthy resources can significantly improve patient care and operational effectiveness.

## Common Questions Addressed
1. **Diagnostic Assistance**: What are the common symptoms and treatments for pulmonary embolism?
2. **Drug Information**: Can you provide the trade names of medications used for treating hypertension?
3. **Treatment Plans**: What are the first-line options and alternatives for managing rheumatoid arthritis?
4. **Specialty Knowledge**: What are the diagnostic steps for suspected endocrine disorders?
5. **Critical Care Protocols**: What is the protocol for managing sepsis in a critical care unit?

## Project Approach
The project involved answering a set of five medical questions using the TinyLlama model, both with and without prompt engineering. The results were compared to assess the model's performance in providing relevant medical information.

## Summary of Findings
The TinyLlama model struggled to consistently follow instructions provided in prompts. Attempts to control the reading level, direct responses to specific audiences, and format the output were largely unsuccessful. Character limits were often ignored.

However, the most notable success came when the symptoms of appendicitis were transformed into a list of warning signs. This transformation proved useful and demonstrates potential applicability for similar queries in the medical domain.

It is worth noting that larger models generally perform better in adhering to instructions, suggesting that the challenges encountered in this project may not be as pronounced with a more advanced model.