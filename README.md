# MFA-registration-policy-via-Azure-AD-Identity-Protection
Configure an Azure MFA policy for your cloud-based users from within the Azure AD Identity Protection pane.


<h2>Description</h2>
<p>MFA can be enabled and enforced for your Microsoft 365 users via both the Microsoft 365 admin center and by using Conditional Access policies. It is also possible to configure an Azure MFA policy for your cloud-based users from within the Azure AD Identity Protection pane.</p>

<h3>Steps:</h3>
<p>1. Go to Azure AD Identity Protection ->Protect Section -> Multifactor authentication registration policy</p>
<p>2. Assignments -> Select Users (we can include & exclude both users & groups)</p>
<p>3. Controls -> Select Require Azure AD multifactor authentication registration</p>
<p>4. Make Enforce Policy is On -> and save.</p>


<h3>Screenshots:</h3>
<p align="center">
MFA registration policy: <br/>
<img src="1.png" height="50%" width="50%" />
<br />
<p align="center">
Assigning a policy to users:  <br/>
<img src="2.png" height="50%" width="50%" />
<br />
<p align="center">
Including or excluding users or groups:  <br/>
<img src="3.png" height="50%" width="50%" />
<br />
<p align="center">
Access controls:  <br/>
<img src="4.png" height="50%" width="50%" />
<br />
<p align="center">
Enforcing the policy:  <br/>
<img src="5.png" height="50%" width="50%" />
<br />
<p>The policy will be saved, and the affected users will be prompted to register for MFA the next time they sign in with their Microsoft 365 credentials.</p>
<p>They will be able to bypass MFA registration and continue to log in for a period of 14 days.</p>
<p>If you have Azure AD Premium P2 licenses available to you in your tenancy, it is highly recommended to deploy the MFA registration policy.</p>

<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
