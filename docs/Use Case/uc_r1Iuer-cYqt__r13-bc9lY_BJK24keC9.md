

# UC_02 (Detailed)

### Name

Setup

### Package Name

Detailed

### Description

The Census Form can contain a list of up to 10 people residing in the dwelling on Census night. Setup is used to capture the number of persons present on Census night to configure the person section.

### List of Actor Names


    
- A_Respondent
    



### Pre-Conditions

1. Respondent logged into System.
2. Respondent's session is current (not timed out).
3. Application available.

### Basic Flow

1. Respondent updates the number of persons present on setup form.<br>2. System verifies number of persons present.<br>3. System configures the person section to support the number of persons present.

### Alternate Flows

<div>Alternative Path 1: Number of persons present not updated.</div><div><br></div><div>a. At step 1: Respondent does not provide the number of persons present (i.e. leaves field blank) and attempts to continue.<br>b. At step 2: System provides Respondent with error message: 1010. Refer to Section 5 for wording.<br>c. End use case.</div><div><br></div><div>Alternative Path 2: Respondent enters 0 for persons present.</div><div><br></div><div>a. At step 1: Respondent enters '0' as the number of Persons Present.<br>b. At step 2: System informs Respondent that they have indicated no one is present in the household and they are not required to complete the Census Form, message code: 1080. Refer to Section 5 for wording.<br>c. End use case.</div><div><br></div><div>Alternative Path 3: Respondent enters more than 10 persons present.</div><div><br></div><div>a. At step 1: Respondent enters 'number greater than 10 as the number of Persons Present.<br>b. At step 2: System advises Respondent 'that they will need to complete two Census forms, message code: 1037. Refer to Section 5 for wording.<br>c. Respondent chooses to continue<br>d. System created the maximum six person form<br>e. End use case.<br></div>

### Successful Outcomes

The Respondent sets up the number of person sections.

### Failure Outcomes

System provides respondent with an informative message telling them what else needs to be done with regards to completing the form(s).



