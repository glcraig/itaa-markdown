

# UC_12 (Detailed)

### Name

Submit Form

### Package Name

Detailed

### Description

The Respondent may submit their Census data only once to the DoS, after completing all sections.  After successful submission, the System issues the Respondent with a receipt number. Any subsequent access to the System will provide the Respondent with their receipt number. Respondent is prevented from making changes or resubmitting their Census form.

### List of Actor Names


    
- A_Respondent
    
- A_DoS Electronic Census Processing System
    



### Pre-Conditions

1. Respondent logged into System.
2. Respondent's session is current (not timed out).
3. Application available.

### Basic Flow

1. Respondent requests Census submission page.<br>2. System provides Census submission page prompting the Respondent to verify contents and confirm as true and correct.<br>3. Respondent provides confirmation that contents are true and correct.<br>4. Respondent requests submission of Census.<br>5. System records request to submit for management information.<br>6. System verifies that the Respondent has confirmed that the contents are true and correct.<br>7. System verifies that a person section has been completed for all persons present.<br>8. System verifies that Address section has been completed.<br>9. System verifies that the dwelling section has been completed.<br>10. System determines that all data has been previously saved.<br>11. System generates 12 digit unique random receipt number.<br>12. System records receipt number, CFN, ECN, submission timestamp, Respondent address and CFN completion status for collector notification information.<br>13. System sends submitted forms to DoS Electronic Census Processing system including the completion status for collector notification information.<br>14. DoS Electronic Census Processing system acknowledges receipt<br>15. System registers submission of Census data for this ECN.<br>16. System increments submission count for management information.<br>17. System determines that the submission process completed successfully.<br>18. System records data status change for Respondent to "submitted" for management information.<br>19. System provides respondent with thank you page which contains their receipt number.<br>20. System requests Respondent to provide ECS feedback.<br>21. Respondent provides ECS feedback, check box responses and comments.<br>22. Respondent directed to Information Page.

### Alternate Flows

<div>Alternative Path 1:  Respondent declines confirmation and proceeds with submission.</div><div><br></div><div>a. At step 3: Respondent declines confirmation that contents are true and correct.<br>b. Continue step 4.<br>c. At step 6: System determines that the confirmation of data being true and correct has not been provided.<br>d. System provides Respondent with Submit (Confirm) Page.<br>e. The Respondent selects "Yes" to confirm that submission is to proceed.<br>f. Continue step 7.</div><div><br></div><div>Alternative Path 2: Respondent declines confirmation and cancels submission.</div><div><br></div><div>a. At step 3: Respondent declines confirmation that contents are true and correct.<br>b. Continue step 4.<br>c. At step 6: System determines that the confirmation of data being true and correct has not been provided.<br>d. System provides Respondent with Submit (Confirm) Page.<br>e. The Respondent selects "Back" to confirm that submission is to be cancelled.<br>f. End use case.</div><div><br></div><div>Alternative Path 3: Person section incomplete.</div><div><br></div><div>a. At step 7: System determines that a person section does not have a status of complete.<br>b. System provides Respondent with error message: System provides Respondent with error message: code 1060. Refer to Section 5 for wording.<br>c. End use case.</div><div><br></div><div>Alternative Path 4: Address section incomplete.</div><div><br></div><div>a. At step 8: System determines that the Address section does not have a status of complete.<br>b. System provides Respondent with error message: System provides Respondent with error message: code 1060. Refer to Section 5 for wording.<br>c. End use case.</div><div><br></div><div>Alternative Path 5: Dwelling section incomplete.</div><div><br></div><div>a. At step 9: System determines that the dwelling section does not have a status of complete.<br>b. System provides Respondent with error message: System provides Respondent with error message: code 1060. Refer to Section 5 for wording.<br>c. End use case.</div><div><br></div><div>Alternative Path 6: Sending forms and completion status to DoS fails (e.g. DoS systems unavailable)</div><div><br></div><div>a. At step 13: System determines that the send process failed.<br>b. The System records the failure.<br>c. The System provides the Respondent with an error message System provides Respondent with error message: code 1046. Refer to Section 5 for wording.<br>d. The System provides the Respondent with the submission page.<br>e. End use case.</div><div><br></div><div>Alternative Path 7: DoS Electronic Census Processing system does not acknowledge receipt</div><div><br></div><div>a. At step 14: System does not get send acknowledgement from DoS.<br>b. The System records the failure.<br>c. The System provides the Respondent with an error message System provides Respondent with error message: code 1046. Refer to Section 5 for wording.<br>d. The System provides the Respondent with the submission page.<br>e. End use case.<br></div><div><br></div><div>Alternative Path 8: Respondent declines to provide feedback.</div><div><br></div><div>a. At step 21: The Respondent declines the offer to provide ECS feedback.<br>b. Continue to step 22.<br></div><div><br></div>

### Successful Outcomes

The Respondent's Census is stored. The Respondent's ECN is permanently locked. The Respondent is provided with a receipt number.

### Failure Outcomes

In some cases, user is presented with a message and they can respond and continue.  The user may need to resubmit the form if that fails.



