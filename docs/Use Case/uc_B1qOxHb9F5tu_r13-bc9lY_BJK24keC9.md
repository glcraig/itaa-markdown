

# UC_19 (Detailed)

### Name

Transfer Management Information

### Package Name

Detailed

### Description

The System transfers management information data to the DoS Electronic Census Processing System.

### List of Actor Names


    
- A_DoS Electronic Census Processing System
    



### Pre-Conditions

1. Application available.
2. DoS Electronic Census Processing system is accessible.

### Basic Flow

<div>Management records have a unique key including a date/time stamp, CFN and ECS. The DoS Electronic Census Processing system will discard duplicate records. For example, if DoS receives the records but the acknowledgement does not reach ECS. In this case ECS will re-send these records and the DoS Electronic Census Processing system will acknowledge but discard them as duplicates.<br></div><div><br></div><div>1. System will be triggered to transfer Management Information data daily.</div>2. System formats Management Information data.<br>3. System transfers data to the DoS Electronic Census Processing system.<br>4. DoS Electronic Census Processing system acknowledges receipt.<br>5. System marks management data as sent.

### Alternate Flows

<div>Alternative Path 1: Data transfer fails</div><div><br></div><div>a. At step 3: Data transfer fails.<br>b. System will attempt again at next trigger event.<br>c. End use case.</div><div><br></div><div>Alternative Path 2: DoS does not acknowledge</div><div><br></div><div>a. At step 4: DoS Electronic Census Processing system does not send acknowledgement.<br>b. System will attempt again at next trigger event.<br>c. End use case.<br></div><div><br></div>

### Successful Outcomes

The System successfully transfers management information data to DoS.

### Failure Outcomes

System will retry transer



