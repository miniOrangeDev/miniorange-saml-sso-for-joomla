## DOWANLOAD AND INSTALLATION STEPS OF JOOMLA SAML SP
- Download the zip file for the miniOrange Joomla SAML SSO plugin for Joomla.
- Unzip the folder and zip all the subfolders except language folder. Now zip the main folder.
- Login into your Joomla site’s Administrator console.
- From menu, click on System, then under Install section click on **Extensions**.
- And upload the zip file under **Upload Package File**.

## Joomla SAML Single Sign-On (SSO) – SAML SSO Login Authentication | Login to Joomla

Joomla Single Sign-On (SSO) is an authentication process in which a user can log in to multiple applications and/or websites by using only a single set of login credentials (such as username and password). This prevents the need for the user to log in separately to the different applications. Joomla Single-Sign-On addresses the challenge of maintaining the credentials for each application separately, streamlining the process of signing on without the need to re-enter the password. 

To know more about SSO [click here](https://docs.joomla.org/SSO)


### JOOMLA SINGLE SIGN-ON ( SSO ):- 


Joomla Single Sign-On (SSO) is an authentication procedure that allows a user to log in to various apps and/or websites using a single set of login credentials (such as username and password). This eliminates the need for the user to log in to each application individually.

[Joomla Single Sign-On Service Provider](https://docs.joomla.org/SAML_Service_Provider_SSO_(SP)) also enables you to manage login and achieve Single Sign On (SSO) with Azure AD, Azure B2C, ADFS, Keycloak, GSuite / Google Apps, Okta, Salesforce, Office 365, Shibboleth2, Shibboleth3, OneLogin, PingFederate, ClassLink, FusionAuth, Absorb LMS or any SAML compliant Identity Provider so that your users can login to Joomla Site by using Identity Provider’s (IDP) users credentials.


The miniOrange Joomla Single Sign on (SAML SSO) Plugin is a SAML 2.0 Service Provider that can be configured to establish trust between the Joomla site and a SAML 2.0 compliant Identity Provider in order to securely authenticate users to Joomla sites. This makes it feasible for your users to log in to the Joomla site in a safe and secure manner.


Joomla SAML Single Sign On ( SSO ) supports all kinds of SSO use cases such as Azure login into Joomla, Azure AD login into Joomla, Azure AD SSO(Azure AD Single Sign-On), Login with Azure AD, Login using Azure AD, Login with Office 365, Office 365 login, Office 365 Single Sign On SSO, Login using Office 365, Login with Azure B2C, Azure B2C login, Login with Azure AD B2C, Azure AD B2C login, ADFS login into Joomla, Login with ADFS, Okta login, OneLogin SSO, Salesforce login, Login using Salesforce, Google Apps login, Google Apps Single Sign On SSO, Login with Google Apps, Login using Google Apps, Login using G Suite, Gsuite login into Joomla, Keycloak login, Keycloak SSO, Auth0 login, Shibboleth login, Login with Shibboleth, Login using Shibboleth, Login with Ping, PingFederate login, PingFederate SSO, ClassLink SSO, FusionAuth SSO, Absorb LMS SSO etc allowing your users to securely login to the Joomla site.

### **Free Version Features:-**

-  **Login Using IDP Credentials**  –  SAML SP helps login to your Joomla site using SAML 2.0 compliant Identity Providers.
-  **Automatic User Registration** –  The user will auto-register after login if the user is not already registered with your site.
-  **Easy to setup**   –  You can easily configure our plugin with any IDP by simply uploading the IDP metadata file/URL with a single click.
-  **Basic Role Mapping**– Assign the default role to users on registration and login.
-  **Export Configuration**– Download the plugin configuration file to transfer your plugin configurations when you change your Joomla instance.
-  Update SP Entity ID and base URL
- Step by step setup guides/ [videos.](https://www.youtube.com/playlist?list=PL2vweZ-PcNpdkpUxUzUCo66tZsEHJJDRl)

###**License Version Features :-**

**All the Free version features.** 

-  Unlimited Authentication and User creation with multiple Identity Providers.
-  **Single Logout (SLO)**  – Support for SAML Single Logout (Make sure your IDP also supports SLO)
-  **Auto-redirect to IDP** – If you want to restrict your site to only logged in users. Selecting this option will redirect the users to your IDP if logged in session is not found.
-  **Auto-redirect to IDP for /administrator URL** – If you want to restrict backend your site to only logged in users using SSO. Selecting this option will redirect the users to your IDP if logged in session is not found.
-  **Backdoor login for Superuser/administrator**  – Checking this option creates a backdoor to login to your website using Joomla credentials in case you get locked out of your IDP.
-  **Disable auto-creation of users if the user does not exist**  – If you enable this feature new users won't be created, only existing users can log in using SSO.
- **Advanced Attribute Mapping**  - Use this feature to map your IDP attributes to your Joomla site attributes like Username, Email, First Name, Last Name, Group/Role, Display Name.
-  **Advanced Role Mapping** – Use this feature to assign Joomla roles to your users based on the group/role sent by your IDP.
-  **Force Authentication**  – Force Authentication allows users to redirect to IDP if the user is not logged in.
- **Multiple SAML IDPs Support** – We support the configuration of Multiple IDPs in the plugin to authenticate the different groups of users with different IDPs.
- **Backend and Frontend Login**  – If a user is Super User, the user will be logged into both the frontend and backend of the site. No need to sign in again in the admin panel (backend) for 
- **Integrated Windows Authentication** – Support for Integrated Windows Authentication (With ADFS)
- **Binding Type**  – Select HTTP-POST or HTTP-Redirect binding type to use for sending SAML Requests.
- **Generate Custom SP Certificate**  - You can upload or generate your own certificates.
- **Select a Signature algorithm**  - You can select any signing algorithm according to your requirement.
- **Auto-sync IDP Configuration from metadata** 
-  **Store Multiple IDP certificates** 
- **Custom admin Login URL** 
- **Anonymous user** - Joomla SAML Single Sign On (SSO) also enables Anonymous Connect (Guest User Login) for your Joomla site, allowing your users to login to the Joomla site using their IDP credentials without having to create new users.
-  **Customize plugin depending upon the requirement** 
If you want to see license version features of plugin you can prefer this [video](https://www.youtube.com/watch?v=6KBF2bwvmeI&list=PL2vweZ-PcNpdkpUxUzUCo66tZsEHJJDRl&index=5&t=4s&ab_channel=miniOrange) demonstration.  


### **JOOMLA SINGLE SIGN-ON ( SSO ) SUPPORTED ADD-ONS**

We have various add-ons to extend the functionality of SAML SSO plugin which can be easily integrated with your Joomla site.

-  **Page and Article Restriction** – Page and Article Restriction allows you to prevent unauthorized users from accessing certain pages or articles, as well as redirecting users to a specific page after SSO.

- **Integrate with Community Builder**  – It enables you to link the Community Builder profiles together. So that you can easily map the community builder's attributes with the IDPs attributes.

- **SSO Login Audit**   –  You can easily monitor your logged in users at one place.

-  **Role Based Redirection**   – This add-on allows you to redirect your users to specific pages/articles based on the roles/groups of the users in Joomla site.

-  **Cross Domain Login between Joomla Sites**  – You may share the login across two Joomla websites (cross-domain, same domain, or sub-domain) by simply entering the other Joomla site URL in the plugin configuration settings. By including the HTML button on the current Joomla site, the user will be able to log in to the other Joomla domain. Please ensure that this plugin has been installed and activated on both Joomla sites. In order to access this function, users must be present on both sites.
 
### [JOOMLA SINGLE SIGN-ON ( SSO ) USE-CASES](https://plugins.miniorange.com/joomla-saml-sso-solutions):

**[Azure AD SAML SSO](https://plugins.miniorange.com/joomla-single-sign-sso-using-azure-ad-idp)**

Azure SSO use cases supported by the Joomla SAML Single Sign On (SSO) plugin include Azure AD SSO (Azure AD Single Sign-On), Azure B2C SSO, Azure B2C login, Login with Azure AD, Login using Azure AD, Office 365 SSO (Office 365 Single Sign On SSO), Login with Office 365, Office 365 Login, Login with Azure B2C, Login with Azure AD B2C login.
You may allow users from several Azure or Office 365 tenants to login to your Joomla site.

You may watch [this](https://www.youtube.com/watch?v=XOoitfFdSeM&list=PL2vweZ-PcNpdkpUxUzUCo66tZsEHJJDRl&index=1&ab_channel=miniOrange) video to learn how to set up Azure AD SSO with Joomla.
 
We provide support for SSO with Azure AD Multi-tenants, Azure AD B2B Login as well as Azure AD B2C login.

The Joomla SAML Single Sign On SSO plugin enables users from any Azure AD tenancy to login to the Joomla site.


**[Google Apps SAML SSO](https://plugins.miniorange.com/joomla-single-sign-sso-using-google-apps-idp)**

The Joomla SAML Single Sign On SSO plugin supports SSO with G Suite / Google Apps (Google Apps Login / Login with G Suite / Login with Google Apps / G Suite login), allowing users in your organization to log in to your Joomla site using their organization's Google Apps credentials.

We offer seamless integration between Joomla Single Sign On (SSO) and Google Apps Login (Login with Google Apps), allowing you to assign Roles / Groups controls to your users based on their membership in Google Groups or Organizational Units.

Our Joomla SSO plugin enables showing user’s Google Profile photo in place of their avatars across out the site (available with Custom integration) in addition to Google Apps Login / SSO with GSuite / Login using G Suite / Login with Google Apps / Login using Google Apps / G Suite login.

You may watch [this](https://www.youtube.com/watch?v=VqBfbEiJHpA&list=PL2vweZ-PcNpdkpUxUzUCo66tZsEHJJDRl&index=9&ab_channel=miniOrange) video to learn how to set up Google Apps SSO with Joomla.


**[PingFederate SAML SSO](https://plugins.miniorange.com/guide-for-pingfederate-as-idp-with-joomla)**

The Joomla SAML Single Sign On (SSO) plugin is Federation-compatible, allowing your students or employees to connect to the Joomla site using their university credentials from any federation such as IN Common, HAKA, HKAF, and so on.
The Federation SSO add-on is required to enable the Federation Joomla Single Sign-On (SSO).


**[Salesforce Community SAML SSO](https://plugins.miniorange.com/joomla-single-sign-sso-using-salesforce-idp)**

The Joomla SAML Single Sign On SSO plugin enables your Salesforce community users to log in to the Joomla site using their Salesforce user’s credentials (Login with Salesforce / Salesforce Login).
Salesforce Login / Salesforce Single Sign-On / Salesforce Community SSO /Login using Salesforce, are all supported by our Joomla Single Sign-On (SAML SSO) plugin.


**[Keycloak SAML SSO](https://plugins.miniorange.com/joomla-single-sign-sso-using-jboss-keycloak-as-idp)**

The Joomla SAML Single Sign On SSO plugin supports Single Sign-On SSO with Keycloak / Login with Keycloak / Keycloak Login / Keycloak Single Sign-On, allowing users to log in to your Joomla site using their Keycloak server credentials (Keycloak SSO). Users can be assigned different Joomla roles/groups depending on their Keycloak groups and Keycloak capabilities.

You may watch [this](https://www.youtube.com/watch?v=gPYltpSKoP8&list=PL2vweZ-PcNpdkpUxUzUCo66tZsEHJJDRl&index=6&ab_channel=miniOrange) video to learn how to set up Keycloak SSO with Joomla.

**[ADFS SAML SSO](https://plugins.miniorange.com/guide-joomla-single-sign-sso-using-adfs-idp)**

Your users can login to Joomla site by using your ADFS user’s credentials.
Login with ADFS / ADFS SSO employs the secure SAML authentication as suggested by ADFS, including 2-factor Auth if enabled for your ADFS accounts.
ADFS Login / Login with ADFS / ADFS SSO (ADFS Single Sign On) enables you to connect your Joomla site to multiple ADFS servers.
 
You may watch [this](https://www.youtube.com/watch?v=cG2fFBW1zhs&list=PL2vweZ-PcNpdkpUxUzUCo66tZsEHJJDRl&index=2&ab_channel=miniOrange) video to learn how to set up ADFS SSO with Joomla.

**[OneLogin SSO ](https://plugins.miniorange.com/joomla-single-sign-sso-using-onelogin-idp)**

The Joomla SAML Single Sign On (SSO) plugin supports all OneLogin SSO use cases, including login to Joomla using OneLogin users’ credentials. We also offer OneLogin integration to automate user creation, updating, and deletion from OneLogin to your Joomla site.

You may activate OneLogin User Provisioning by utilizing our [SCIM user provisioning](https://plugins.miniorange.com/joomla-onelogin-user-sync-provisioning) add-on along with SAML SSO plugin.

Our Joomla SAML Single Sign-On plugin also supports SSO for school and university use-cases such as ClassLink SSO or ClassLink Login onto your Joomla site (ClassLink Single Sign-On).


###  LIST OF SUPPORTED IDPS

- [Azure AD](https://plugins.miniorange.com/joomla-single-sign-sso-using-azure-ad-idp) (Login with Azure AD)
- [Azure AD B2C](https://plugins.miniorange.com/azure-ad-b2c-saml-single-sign-on-sso-into-joomla) (Login using Azure AD B2C)
- [Keycloak](http://plugins.miniorange.com/joomla-single-sign-on-sso-using-jboss-keycloak-idp) (Login with Keycloak)
- [ADFS](https://plugins.miniorange.com/guide-joomla-single-sign-sso-using-adfs-idp) (Login with ADFS)
- [Okta](https://plugins.miniorange.com/joomla-single-sign-sso-using-okta-idp) (Login with Okta)
- [Salesforce](https://plugins.miniorange.com/joomla-single-sign-sso-using-salesforce-idp) (Login using Salesforce)
- [Shibboleth2](https://plugins.miniorange.com/guide-to-setup-shibboleth2-as-idp-with-joomla) (Login using shibboleth2)
- [Shibboleth3](https://plugins.miniorange.com/guide-to-setup-shibboleth3-as-idp-with-joomla) (Login with shiboleth3)
- [GSuite login / Login with Google Apps / Login using Google Apps directory](https://plugins.miniorange.com/joomla-single-sign-sso-using-google-apps-idp) (Login GSuite login/google apps)
- [miniOrange IDP](https://plugins.miniorange.com/joomla-single-sign-sso-using-miniorange-idp) (supports SAML SSO)
- [Onelogin](https://plugins.miniorange.com/joomla-single-sign-sso-using-onelogin-idp) (Login with Onelogin)
- [Centrify](https://plugins.miniorange.com/joomla-single-sign-on-sso-using-centrify-as-idp) (Login with Centrify)
- [SimpleSAMLphp](https://plugins.miniorange.com/saml-single-sign-on-sso-for-joomla-using-simplesaml-as-idp) (Login with SimpleSAMLphp )
- [OpenAM](https://plugins.miniorange.com/guide-for-openam-as-idp-with-joomla) (Login with OpenAM)
- [Ping Federate](https://plugins.miniorange.com/guide-for-pingfederate-as-idp-with-joomla) (Login with Ping)
- [PingOne](https://plugins.miniorange.com/saml-single-sign-on-sso-for-joomla-using-pingone-as-idp) (PingOne SSO)
- [RSA Secure ID](https://plugins.miniorange.com/guide-for-joomla-single-sign-on-sso-using-rsa-securid-as-idp) (Login with RSA Secure ID)
- [Oracle](https://plugins.miniorange.com/oracle-access-manager-as-idp-and-joomla-as-sp) (Login with Oracle)
- [Bitium](https://plugins.miniorange.com/joomla-single-sign-sso-using-bitium-idp) (Login with Bitium)
- [WSO2](https://plugins.miniorange.com/saml-single-sign-sso-joomla-using-wso2) (Login with WSO2)
- [NetIQ](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-netiq-as-idp) (supports SAML SSO)
- [LastPass](https://plugins.miniorange.com/guide-to-configure-lastpass-as-an-idp-saml-sp) (LastPass SSO)
- [Auth Anvil](https://plugins.miniorange.com/joomla-single-sign-sso-using-authanvil-ias-dp) (Auth Anvil SSO)
- [Auth0](https://plugins.miniorange.com/guide-for-auth0-as-idp-with-joomla) (Login with Auth0)
- [Windows sso](https://plugins.miniorange.com/guide-joomla-single-sign-sso-using-adfs-idp#step2) (Login with Windows sso)
- [Wordpress](https://plugins.miniorange.com/wordpress-single-sign-on-sso-using-joomla) (Login with Wordpress)
- [Drupal](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-with-drupal) (Login with Drupal)
- [Office 365](https://plugins.miniorange.com/saml-single-sign-on-sso-for-joomla-using-office-365-as-idp) (Login with Office 365)
- [Salesforce community](https://plugins.miniorange.com/salesforce-community-saml-single-sign-on-sso-into-joomla) (Login with Salesforce community)
- [Classlink](https://plugins.miniorange.com/saml-single-sign-on-sso-into-joomla-using-classlink-as-idp-classlink-sso-login) (Login with Classlink)
- [Absorb LMS](https://plugins.miniorange.com/absorb-lms-single-sign-on-sso-using-joomla) (Login with Absorb LMS)
- [Gluu server](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-gluu-server-as-idp) (Login with Gluu server)
- [Jumpcloud](https://plugins.miniorange.com/jumpcloud-single-sign-on-sso-using-joomla) (Login with Jumpcloud)
- [Identity server4](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-identityserver4-as-idp) (Login with Identity server4)
- [Degreed](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-degreed-as-idp) (Login with Degreed)
- [CyberArk](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-cyberark-as-idp) (Login with CyberArk)
- [Duo](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-duo-as-idp) (Login with Duo)
- [Fusion Auth](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-fusionauth-as-idp) (Login with Auth)
- [SiteMinder](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-siteminder-as-idp) (Login with SiteMinder)
- [SecureAuth](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-secureauth-as-idp) (Login with SecureAuth)
- [Fonteva](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-fonteva-as-idp) (Login with Fonteva)
- [SURFContext](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-surfconext-as-idp) (Login with SURFContext)
- [Phenixld](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-phenixid-as-idp) (Login with Phenixld)
- [OpenAthens](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-openathens-as-idp) (Login with OpenAthens)
- [CA Identity](https://plugins.miniorange.com/joomla-saml-single-sign-on-sso-using-openathens-as-idp) (Login with CA Identity)
- IBM (Login with IBM)
- Magento (Login with Magento)
- VMware (Login with VMware)
and practically any SAML-compliant Identity Provider.


If you require any [Single Sign On ( SSO )](https://www.miniorange.com/products/single-sign-on-sso) application or need any help with installing this plugin, please feel free to email us at joomlasupport@xecurify.com or Contact us.


### [REAL TIME USER PROVISIONING USING SCIM](https://www.miniorange.com/products/user-provisioning)
It provides real time user-provisioning (sync) from your IDP to your Joomla site using SCIM(System for Cross-domain Identity Management) standard. SCIM is an open standard HTTP-based protocol for automating the communication of user identification information between identity domains, or IT systems. SCIM intends to make cloud user provisioning and management as simple as possible. When an Identity Provider creates, updates, or deletes a user, that user will also be added, updated, or deleted from the Joomla site. Your IDP should be supported for the SCIM standard to the User Provisioning (sync) in order to utilize this plugin.

**Dependencies**
NONE
**24/7 Support**
If you require any SAML Single Sign On (SSO) extensions or need any assistance with installing this plugin or if you have any questions, please feel free to reach out to us on our 24*7 support at joomlasupport@xecurify.com or Contact us.
**WEBSITE**
You can visit our website to find out more security related solutions https://plugins.miniorange.com/joomla/. For more support or info email us at joomlasupport@xecurify.com. You can also submit your query from the plugin’s configuration page.
