# Project Description and Architecture
These are supporting projects that are architectured. 


## Table of Contents

- [Store Management System](#SMS)
- [Customer Management System](#CMS)
- [AI Sales Management System](#AISMS)




## Store Management System

RESTful endpoints supporting store inventory management system. Written in Java and Springboot.

<table>
  <tr style="background-color: gray;">
    <th>Verb</th>
    <th>Endpoint</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/inventory/products</td>
    <td>Developer</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/inventory/bogo</td>
    <td>Designer</td>
  </tr>
<tr>
    <td>GET</td>
    <td>/inventory/bogos</td>
    <td>Designer</td>
  </tr>
<tr>
    <td>DELETE</td>
    <td>/inventory/bogos</td>
    <td>Designer</td>
  </tr>
</table>


![Architecture Diagram](images/development.png)

![Architecture Diagram](images/deployed.png)


## Customer Management System

RESTful endpoints supporting shopping cart management system. Written in C#.


## AI Sales Management System (future work)

AI driven solution to determine sale prices and BOGO prices of store inventory.

RESTful endpoints supporting when store inventory should go on sale due to calendar date.

Written in Python.
