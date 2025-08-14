<h1>Active Directory Lab</h1>

<h2>Description</h2>
Lab focused on hands-on experience with Microsoft Active Directory. I performed key administrative tasks, including creating and deleting user accounts, moving users between Organizational Units (OUs), and creating a new OU for better organization. I also unlocked user accounts that were locked due to failed login attempts. The lab simulated real-world AD management tasks in a Windows Server environment.
<br />

<h2>Platforms Used </h2>

- <b>Server Academy</b>

<h2>Program walk-through:</h2>

<p align="center">
🛠 Step 1: Accessing Active Directory Users and Computers <br/>
<p align="left">
After logging into the Server Academy lab environment:
 1. Click the **Start Menu**.<br>
2. Open **Server Manager**.<br>
3. In the top right corner, click **Tools**.<br>
4. From the dropdown menu, select **Active Directory Users and Computers**.<br>

This opens the ADUC console, which is where all user, group, and OU management is performed.  

<br />
<br />
<p align="center">
👤 Step 2 – Creating New User Accounts  <br/>
<p align="left">
1.  In ADUC, navigate to the **domain name** listed in the left-hand panel. <br>
2. Right-click the **Organizational Unit (OU)** where the user should be created (e.g., *Domain Admin Users*). <br> 
3. Select **New → User**.  <br>
4. 📝 Enter:  <br>
   - First Name  <br>
   - Last Name  <br>
   - User Logon Name (e.g., `jane.doe@sdcsm.com`)  <br>
5. Set an **initial password**.  <br>
6. Check **User must change password at next logon**. <br> 
7. Click **Finish** to create the account.  <br>

<br />
<br />
🔄 Step 3 – Resetting Passwords: <br/>
<p align="left">
1. Locate the user in the correct OU. <br>
2. Right-click their name and select **Reset Password**. <br> 
3. Enter a new temporary password.  <br>
4. Check **User must change password at next logon**. <br>
5. Click **OK**. <br>
 
<br />
<br />
🔀 Step 4 – Moving Users Between OUs:  <br/>
<p align="left">
1. Select the user account in the left-hand panel. <br>
2. Drag the user into the new OU (e.g., from *Sales* to *IT*).  <br>
3. Click **Yes** to confirm the move. <br>


<br />
<br />
🚫 Step 5 – Disabling and Deleting Accounts:  <br/>
<p align="left">
 **To Disable:**  
1. Right-click the user account. <br>
2. Select **Disable Account** (a down arrow icon appears on the user icon). <br>
**To Delete:**  
1. Right-click the user account. <br>
2. Select **Delete**. <br>
3. Confirm the deletion. <br>

<br />
<br />
<h2>Key Takeaways:</h2>

 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
