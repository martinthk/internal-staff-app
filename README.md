# Internal Staff App
A full-stack iOS native application for internal staffs to streamline B2B procedures.

![Thumbnail](https://user-images.githubusercontent.com/73326875/185791121-594d8200-4d5a-4327-8198-96ac87e8df29.png)


<!-- TABLE OF CONTENTS -->
<details>
    <summary>Table of Contents</summary>
    <ol>
        <li>
            <a href="#key-features">Key Features</a>
            <ul>
                <li><a href="#build-with">Build with</a></li>
            </ul>
        </li>
        <li>
            <a href="#screenshots-recordings"> Screenshots/ Recordings </a>
            <ul>
                <li><a href="#home-tab"> Home Tab </a>
                    <ul>
                        <li><a href="#class-subview"> Class Subview </a></li>
                        <li><a href="#edit-class-view"> Edit Class View </a></li>
                    </ul>
                </li>
                <li><a href="#calender-tab"> Calender Tab </a></li>
                <li><a href="#add-class-form"> Add Class Form </a></li>
                <li><a href="#device-tab"> Device Tab </a>
                    <ul>
                        <li><a href="#device-subview"> Device Subview </a></li>
                        <li><a href="#edit-device-view"> Edit Device View </a></li>
                    </ul>
                </li>
                <li><a href="#account-tab"> Account Tab </a></li>
                <ul>
                    <li><a href="#edit-account-view"> Edit Account View </a></li>
                </ul>
                <li><a href="#side-menu"> Side Menu </a></li>
            </ul>
        </li>
    </ol>
</details>

## Key Features
- Summary view for upcoming events/ classes
    - Provide access to deatiled information of each event/ class
- Calendar integeration
    - Keep track of existing scheudles 
- Devices tracking (status, location, history)
   - Status [available, on hold, sold]: auto-update depending on history record
- Tier system
    - Base on auto-accumulating working hours

### Build with
| Tech used | Description |
|:----------------|:-------------|
| Swift | Front-end  |
| PHP | Back-end communication |
| phpMyAdmin | Database management  |
| Firebase | Cloud messaging  |
| APNs | Send push notification to deives  |

## Screenshots/ Recordings

### Home Tab
- Call user's phone number via clicking on their icons
<details>
  <summary> Activate overlay menu via gesture </summary>
  
  https://user-images.githubusercontent.com/73326875/185791806-828b29bb-b77c-4f3d-9cfe-ef9bc1eedd29.mp4
</details>

<details>
  <summary> Integration with Google Map (generate route to destination)</summary>

  https://user-images.githubusercontent.com/73326875/185796163-59cde8a4-73c3-4511-872f-bb756854ab20.mp4
</details>

![1_Home](https://user-images.githubusercontent.com/73326875/185791862-5c4bf6ab-1025-4d97-98dc-12bed957843e.png)

#### Class Subview
![1_Home_Class](https://user-images.githubusercontent.com/73326875/185791868-8e6f415b-9782-47a4-a26d-e93cfa5a69a8.png)

#### Edit Class View
<details>
  <summary> Staff selection & device selection base on availability (determined base on database records </summary>
  
  https://user-images.githubusercontent.com/73326875/185794158-f916bc64-6b93-48a2-97ab-978274bb971f.mp4
</details>

![1_Home_Class_Edit](https://user-images.githubusercontent.com/73326875/185792212-fec896ae-d4ca-4c60-ada7-35759c4f184d.png)

### Calender Tab

![2_Calendar](https://user-images.githubusercontent.com/73326875/185791937-c5db17db-39ae-4659-810a-09cd9f31095f.png)

### Add Class Form
<details>
  <summary> Complete steps to add a class </summary>

  https://user-images.githubusercontent.com/73326875/185796014-5d20b10f-1de0-4324-a50b-64e1560f9850.mp4
</details>

### Device Tab
<details>
  <summary> Navigation in device tab </summary>

  https://user-images.githubusercontent.com/73326875/185796403-c5164420-38ed-4e10-b08c-ade28dd998b7.mp4

</details>

![3_Device](https://user-images.githubusercontent.com/73326875/185791941-3d6af117-1508-4edb-87a8-f45cfc2c029e.png)

#### Device Subview
![3_Device_Subview](https://user-images.githubusercontent.com/73326875/185792006-566b8af5-cc0c-48ca-a5f0-9bf21de34684.png)

#### Edit Device View
![3_Device_Subview_Edit](https://user-images.githubusercontent.com/73326875/185792010-af821e19-5401-4621-80a1-72901cf1df95.png)


### Account Tab
- Tier based on auto-accumulating working hours

![4_Account](https://user-images.githubusercontent.com/73326875/185791966-ca46f8e8-1429-4be8-9925-16ac71cbc8cb.png)

#### Edit Account View
<details>
  <summary> Pick image from device's album </summary>

  https://user-images.githubusercontent.com/73326875/185794952-370d5059-867c-4bb4-953c-dba679daa28d.mp4

</details>

![4_Account_Edit](https://user-images.githubusercontent.com/73326875/185791973-89d93c35-f08e-411a-aaa7-5740ca14f96a.png)

### Side Menu
<details>
  <summary> Apply Shift (with pre-defined filter options) </summary>

  https://user-images.githubusercontent.com/73326875/185793823-eb72bafd-11ec-4a09-be57-9a4667f88c9e.mp4
  
</details>
<details>
  <summary> Job Application (auto draft eamil with template format) </summary>
  <img src="https://user-images.githubusercontent.com/73326875/185793887-5a8e94de-184b-45ac-8ca0-a9b8bc24879b.PNG" width="400">

</details>

![0_Side Menu](https://user-images.githubusercontent.com/73326875/185792254-b4fd8ab5-6d77-432b-b2b3-b611dd8212c1.png)


<details>
  <summary> Log in </summary>
  
  https://user-images.githubusercontent.com/73326875/185791501-776d91ea-ea6e-40ed-9ada-1e427e4beef1.mp4
</details>

<details>
  <summary> Sign-up </summary>
  <img src="https://user-images.githubusercontent.com/73326875/185791991-84b2793d-8a3f-4439-bf60-9cde6891ce85.png" width="400">
</details>

