
## Diagram

![LOM Base - new](../img/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9.png)



### Name


LOM Base - new


### Description


This is a Logical Operational View of the ECS solution. Identified Actors, along with Logical Nodes, are placed onto the Logical Location View developed earlier. In addition, the identified Deployment Units are “deployed” onto Nodes in the model. The ECS solution is consistent with a generic web application hosting pattern.


## Element

[Expand all](#){ .md-button .diff-line }


### Actor


    

<details markdown=1>
<summary markdown="span">A_Electronic Census Processing</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>A_Electronic Census Processing</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td>IT System</td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
<td>
        
</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">A_Support Device</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>A_Support Device</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>PC or mobile device used by help desk support person.  They are using the system via a browser, so no software to be deployed.

The browser accessed user interface - must meet the accessibility requirements including operation with JavaScript disabled and support for screen readers. ECS application running on the server generates all HTML pages displayed to the respondent and performs all field validation, business rule and mandatory question checks, and subsequent processing. The browser performs the pure presentation layer function, and thus every individual page transition requires interaction with the server.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td>IT System</td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
<td>
        
</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">A_System Administrator</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>A_System Administrator</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>The System Administrator is responsible for support of the ECS system itself.  The System Administrator deploys new versions of the ECS system and may be involved in problem troubleshooting on request from the Census Help Desk.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td>Human</td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
<td>
        
                
                <div><strong>SubSystem,Access</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Access.</div>
                
                
</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">A_Census Help Desk Support</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>A_Census Help Desk Support</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Help desk provides visibility to end-user issues.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td>Human</td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
<td>
        
</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">A_Respondent</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>A_Respondent</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Census form respondent, might be using a PC, or a mobile device.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td>Human</td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
<td>
        
                
                <div><strong>SubSystem,Access</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Access.</div>
                
                
</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">A_Respondent PC</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>A_Respondent PC</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>PC used by census respondent, in this case using a browser to access the centralized version of the application.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td>IT System</td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
<td>
        
</td>
    </tr>
</table>


</details>


    




### Subsystem





### OMLocation


    

<details markdown=1>
<summary markdown="span">L_01 External Respondent</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>L_01 External Respondent</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>L_External Respondent

Cardinality = 10,000,000</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">L_02 DoS Data Centre</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>L_02 DoS Data Centre</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>L_External Client Data Centre

Cardinality = 1</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">L_03 External Client User</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>L_03 External Client User</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>L_External Client User

Cardinality = 1</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">L_04 Cloud Secure (DMZ)</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>L_04 Cloud Secure (DMZ)</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>L_Cloud Secure (DMZ)

Cardinality = 1</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">L_05 Cloud Data Centre Enterprise</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>L_05 Cloud Data Centre Enterprise</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>L_Cloud Data Centre Enterprise

Cardinality = 1</td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">L_06 External 3rd Party</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>L_06 External 3rd Party</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>L_External 3rd Party

Cardinality = 3</td>
    </tr>
</table>


</details>


    




### Logical Connection


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span"></summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    



### Logical Node


    

<details markdown=1>
<summary markdown="span">LN_API Gateway</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_API Gateway</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="https://www.ibm.com/cloud/api-connect">IBM API Connect</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_Gateway</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>TE_API Access</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_App Store</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_App Store</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="">ECS Solution</a></div>
            
                <div><a href="https://www.sqlite.org/index.html">SQLite</a></div>
            
                <div><a href="">Android</a></div>
            
                <div><a href="">IOS</a></div>
            
                <div><a href="">Windows</a></div>
            
                <div><a href="https://developers.google.com/maps/documentation/geolocation/overview">Google Maps API</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>L_06 External 3rd Party</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>I_01b MobileApp (IOS)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                
            
                <div>I_01a MobileApp (Android)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                
            
                <div>I_01c MobileApp (Windows)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Census Data Delivery</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Census Data Delivery</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_Messaging</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>E_17 SendRespondentData</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_20 ForwardProxy</div>
                
            
                <div>E_18 SendMgtInfo</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_19 PullECNs</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Census Form Handling</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Census Form Handling</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="https://httpd.apache.org/">Apache http Server</a></div>
            
                <div><a href="https://cloud.ibm.com/developer/appservice/create-app?starterKit=687d91f2-ba5c-3914-8da5-57876c1f772a&defaultLanguage=undefined">Java Liberty App</a></div>
            
                <div><a href="https://tomcat.apache.org/">Apache Tomcat</a></div>
            
                <div><a href="https://cloud.ibm.com/catalog/content/.::1-b9f20fe3-baac-459b-b047-cb4ae9eb46f2-global">WebSphere Application Server for VSI</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_App_Microservices</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>E_10 FormDefinitionController</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Services View/aodservices_2SjGFR5cKyw_r13-bc9lY_BJK24keC9">ECS Services</a></div></li>
                    
                
            
                <div>E_05 FormHandlingWebServer</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_07 ViewController</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_09 FormSubmission</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Services View/aodservices_2SjGFR5cKyw_r13-bc9lY_BJK24keC9">ECS Services</a></div></li>
                    
                
            
                <div>D_03 FormData</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Services View/aodservices_2SjGFR5cKyw_r13-bc9lY_BJK24keC9">ECS Services</a></div></li>
                    
                
            
                <div>TE_04 App Server</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_08 Validation</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Census Help Desk</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Census Help Desk</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="">ECS Solution</a></div>
            
                <div><a href="https://cloud.ibm.com/developer/appservice/create-app?starterKit=687d91f2-ba5c-3914-8da5-57876c1f772a&defaultLanguage=undefined">Java Liberty App</a></div>
            
                <div><a href="https://tomcat.apache.org/">Apache Tomcat</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_Census Help Desk</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>E_24 ConfigMgr</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_23 MgtInfoViewer</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>TE_App Server</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>U_03 RespondentViewer</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>U_05 ConfigMgrUI</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_22 RespondentViewer</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>U_04 MgtInfoViewer</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Census Information Management</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Census Information Management</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="">ECS Solution</a></div>
            
                <div><a href="https://cloud.ibm.com/developer/appservice/create-app?starterKit=687d91f2-ba5c-3914-8da5-57876c1f772a&defaultLanguage=undefined">Java Liberty App</a></div>
            
                <div><a href="https://tomcat.apache.org/">Apache Tomcat</a></div>
            
                <div><a href="https://cloud.ibm.com/catalog/content/.::1-b9f20fe3-baac-459b-b047-cb4ae9eb46f2-global">WebSphere Application Server for VSI</a></div>
            
                <div><a href="">MongoDB</a></div>
            
                <div><a href="https://cloud.ibm.com/catalog/services/db2">Db2</a></div>
            
                <div><a href="https://cloud.ibm.com/databases/databases-for-postgresql/create">Databases for PostgreSQL</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_Database Services</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>D_04 RespondentData</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_B19eGrZ5tqYO_r13-bc9lY_BJK24keC9">SD - UC_19 Transfer Management Information</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Services View/aodservices_2SjGFR5cKyw_r13-bc9lY_BJK24keC9">ECS Services</a></div></li>
                    
                
            
                <div>E_14 MfgInfoProcess</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>TE_RDBMS</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_13 Translation</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>TE_11 App Server</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Connectivity</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Connectivity</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="https://www.ibm.com/cloud/cloud-internet-services">IBM Cloud Internet Services</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>L_04 Cloud Secure (DMZ)</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>TE_Firewall</div>
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Device Replication Services</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Device Replication Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="">ECS Solution</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>E_12 Mobile Device Replication</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Services View/aodservices_2SjGFR5cKyw_r13-bc9lY_BJK24keC9">ECS Services</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Edge Services</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Edge Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Provide network capability to deliver content through the Internet (DNS, CDN, firewall, load balancer).</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
                <div>edge services</div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="https://www.ibm.com/cloud/cloud-internet-services">IBM Cloud Internet Services</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
                <div><a href="../../Non Functional Requirements/nfr_BJAcxrWqK5YO_r13-bc9lY_BJK24keC9">Overall response time</a></div>
            
                <div><a href="../../Non Functional Requirements/nfr_HJ55lSW9t9YO_r13-bc9lY_BJK24keC9">Capacity during census enumeration period.</a></div>
            
                <div><a href="../../Non Functional Requirements/nfr_Hkv5lBZ9tqtd_r13-bc9lY_BJK24keC9">Transaction Processing Time</a></div>
            
                <div><a href="../../Non Functional Requirements/nfr_Hy89lHbcY5tO_r13-bc9lY_BJK24keC9">Device Support</a></div>
            
                <div><a href="../../Non Functional Requirements/nfr_r1_qgSZct9Fd_r13-bc9lY_BJK24keC9">Availability</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_Edge Services</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_04 Cloud Secure (DMZ)</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
                <div>Overall response time</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                    <li><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></li>
                    
                
            
                <div>Capacity during census enumeration period.</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                    <li><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></li>
                    
                
            
                <div>Transaction Processing Time</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                    <li><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></li>
                    
                
            
                <div>Device Support</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                    <li><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></li>
                    
                
            
                <div>Availability</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                    <li><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></li>
                    
                
            
            
                <div>TE_Load Balancer</div>
                
            
                <div>TE_Secure Gateway</div>
                
            
                <div>TE_CDN</div>
                
            
                <div>TE_DNS</div>
                
            
                <div>TE_Firewall</div>
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Mobile Device</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Mobile Device</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Mobile device, running an application that must be available for Android, iOS and Windows devices. The functionality of the mobile device application will be like that offered by the Rich client browser application. Additionally, the solution will support “offline” mode of operation whereby census can be filled in by the mobile device user while the device is not connected to any network. The data is temporarily stored on the device and replicated back to the servers as soon as connection to a network is established. The data is removed from the mobile device once it is replicated to the server.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="">ECS Solution</a></div>
            
                <div><a href="https://www.sqlite.org/index.html">SQLite</a></div>
            
                <div><a href="">Android</a></div>
            
                <div><a href="">IOS</a></div>
            
                <div><a href="">Windows</a></div>
            
                <div><a href="https://developers.google.com/maps/documentation/geolocation/overview">Google Maps API</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>L_01 External Respondent</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>d_02 FormData</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>d_01 RespondentData</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_01a Mobile App (Android)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                
            
                <div>U_02c PhoneUI (Windows)</div>
                
            
                <div>E_02a DeviceLocalDB (Android)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_02b DeviceLocalDB (IOS)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>E_01b MobileApp (IOS)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                
            
                <div>U_02a PhoneUI (Android)</div>
                
            
                <div>U_01c MobileUI (Windows)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>U_01a MobileUI (Android)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>U_01b MobileUI (IOS)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
                <div>U_02b PhoneUI (IOS)</div>
                
            
                <div>E_01c MobileApp (WIndows)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                
            
                <div>E_02c DeviceLocalDB (Windows)</div>
                
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Privleged User Security Services</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Privleged User Security Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Authentication for privliedged users</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_IAM</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>E_06 Authentication</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Services View/aodservices_2SjGFR5cKyw_r13-bc9lY_BJK24keC9">ECS Services</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Respondent ID Services</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Respondent ID Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Responsible for validating CFN/ECN against master list and using this to identify session.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="">ECS Solution</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_App_Microservices</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>E_06a Respondent Identity</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Sequence View/cmdynamicview_rknuMrZcFqKO_r13-bc9lY_BJK24keC9">SD - UC_01 Logon</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                    <li><div><a href="../../Services View/aodservices_2SjGFR5cKyw_r13-bc9lY_BJK24keC9">ECS Services</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">LN_Transformation & Connectivity</summary>

<table>
    <caption></caption>
    <thead>
        <tr>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>LN_Transformation & Connectivity</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Transformation and Connectivity - enables and connects securely between modules running in the cloud and applications running in the DoS enterprise data centre.</td>
    </tr>
    <tr>
        <td> <strong>Type</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
            
                <div>messaging</div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
            
                <div><a href="https://camel.apache.org/">Apache Camel</a></div>
            
                <div><a href="https://www.ibm.com/support/knowledgecenter/en/SSTTDS_11.0.0/com.ibm.ace.home.doc/help_home.htm">IBM App Connect Enterprise</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Architectural Decision</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Non Functional Requirement</strong> </td>
        <td>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Sub-level Diagram</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
            
                <div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div>
            
                <div><a href="../../IT System View/aoditsystem_SJ5yHK9eF_r13-bc9lY_BJK24keC9">ECS Base</a></div>
            
                <div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div>
            
        </td>
    </tr>
    <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
            
                <div>PN_Edge Services</div>
                
                    
                    <li><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></li>
                    
                
            
                <div>L_05 Cloud Data Centre Enterprise</div>
                
                    
                    <li><a href="../../Logical Operational View/lomview_S18vZHZqK9FO_r13-bc9lY_BJK24keC9">LOM - Base</a></li>
                    
                    <li><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></li>
                    
                
            
            
                <div>E_16 Middleware</div>
                
                    
                    <li><div><a href="../../Prescribed Operational Model/pomview_ryoKWHbcF9Yd_r13-bc9lY_BJK24keC9">POM - Base</a></div></li>
                    
                    <li><div><a href="../../Logical Operational View/lomview_SJ4GogkCd_r13-bc9lY_BJK24keC9">LOM Base - new</a></div></li>
                    
                    <li><div><a href="../../Static View/cmstaticview_2VSZD2lD7RK_r13-bc9lY_BJK24keC9">ECS Static View</a></div></li>
                    
                
            
        </td>
    </tr>
</table>


</details>


    




