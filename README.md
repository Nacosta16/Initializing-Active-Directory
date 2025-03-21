# Initializing-Active-Directory

  <H2>Active Directory is a directory service that helps organizations manage users, computers, and resources in a network. It provides authentication, authorization, and centralized management for enterprise environments </H2>

  - <b> Install </b>
    
     - Open windows server 2022 in virtual box
     - Open server manager
     - Select add roles and features on the dashboard
     
     <img src="https://sigmawire.net/i/03/r6fMjA.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
     
     - Click next and select rolebased
     
     <img src="https://sigmawire.net/i/03/zRxGT1.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
     
     - Select your windows server, hit next (notice the IP is the one we set up during the windows server install link before this one)
     
     <img src="https://sigmawire.net/i/03/xYRUK7.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
     
     - Select active directory with domain services, add features, next

    <img src="https://sigmawire.net/i/03/zN7WZB.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>

    - Make sure group policy is selected, click next until you see

     <img src="https://sigmawire.net/i/03/qcPR5S.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
 
    - Install but do not close the dialog box just yet

     <img src="https://sigmawire.net/i/03/FzivE8.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>

  - <b> Promote the server to domain control </b>
     
     - Select "promote the server to domain control" in the dialog box

    <img src="https://sigmawire.net/i/03/InqGNH.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>  
     
     - Select add new forest, name it whatever you'd like, click next and add a password, click next again

     <img src="https://sigmawire.net/i/03/ifpmMz.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>

     - Click next past DNS options because you are not creating DNS delegation, leave the rest of the options default, do the prerequisite check, then install

     <img src="https://sigmawire.net/i/03/SDE1ov.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
 
     - Restart the VM to complete set up
       
     - Verify active directory by selecting tools on the server manager dashboard, and check to see if active directory options are there
   
        <img src="https://sigmawire.net/i/03/5m6ybg.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
