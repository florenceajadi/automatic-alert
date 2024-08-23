<h4>Automatic Alert</h4>
<p>detecting suspicious activities and potential threats. Creating these rules collected by Sentinel, looking for patterns. When a rule identifies a threat, it triggers an alert, allowing security teams to investigate and respond quickly.  </p>
<p>
  <img src="https://github.com/user-attachments/assets/54cc4e95-188d-4d05-b01f-cc10f7aeec88" height="80%" width="80%" />
</p>
<p>
Imported a file into Sentinel Analytics and focused on CUSTOM: Brute Force SUCCESS -Windows.  </p>

  <p>
  <img src="https://github.com/user-attachments/assets/6e19d441-9374-44a9-b00d-759c4429a8a5" height="80%" width="80%" />
    <p>1) identifying potential brute force attacks or suspicious activity by flagging IP addresses that have repeatedly failed to log in to a network in 1hr.2) Successful logons are used to monitor and identify successful
    network logons within the past hr. 3)Successful logon joins the results of successful and failed logon attempts to identify scenarios where both types of events (success and failure) occurred from the 
      same IP address on the same host within a specific logon type. </p>
  </p>
<p>
   <img src="https://github.com/user-attachments/assets/f6304d3d-432b-4c8a-a1a7-31c1d08708be" height="80%" width="80%" />
</p>
<p>As you can see the IP Address failed to login into the windows-vm over 20 times and had 1 successful login.</p>
 
