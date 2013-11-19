tTM1Input
===================

Function of tTM1Input
---------------------------


tTM1Input is a Talend Component for accessing IBM Cognos TM1 Data Cubes. It uses the MDX query language as used by IBM Cognos TM1 (slightly different to other MDX dialects). The relevant parameters are:

* Hostname
* Application
* Username
* Password
* MDX Query


Setting the schema
-------------------------

We suggest replacing the following characters:

* Empty space
* Brackets
* Minus - and baseline dot

by underline. We plan to integrate the „Guess Schema“ in future, as it is limitied to SQL queries at the moment.
If you run the Job, the component provides some hints; it reads the internal fieldnames ("MEMBER_UNIQUE_NAME", might be different to the field names the MDX query suggests) and propose Talend field names that will work.

	Fieldname [plan_time].[Dec-2003] as _plan_time___Dec_2003_ added.
	Fieldname [plan_time].[Feb-2003] as _plan_time___Feb_2003_ added.
	Fieldname [plan_time].[Mar-2003] as _plan_time___Mar_2003_ added.
	
Installation
-------------------

The jar file TM1JavaAPI.jar can be found in C:\Program Files\Cognos\TM1\bin\classes\TM1JavaAPI.jar and cannot be provided with this component due to legal issues. This component is tested with TM1 Version 9.5.2.

Contact
-------------

**iTransparent GmbH | Business Process Architects**

Bayreuther Straße. 31
90409 Nürnberg

Tel.: +49 911 9239630 - 4

Fax: +49 911 9239630 - 9

[www.iTransparent.de] [1]

[1]: http://www.iTransparent.de/ "www.iTransparent.de"