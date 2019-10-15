---
layout: page
title: Program
tags: [program, schedule]
date: 2019-09-25
comments: false
---

## A Glance

<div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:center; vertical-align: middle; padding:40px 0;">
<a href="/donate">DONATE</a>
</div>

<div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:center; vertical-align: middle; padding:40px 0; margin-top:30px">
<a href="/blog">VIEW THE BLOG</a>
</div>
    
## A Glance


<div class="container">
  <h2>Responsive Tables Using LI <small>Triggers on 767px</small></h2>
  <ul class="responsive-table">
    <li class="table-header">
      <div class="col col-1">Job Id</div>
      <div class="col col-2">Customer Name</div>
      <div class="col col-3">Amount Due</div>
      <div class="col col-4">Payment Status</div>
    </li>
    <li class="table-row">
      <div class="col col-1" data-label="Job Id">42235</div>
      <div class="col col-2" data-label="Customer Name">John Doe</div>
      <div class="col col-3" data-label="Amount">$350</div>
      <div class="col col-4" data-label="Payment Status">Pending</div>
    </li>
    <li class="table-row">
      <div class="col col-1" data-label="Job Id">42442</div>
      <div class="col col-2" data-label="Customer Name">Jennifer Smith</div>
      <div class="col col-3" data-label="Amount">$220</div>
      <div class="col col-4" data-label="Payment Status">Pending</div>
    </li>
    <li class="table-row">
      <div class="col col-1" data-label="Job Id">42257</div>
      <div class="col col-2" data-label="Customer Name">John Smith</div>
      <div class="col col-3" data-label="Amount">$341</div>
      <div class="col col-4" data-label="Payment Status">Pending</div>
    </li>
    <li class="table-row">
      <div class="col col-1" data-label="Job Id">42311</div>
      <div class="col col-2" data-label="Customer Name">John Carpenter</div>
      <div class="col col-3" data-label="Amount">$115</div>
      <div class="col col-4" data-label="Payment Status">Pending</div>
    </li>
  </ul>
</div>


### CSS


<div class="wrapper">
  
  <div class="table">
    
    <div class="row header">
      <div class="cell">
        Name
      </div>
      <div class="cell">
        Age
      </div>
      <div class="cell">
        Occupation
      </div>
      <div class="cell">
        Location
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Name">
        Luke Peters
      </div>
      <div class="cell" data-title="Age">
        25
      </div>
      <div class="cell" data-title="Occupation">
        Freelance Web Developer
      </div>
      <div class="cell" data-title="Location">
        Brookline, MA
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Name">
        Joseph Smith
      </div>
      <div class="cell" data-title="Age">
        27
      </div>
      <div class="cell" data-title="Occupation">
        Project Manager
      </div>
      <div class="cell" data-title="Location">
        Somerville, MA
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Name">
        Maxwell Johnson
      </div>
      <div class="cell" data-title="Age">
        26
      </div>
      <div class="cell" data-title="Occupation">
        UX Architect & Designer
      </div>
      <div class="cell" data-title="Location">
        Arlington, MA
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Name">
        Harry Harrison
      </div>
      <div class="cell" data-title="Age">
        25
      </div>
      <div class="cell" data-title="Occupation">
        Front-End Developer
      </div>
      <div class="cell" data-title="Location">
        Boston, MA
      </div>
    </div>
    
  </div>
  
  <div class="table">
    
    <div class="row header green">
      <div class="cell">
        Product
      </div>
      <div class="cell">
        Unit Price
      </div>
      <div class="cell">
        Quantity
      </div>
      <div class="cell">
        Date Sold
      </div>
      <div class="cell">
        Status
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Product">
        Solid oak work table
      </div>
      <div class="cell" data-title="Unit Price">
        $800
      </div>
      <div class="cell" data-title="Quantity">
        10
      </div>
      <div class="cell" data-title="Date Sold">
        03/15/2014
      </div>
      <div class="cell" data-title="Status">
        Waiting for Pickup
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Product">
        Leather iPhone wallet
      </div>
      <div class="cell" data-title="Unit Price">
        $45
      </div>
      <div class="cell" data-title="Quantity">
        120
      </div>
      <div class="cell" data-title="Date Sold">
        02/28/2014
      </div>
      <div class="cell" data-title="Status">
        In Transit
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Product">
        27" Apple Thunderbolt displays
      </div>
      <div class="cell" data-title="Unit Price">
        $1000
      </div>
      <div class="cell" data-title="Quantity">
        25
      </div>
      <div class="cell" data-title="Date Sold">
        02/10/2014
      </div>
      <div class="cell" data-title="Status">
        Delivered
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Product">
        Bose studio headphones
      </div>
      <div class="cell" data-title="Unit Price">
        $60
      </div>
      <div class="cell" data-title="Quantity">
        90
      </div>
      <div class="cell" data-title="Date Sold">
        01/14/2014
      </div>
      <div class="cell" data-title="Status">
        Delivered
      </div>
    </div>
    
  </div>
  
  <div class="table">
    
    <div class="row header blue">
      <div class="cell">
        Username
      </div>
      <div class="cell">
        Email
      </div>
      <div class="cell">
        Password
      </div>
      <div class="cell">
        Active
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Username">
        ninjalug
      </div>
      <div class="cell" data-title="Email">
        misterninja@hotmail.com
      </div>
      <div class="cell" data-title="Password">
        ************
      </div>
      <div class="cell" data-title="Active">
        Yes
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Username">
        jsmith41
      </div>
      <div class="cell" data-title="Email">
        joseph.smith@gmail.com
      </div>
      <div class="cell" data-title="Password">
        ************
      </div>
      <div class="cell" data-title="Active">
        No
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Username">
        1337hax0r15
      </div>
      <div class="cell" data-title="Email">
        hackerdude1000@aol.com
      </div>
      <div class="cell" data-title="Password">
        ************
      </div>
      <div class="cell" data-title="Active">
        Yes
      </div>
    </div>
    
    <div class="row">
      <div class="cell" data-title="Username">
        hairyharry19
      </div>
      <div class="cell" data-title="Email">
        harryharry@gmail.com
      </div>
      <div class="cell" data-title="Password">
        ************
      </div>
      <div class="cell" data-title="Active">
        Yes
      </div>
    </div>
    
  </div>
  
