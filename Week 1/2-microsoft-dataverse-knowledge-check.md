
**1. The Microsoft Dataverse can store large amounts of data, but only authorized users can access it. How is this controlled?**

Specific code must be added in the Administration center to limit users.

**The Azure Active Directory is used for authentication**

Only users who have a share link can access the data

*Correct! The Dataverse uses the Azure Active Directory for authentication.*

 **2. Which of the following statements are true regarding a Complex table? Select all that apply.**
 
**You may need a license to use a Complex table**

*Correct! If the Complex table comes from Dynamics 365 or a third-party solution you may need additional licenses to use the table.*

**A complex table uses server-side logic.**

*Correct! Complex tables in a Dataverse will have come from Dynamics 365 or other third-party solutions which is why they contain server-side logic.*

Complex tables appear in every instance of the Dataverse.

**3. If a one-to-many relationship (also called a Parent/Child relationship) exists between two tables which of the following statements are true? Select all that apply.**

**The linked column in the One (Parent) table is known as the Key.**

*Correct! The linked column in the One (parent) table that contains the unique values is known as the Key.*

**The linked column in the Many (Child) table is known as the Foreign Key**

*Correct! The Foreign Key column in the child table can have the same entry repeated on multiple rows*

The link column in the table that is on the One (Parent) side of the relationship can have repeating entries.

**4. How many Microsoft Dataverse Databases can be provisioned within an Environment?**

Two

As many as you need.

**One**

*Correct! Each Environment allows you to provision one Microsoft Dataverse Database.*

**5. Which of the following statements are true in relation to Environments? Select all that apply.**

**An Environment is bound to a geographic location.**

*Correct! An Environment is bound to a geographic location. When you create a Microsoft Dataverse database, that database is created within datacenters in that specific geographic location.*

Only one Environment can be created in each tenant.

**An Environments resources can only be accessed by users within the tenant.**

*Correct! Each Environment is created under a Microsoft Azure Active Directory tenant and the Active directory limits access to users who are authorized in that tenant.*

**6. If you wanted to restrict which data connectors can be used with Microsoft Dataverse, which section in the Power Platform Admin Center would you need to go to?**

Data Integration

**Data Policies**

Environments

*Correct! This section allows you to set up policies which restrict which data connectors can be used with Microsoft Dataverse.*