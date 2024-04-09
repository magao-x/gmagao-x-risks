---
name: GMAGAO-X PR/PFR Report
PR/PFR: ''
title: ''

---
<!-- Once the issue is created, the creator should add a PR or PFR label -->
<!-- The creator should assign one or more people to the PR/PFR -->
<!-- The creator should add labels, as discussed below -->
<!-- The creator should consider adding a milestone for resolution of the problem -->

<!-- Note that PR reporting should begin at the start of manufacturing/assembly of flight hardware or of GSE that directly interfaces with flight hardware -->
<!-- PFR reporting should begin at the start of verification/validation testing -->

<!-- Guidelines for whether an issue should be a PR or a PFR: -->
<!--   **Generate a PR**        **Generate a PFR** -->
<!--   -------------------      -------------------  -->
<!--   Operator Error           Blown fuse -->
<!--   Database problem         Over voltage or over current -->
<!--   Procedural problem       Limit failure -->
<!--   Inspection finding       Hardware stress -->
<!--   Connector mismate        Hardware change -->
<!--   Process control test finding    Software change -->
<!--   Requires rework          Requires repair -->
<!--   Problem that can be solved on the spot    Problem discovered in the functioning or operation of hardware or software -->
<!--   Software issues related to formatting errors, requirement changes, adaptive changes, enhancements, etc.     Problem affects interface between Instruments and Subsystems -->
<!--                            Problem involves significant cost or schedule impact -->
<!--                            Problem not covered by a PR or deviation -->

<!-- If a discrepancy documented in a PR requires any type of troubleshooting, including investigation or repair, it should be elevated to a PFR -->

# **Full Description:**  

**Problem Description:**
<!-- Enter text after the **. Provide the following information: -->
<!-- Problem description -->
<!-- Details of the incident -->
<!--    Date/Time of incident -->
<!--    Operators -->
<!--    Hardware involved -->
<!--    Test equipment involved -->
<!--    Instrument configuration -->
<!--    Relevant environmental conditions -->
<!--    Details of what happened/what was observed -->
<!-- Impact of issue -->

**Safety Assessment/Workarounds:**

<!-- Do we want to operate before this is fixed? -->
<!-- Is it safe to do so? -->
<!-- What are the workarounds that allow us to continue? -->

**Initial Thoughts on Possible Solutions:**    

**Affected Systems:**

<!-- Type in affected systems and subsystems here and add a label for the system -->

**Priority:**

<!-- Low, Moderate, High, Very High, Extreme Priority -->
<!-- If the priority is high or greater, the operator should add a label to the issue -->

# **Troubleshooting:**
Be sure to document any investigations, inspections, analyses, testing, etc. that are performed to understand the discrepancy and its root cause.  Include relevant drawings, photo-documentation, oscilloscope traces, etc.

# **Resolution Info:**
Once the issue is resolved, discuss the following areas.  The discussion should scale with the significance of the problem.  Major PFRs should address all of the following.

## **Root Cause:**
What were the root cause and contributing factors?  How does the root cause explain the symptoms?
<!-- For instance, Design error, Modeling error, Workmanship, Random part failure, Procedure, Operator error, or other. -->

## **Resolution:**
How was the issue corrected?  For hardware issues, what is the disposition of the hardware?  (Use as-is / rework (to return to near new condition) / repair (to restore functionality but with drop in performance) / scrap).    What are the expected outcomes/improvements?  Are there any follow-ups/unresolved questions?

## **Recurrence Prevention:**
Do we expect this discrepancy to occur again or to manifest itself in other parts of the instrument/operations?  How can this problem be prevented in future?  Is a risk being opened to address possible recurrence?


