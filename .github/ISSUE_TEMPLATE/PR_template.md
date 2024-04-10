---
name: "GMAGAO-X PR/PFR Report"
PR/PFR: ''
title: ''

---
<!-- Use this template to fill out a Problem Report or a Problem Failure Report -->
<!-- Once the issue is created, the creator should add a PR or PFR label -- See guidelines below. -->
<!-- The creator should assign one or more people to the PR/PFR -->
<!-- The creator should add labels, as discussed below -->
<!-- The creator should consider adding a milestone for resolution of the problem -->
<!-- Note that unless there is a safety concern, you generally want to avoid breaking configuration until root cause is determined or until you determine that you can do so without losing information.  -->

<!-- PR reporting should begin at the start of manufacturing/assembly of flight hardware or of GSE that directly interfaces with flight hardware -->
<!-- PFR reporting should begin at the start of verification/validation testing -->

<!-- Guidelines for whether an issue should be a PR or a PFR: -->

<!-- **Generate a PR:** -->
<!--   Operator Error; Database problem; Procedural problem; Inspection finding; Connector mismate; Process control test finding; Requires rework; Problem that can be solved on the spot; Software issues related to formatting errors, requirement changes, adaptive changes, enhancements, etc. -->

<!-- **Generate a PFR:** -->
<!--   Blown fuse; Over voltage or over current; Limit failure; Hardware stress; Hardware change; Software change; Requires repair;  Problem discovered in the functioning or operation of hardware or software; Problem affects interface between Instruments and Subsystems; Problem involves significant cost or schedule impact; Problem not covered by a PR or deviation --> 
<!-- If a discrepancy documented in a PR requires any type of troubleshooting, including investigation or repair, it should be elevated to a PFR -->

# **Full Description:**  
<!-- This section should be filled out when the PR/PFR is opened -->

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

<!-- List affected systems and subsystems here and add a label for the system -->

**Priority:**

<!-- Low, Moderate, High, Very High, Extreme Priority -->
<!-- If the priority is high or greater, the operator should add a label to the issue -->

<!-- THE TEMPLATE ENTRY GENERALLY ENDS HERE.  TROUBLESHOOTING AND RESOLUTION COMMENTS CAN BE ENTERED LATER -->

# **Troubleshooting:**
Be sure to document any investigations, inspections, analyses, testing, etc. that are performed to understand the discrepancy and its root cause.  Include relevant drawings, photo-documentation, oscilloscope traces, etc.

# **Resolution Info:**
Once the issue is resolved, discuss the following areas.  The discussion should scale with the significance of the problem.  Major PFRs should address all of the following.

## **Root Cause:**
What were the root cause and contributing factors?  How does the root cause explain the symptoms?
<!-- For instance, Design error, Modeling error, Workmanship, Random part failure, Procedure, Operator error, or other. -->

## **Resolution:**
How was the issue corrected?  For hardware issues, what is the disposition of the hardware?  (Use as-is / rework [to return to near new condition] / repair [to restore functionality but with drop in performance] / scrap).    What are the expected outcomes/improvements?  Are there any follow-ups/unresolved questions?

## **Recurrence Prevention:**
Do we expect this discrepancy to occur again or to manifest itself in other parts of the instrument/operations?  How can this problem be prevented in future?  Is a risk being opened to address possible recurrence?


