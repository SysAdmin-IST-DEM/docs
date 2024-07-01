<div style="display: flex; justify-content: space-between; align-items: center;">
    <h1 style="font-size: 34px;">ICALCS</h1>
    <p align="right">
        <img src="../../assets/dem_logo.png" alt="logo" width="200" height="75">
    </p>
</div>

ICALCS are the computers which DEM offers to students and professors. These computers have the licensing for software that might not run smoothly on personal computers and have licensing for software not available to everyone. Professors and students connect to these computers via **Remote Desktop** with their User account.

**Rule of thumb:** No one is allowed to store their files inside these computers. All users have a separate folder for their files on a mapped drive in the network.

Here is a look at the current state at each ICALC and their respective software installed.

|                              | ICALC0        | ICALC1        | ICALC2        | ICALC3        | ICALC4        | ICALC5        | ICALC6        | ICALC7        | ICALC8        | ICALC9        |
| ---------------------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| IP Address                   | 10.16.233.230 | 10.16.233.228 | 10.16.233.227 | 10.16.233.229 | 10.16.233.231 | 10.16.233.232 | 10.16.233.236 | 10.16.233.237 | 10.16.233.243 | 10.16.233.244 |
| Solidworks                   | 2023          | 2023          | 2023          |               |               |               | 2023          | 2023          | 2023          | 2023          |
| NX                           | 1957          | 1957          | 1957          | 1957          | 1957          | 2212          | 2212          | 2212          | 2212          | 2212          |
| Abaqus                       | 2019          | 2019          | 2019          |               |               |               | 2021          | 2021          |               |               |
| Intel oneAPI                 |               |               |               |               |               |               | 2021          | 2021          |               |               |
| Star-CCM+                    |               |               |               |               |               |               | 2306          | 2306          | 2306          | 2306          |
| Ansys                        |               |               |               |               |               |               |               |               |               |               |
| Altium (Private License)     |               | TSB           | TSB           |               |               |               |               |               |               |               |
| Fidelity (Private License)   |               | 2022.1 (TSB)  | 2022.1 (TSB)  |               |               |               |               |               |               |               |
| Finemarine (Private License) |               | 2022.1 (TSB)  | 2022.1 (TSB)  |               |               |               |               |               |               |               |
| Simcenter Nastran            |               |               |               |               |               |               | 2020.1-1915   | 2020.1-1916   |               |               |
| Matlab Oficial               |               |               |               |               |               | r2024a        | r2024a        | r2024a        | r2024a        | r2024a        |
| Altair                       |               |               |               | Aerotec       |               |               |               |               |               |               |

### Adding a new ICALC

Adding a new ICALC is not an easy task but fortunaly is also not a common one made by the professor.

Here a list of things you might need to do if you need to install a new ICALC:

<ul>
    <li>For preparation you can check for space in the Polo1 room also talked about in this docs.</li>
    <li>You'll need to ask for a static IP address so people can connect via Remote Desktop to the computer. You can do so by sending an email to DSI (their general email) and ask for one assigned to that machine.</li>
    <li>Once you have the computer, start with installing the Windows 11 since it might not come with it pre installed and come with a later version of it- </li>
    <li>Install all the appropriate software meant for that computer.</li>
</ul>

## Common Requests

##### Request: Studing Association asks to add a computer to the Authorized list.

##### Solution:

Student Associations have acess to some ICALC's with software which they might need to run their simulations. This acess can only made from authorized IP's. These can be added...

##### Request: Add new User to the domain so it can be used in the ICALC.

##### Solution:

Users in the ICALC have their accounts in our domain, if a new masters/doctorate student asks for acess to ICALC's (usually sent by a professor), we need to create a new ICALC account using their email, and a random password to be changed on the first login. More about how to do this can be found on the [Active Directory](../active_directory/README.md) aba.

##### Request: Install / Update new Software.

##### Solution:

Most often than most of the other requests, people who use the ICALC's (either a student association or an individual), might ask you to update software or install new software. This is also trivial you can just search for the update and install it.

**!!HOWEVER Careful when installing software not all software should be installed in the ICALC's there should be a talk either with your collegue or with the Professor to check if it makes sense to add the software in question to the ICALC's!!**