</div>

    
 
### Welcome Ceremony

```
* Prof. Abdelfatah Mohamed
* Prof. Amr ElTawil
* Prof. Sameh Nada
* Prof. Goto Satoshi
* Prof. Suzuki Masaaki
* Prof. Ahmed ElGohary
```


 <div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:left; vertical-align: left; padding:40px 0;">
 * Prof. Abdelfatah Mohamed
Prof. Amr ElTawil
Prof. Sameh Nada
Prof. Goto Satoshi
Prof. Suzuki Masaaki
Prof. Ahmed ElGohary
 </div>
 
 
### Plenary Seminars

```
* 11:30 – 12:30 Prof. Shigeki Sugano (Waseda)
* 12:30 –13:30 Prof. Mohamed Fanni (E-JUST, MTR)
* 13:30 – 14:30 Prof. Tomoyuki Miyashita (Waseda)
* 14:30 – 15:00 Eng. Ahmed Saad (Unilever)
* 15:00 – 15:30 Plenary from FIBH (E-JUST)
```

### Interative Forum


### Seminars

```
* 09:30 – 10:30 Interactive Forum: Professors (Q&A)
* 10:30 – 11:00 Seminar 1: Alumni or Student from MTR
* 11:00 – 11:30 Seminar 2: Student from Waseda
* 11:30 – 12:00 Seminar 2: Victor or Moondeep (TBD)
```


### Day 1 Oct. 28 (Mon)

* 09:30 – 11:00 : Welcome Ceremony
    * Prof. Abdelfatah Mohamed
    * Prof. Amr ElTawil
    * Prof. Sameh Nada
    * Prof. Goto Satoshi
    * Prof. Suzuki Masaaki
    * Prof. Ahmed ElGohary

* 11:30 – 16:00 : Plenary Seminars
* 16:00 – 18:00 : Banquet at E-JUST

### Day 2 Oct. 29 (Tue)

* 09:30 – 10:30 : Interactive Forum
* 10:30 – 12:00 : Invited Talks
* 12:00 – 13:30 : Lunch at E-JUST
* 14:00 – 16:00 : Seminars on Selected Topics of Mechatronics and Robotics

### Day 3 Oct. 30 (Wed)

* 09:30 – 12:00 : Laboratory-based Sessions
* 12:00 – 13:30 : Lunch at E-JUST
* 13:30 – 15:30 : PBL-based Sessions
* 15:30 – 16:00 : Closing Ceremony


## Speakers

#### Prof. Sugano Shigeki (Waseda University)

##### Title: TBD

Abstract
{: .notice}

#### Prof. Miyashita Tomoyuki (Waseda University)

##### Title: TBD

Abstract
{: .notice}

#### Prof. Mohamed Fanni (Egypt-Japan University of Science and Technology)

##### Title: TBD

Abstract
{: .notice}


#### Dr. Victor Parque (Waseda University)

##### Title: TBD

Abstract
{: .notice}


[Home](https://pemtr2019.github.io){: .btn}

