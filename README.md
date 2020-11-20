___

    Date: 20th of November 2020
    Author: Carlos Munoz
    Email: carlos_munozgarrido@mcafee.com

___
# McAfee Mvision Cloud

This notebook goes through different samples that demonstrate the use of the Mvision Cloud.

Currently the following samples are provided:

* **Use Case 1:** How to get all the tenants associated with current credentials.

* **Use Case 2:** Authenticate against the default Tenant, 
This code snippet shows how to get authenticated and creates two variables used on further use cases token value and tenant Id.

* **Use Case 3:**

* Using the previous authentication token, submit a CSP template document for CSPM inspection.
This code generates an unique URL related to the uploaded content, next code snippet shows how to get the result of the analysis using this unique URL

*  Get the results, in terms of policies violated, related to the previous template uploaded.

* **Use Case 4:** In this snippet I show how to, using the new and undocumented REST API schema, get the incidents generated, this snippet used the tenant ID and the token value from use case 2

* **Use Case 5:** In this snippet I show how to, using the old skyhigh REST API schema, get the audit log. In the comments of this use case I introduce how to do it using the new schema. 

