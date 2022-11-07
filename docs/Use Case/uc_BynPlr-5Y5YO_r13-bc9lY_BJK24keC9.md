

# UC_01 (Detailed)

### Name

Respondent Logon

### Package Name



### Description

The Respondent logs onto the System using a Census Form Number (CFN) and Electronic Census Number (ECN) which constitute logon credentials.
Following successful logon, the Respondent is presented with the ECS Census Form.

### List of Actor Names


    
- A_Respondent
    



### Pre-Conditions

1. CFN & ECN held by respondent
2. Internet access available to respondent.
3. Within enumeration period.
4. Application available.

### Basic Flow

1. Respondent accesses welcome page containing information about ECS, minimum system requirements and accessibility.<br>2. Respondent requests logon to System.<br>3. System records session start time for management information.<br>4. System records type and version of Respondent operating system for management information.<br>5. System records type and version of Respondent browser for management information.<br>6. System provides logon input request.<br>7. Respondent enters CFN CWL.<br>8. Respondent enters CFN CWL check digit.<br>9. Respondent enters CFN RNO.<br>10. Respondent enters CFN RNO check digit.<br>11. Respondent enters ECN.<br>12. Respondent requests access to System.<br>13. System confirms that CFN is valid.<br>14. System confirms that ECN is valid.<br>15. System confirms that ECN is not currently locked due to in excess of 5 failed logon attempts and time delay.<br>16. System confirms that CFN has not been subject to a large quantity of CFN activity (10 logins).<br>17. System confirms that submission has not occurred for the ECN entered.<br>18. System confirms that the ECN entered is not bound to a CFN.<br>19. System records the binding of the entered CFN and ECN combination.<br>20. System requests encryption of the ECN with the DoS public key from the Security System.<br>21. System records successful logon for management information.<br>22. System records data status change for Respondent to "logged on but no data saved" for management information.<br>23. System provides the Respondent with the first section of the form.

### Alternate Flows

<div>Alternative Path 1: Respondent enters invalid CFN with a valid ECN.</div><div><br></div><div>a. At step 13: System determines that CFN is not valid.<br>b. At step 14: System determines that ECN is valid.<br>c. System initiates Respondent time delay lockout.<br>d. System provides Respondent with error message: code 920. Refer to Section 5 for wording.<br>e. System records generation of error message for management information.<br>f. System records failed logon attempt for management information.<br>g. Repeat step 6.</div><div><br></div><div>Alternative Path 2:  Respondent re-enters invalid CFN with a valid ECN.</div><div><br></div><div>a. Continue from Use Case 01, alternate path 1, Step g.<br>b. At step 13: System determines that CFN is not valid<br>c. System determines that re-entered CFN is the same as that originally entered, then it is likely the respondent has entered the CFN as it appears on their form<br>d. At step 14: System determines that ECN is valid<br>e. Continue at step 15.</div><div><br></div><div>Alternative Path 3:  Respondent enters invalid ECN with a valid CFN.</div><div><br></div><div>a. At step 13: System determines that CFN is valid.<br>b. At step 14: System determines that ECN is not valid.<br>c. System initiates Respondent time delay lockout.<br>d. System provides Respondent with error message: code 830. Refer to Section 5 for wording.<br>e. System records generation of error message for management information.<br>f. System records failed logon attempt for management information.<br>g. Repeat step 6.</div><div><br></div><div>Alternative Path 4:  Respondent enters invalid ECN and invalid CFN.</div><div><br></div><div>a. At step 13: System determines that CFN is not valid.<br>b. At step 14: System determines that ECN is not valid.<br>c. System initiates Respondent time delay lockout.<br>d. System provides Respondent with error message: code 450. Refer to Section 5 for wording.<br>e. System records generation of error message for management information.<br>f. System records failed logon attempt for management information.<br>g. Repeat step 6.</div><div><br></div><div>Alternative Path 5:  System determines respondent is temporarily locked out.</div><div><br></div><div>a. At step 15: System determines that ECN has is temporary locked due to in excess of 5 failed logon attempts.<br>b. System provides Respondent with error message: code 550. Refer to Section 5 for wording.<br>c. System records generation of error message for management information.<br>d. System records failed logon attempt for management information.<br>e. Repeat step 6.</div><div><br></div><div>Alternative Path 6:  System detects "large" quantity of CFN logon activity.</div><div><br></div><div>a. At step 16: System determines that logons with CFN provided has exceeded limit (10 logins).<br>b. System flags data associated with CFN as suspect.<br>c. System initiates CFN lockout.<br>d. System provides Respondent with error message: code 540. Refer to Section 5 for wording.<br>e. System records generation of error message for management information.<br>f. System records failed logon attempt for management information.<br>g. Repeat step 6.</div><div><br></div><div>Alternative Path 7:  System determines submission has occurred for ECN.</div><div><br></div><div>a. At step 17: System determines that submission has occurred for the ECN entered.<br>b. System provides Respondent with thank you page which also displays the receipt number.<br>c. System records failed logon attempt for management information.<br>d. Repeat step 6.</div><div><br></div><div>Alternative Path 8:  Respondent logs back in.</div><div><br></div><div>a. At step 18: System determines that the ECN entered is bound to a CFN.<br>b. System determines that the ECN is bound to the CFN entered.<br>c. System displays section and page where form was left off during previous session.</div><div>d. Use case ends.</div><div><br></div><div>Alternative Path 9:  ECN bound to another CFN.<br></div><div><br></div><div>a. At step 18: System determines that the ECN entered is bound to a CFN.<br>b. System determines that the ECN is bound to a CFN that differs to that entered.<br>c. System provides Respondent with error message: code 740. Refer to Section 5 for wording.<br>d. System records generation of error message for management information.<br>e. System records failed logon attempt for management information.<br>f. Repeat step 6.<br></div><div><br></div>

### Successful Outcomes

The Respondent is presented with the first section of the ECS Census Form.

### Failure Outcomes

Generally, user presented with an appropriate error message and the error is logged.



