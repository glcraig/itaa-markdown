

# UC_08 (Detailed)

### Name

Provide Person Data

### Package Name

Detailed

### Description

The Respondent provides answers to the questions contained in the person section.

### List of Actor Names


    
- A_Respondent
    



### Pre-Conditions

1. Respondent logged into System.
2. Respondent's session is current (not timed out).
3. Application available.
4. Respondent has provided the number of persons present on setup (see Setup Use Case).

### Basic Flow

<div>Questions will need to be dynamically changed base on answers to previous questions. For example, if the answer to Q12: “Country of birth”, is Bolumbia then the next question Q13: “Years of arrival in Bolumbia”, should be changed to read: “Based on your response to question 12, you are not required to answer this question.”</div><div><br></div><div>Answers to questions should be dynamically populated based on answers. For example, if the respondent answers “the same as the previous address” the address is populated automatically from the previous data.</div><div><br></div><div>The list of questions can be found in Ref [1] Case Study Background.<br></div><div><br></div><div>1. System displays page with person questions.</div>2. Respondent answers questions.<br>3. Respondent requests next page.<br>4. System detects there are more pages to be displayed.<br>5. System displays the next page.<br>6. Use case continues from step 2.

### Alternate Flows

<div>Alternative Path 1: System detects last page</div><div><br></div><div>a. System detects this is the last page on step 4.<br>b. System prompts respondent to complete section.<br>c. Go to use case Complete Section.</div><div><br></div><div>Alternative Path 2: Respondent navigates to another section.</div><div><br></div><div>a. Respondent requests navigation to another section without completing the Person section.<br>b. System data will be captured with the user's session.<br>c. System navigates Respondent to requested section.<br>d. End use case.<br></div>

### Successful Outcomes

The Respondent enters all mandatory and optional person data.

### Failure Outcomes

System prompts user to complete and, in some cases, saves progress.



