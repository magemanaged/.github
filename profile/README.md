<p align='center'>
  <a href='https://github.com/magemanaged'>
    <img src='https://user-images.githubusercontent.com/40064946/165388455-62700757-2e58-485f-9c35-14475e3a8d45.svg' width='90%'/>
  </a>
</p>

## ✨ Magemanaged

Magemanaged is a workplace employee and asset management platform available for organizations connected to Azure AD. The platform was developed to unify and streamline the execution of common workplace tasks across various Software as a Service (SaaS) products through the use of RESTful APIs. Utilizing the Microsoft Authentication Library (MSAL) all requests made are authenticated and authorized through the Microsoft identity platform with OAuth 2.0 access code grants. More granual access control within the organization is possible through the use of app roles configured within Azure.

## 🧙 Merlin
<p align='center'>
<a href='https://github.com/magemanaged/magemanaged-merlin-api'>
    <img src='https://user-images.githubusercontent.com/40064946/166190941-f273d5d2-d0c0-450f-9893-f326cf9a6e2f.svg' align='center' width='50%'/>
  </a>
  </p>
  
Merlin is the NodeJS RESTful API backend for the magemanaged platform. Merlin acts as the intermediary between the platform and other software services. This API service is connected to the same Azure AD instance as the Single Page Application (SPA) portion of the platform. Merlin provides the same level of authorization and authentication as the web application by integrating with Azure AD to validate all identity access tokens received and ensuring that the request is within the allowed scope for the user.

## ⛓️ Integrations
Magemanaged allows for integration with multiple SaaS products.
### Jira 
Utilizing your organization's Jira API key magemanaged can open, track and close issues automatically. 
  
