## Independent Health 
### Interoperability API Developer Portal

**The Independent Health Interoperability API Developer Portal provides third-party app developers with access to documentation, registration services, Developer Sandbox services, and other developer services related to application programming interfaces (“APIs”) provided by Independent Health or one of its subsidiaries.**

If you are a DEVELOPER and would like to connect your application to our Interoperability API we’re here to support you each step of the way. 
The Developer Sandbox will allow 3rd Party Application Developers to test their application’s connection to the APIs.
Our 3rd Party Developer forum will allow you to search through discussions and review previously asked questions.

When you are ready you can submit a request for access to the Sandbox version of the Interoperability API using this form: [Request Sandbox API Access](https://github.com/Craig-Kaputa/Craig-Kaputa.github.io/issues/new?assignees=&labels=&template=sandbox-api-key-request.md&title=Request+for+Sandbox+API+Access)

As you work through connecting your application to our CMS Patient Access/ FHIR v7 Compliance API, you can submit support requests using this form: [Support Request](https://github.com/Craig-Kaputa/Craig-Kaputa.github.io/issues/new?assignees=&labels=&template=support-requests.md&title=)

Once the sandbox connection has been established and tested and you are ready to proceed you can submit a Production API Key request using this form: [Request Production API Key](https://github.com/Craig-Kaputa/Craig-Kaputa.github.io/issues/new?assignees=&labels=&template=production-api-key-request.md&title=Request+for+Production+API+Access)

**As you complete the forms above, be sure to:**
* Inculde all fields.
* Pay special attention to the URLs and links within your requests.

**We will:**
* Review and respond to your request in a timely manner.
* If your request is approved, we will email you a Client ID and Secret. It is important that you save the client ID and secret in a secure manner.

[Home Page](https://craig-kaputa.github.io/) 
| [Support Request](https://github.com/Craig-Kaputa/Craig-Kaputa.github.io/issues/new?assignees=&labels=&template=support-requests.md&title=)
| [Discussion Forum](https://github.com/Craig-Kaputa/Craig-Kaputa.github.io/discussions)

**SWAGGER ENDPOINTS**

No | API        | Description | More Details
------------ | -------------| -------------| -------------
1 | /v1/patientaccess/Patient/{id} 1.0.0 production | The Patient Access API is an enterprise API that implements the HL7 FHIR standard and provides the ability for members to access their data using Third-party client applications supporting those standards. The Patient Access API implements the FHIR Patient resource conforming to the CARIN Patient Profile specified in the CAIRN Blue Button Implementation Guide (v0.1.0). The Patient Access API follows the User token security model. The Patient resource supports the following operations: 1. Read the current state of the resource using the Logical (unique) ID [FHIR Base]/Patient/{id} | [More Info](https://github.com/Craig-Kaputa/Craig-Kaputa.github.io/discussions)
2 | /v1/patientaccess/Coverage 1.0.0 production | The API supports the FHIR Coverage resource and conforms to the CARIN Coverage Profile specified in the CARIN Blue Button Implementation Guide (v0.1.0). This API currently follows User token security. The Coverage resource supports: 1. Launch Coverage by calling the [FHIR Base]/Coverage without any identifier which will request the coverage resource for the Authenticated user 2. Coverage Search by Member ID 3. Coverage search by Membership ID | [More Info](https://github.com/Craig-Kaputa/Craig-Kaputa.github.io/discussions)

