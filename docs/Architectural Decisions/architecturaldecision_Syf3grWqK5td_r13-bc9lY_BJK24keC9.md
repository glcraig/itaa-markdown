

# AD-0005

### Name

Web application architecture

### Status

accepted

### Last Update

2019-10-10

### Subject Area



### Topic



### Issue or Problem Statement

How should the ECS client web application be implemented?

### Assumptions



### Motivation



### Notes



[Expand all](#){ .md-button .same-line }

### Alternatives


    

<details markdown=1>
<summary markdown="span">AJAX Web 2.0 style application</summary>

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
        <td>AJAX Web 2.0 style application</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Use of more interactive AJAX framework to load and update page data between page navigation.<br></td>
    </tr>
    <tr>
        <td> <strong>Best Applied</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Contraindications</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">Both HTML and AJAX</summary>

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
        <td>Both HTML and AJAX</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>Using a combination of both to provide greater interactivity for devices that can support it while supporting more limited devices/connections to still have full functionality.<br></td>
    </tr>
    <tr>
        <td> <strong>Best Applied</strong> </td>
        <td></td>
    </tr>
    <tr>
        <td> <strong>Contraindications</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    

<details markdown=1>
<summary markdown="span">HTML Client</summary>

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
        <td>HTML Client</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td>A pure HTML based client with all data loaded with page.<br></td>
    </tr>
    <tr>
        <td> <strong>Best Applied</strong> </td>
        <td><br></td>
    </tr>
    <tr>
        <td> <strong>Contraindications</strong> </td>
        <td></td>
    </tr>
</table>


</details>


    



### Decision



### Justification

<ul><li>Much more responsive application with all actions occurring locally<br>within the browser.</li><li>Substantial reduction in server end infrastructure</li><li>Ability to change question, help and message text without application<br>changes.</li><li>Use only the core AJAX mechanism, avoiding the GUI presentation<br>widget sets as these are more likely to have browser dependencies.</li><li>Substantial increase in application scalability.<br></li></ul>

### Implications

Additional UI development effort.

### Derived Requirements



### Related Decisions



