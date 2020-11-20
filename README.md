___

    Date: 20th of November 2020
    Author: Carlos Munoz
    Email: carlos_munozgarrido@mcafee.com

___
# McAfee Mvision Cloud

This notebook goes through different samples that demonstrate the use of the Mvision Cloud REST API.

Currently the following samples are provided:

* **Use Case 1:** How to get all tenants associated with current credentials.

* **Use Case 2:** Authenticate against the default Tenant.

This code snippet shows how to get authenticated. It defines two variables used on further use cases (token value and tenant Id).

* **Use Case 3:** Submit a CSP template document for CSPM inspection

Using the previous authentication token, submit a CSP template document for CSPM inspection.
This code generates an unique URL related to the uploaded content, next code snippet shows how to get the results, in terms of policies violated, of the analysis done using this unique URL

* **Use Case 4:** Get the incidents generated

This snippet shows how to, using the new and undocumented REST API schema, get the incidents generated, this snippet uses the tenant ID and the token value from use case 2

* **Use Case 5:** Get the audit log

This snippet shows how to, using the old skyhigh REST API schema, get the audit log. In the comments some guidance about  how to use new schema is introduced.

