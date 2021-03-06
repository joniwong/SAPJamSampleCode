# SAPJamSampleCode
A collection of simple sample code containing examples that demonstrate simple API and integration workflows.

### OAuth_1_HMAC-SHA1
* Provides authentication of the SAP Jam API with OAuth1.0 and the HMAC-SHA1 signature type.
* This example assumes a Jam deployment with an OAuth client application configured for a company, and a user that can successfully log into the company via the Web UI to authorize the OAuth client to make API requests on behalf of the user.
* Consists of the following Eclipse Projects:
  * jam_java_oauth1_client
    * Client library that provides authentication of the SAP Jam API with OAuth1.0 and the HMAC-SHA1 signature type.
    * Dependencies:
      * junit.jar - http://junit.org/
  * jam_java_oauth1_hmac_sha1_client_sample
     * Sample client code that uses the jam_java_oauth1_client library to illustrate authentication of the SAP Jam API with OAuth1.0 and the HMAC-SHA1 signature type.

### OpenSocial/Gadget/HCP_Lumira
* Source code for the OpenSocial gadget in "Using OpenSocial gadgets with SAP Jam on SAP HANA Cloud Platform" in the "SAP Jam Developer Guide".
* The related documentation is located at: http://help.sap.com/download/documentation/sapjam/developer/index.html#hcp/concepts/INTRO-OpenSocial_HCP.html

### OpenSocial/Gadget/Localization
* Source code for the OpenSocial gadget in "Applying String Localization to OpenSocial Gadgets" in the "SAP Jam Developer Guide".
* The related documentation is located at: http://help.sap.com/download/documentation/sapjam/developer/index.html#opensocial/concepts/LOCALE-StringLocalization.html

### OpenSocial/Gadget/Search/Search_Jam_Appdata
* Source code for the OpenSocial gadget in "Adding OpenSocial Gadget Data to SAP Jam Search" in the "SAP Jam Developer Guide".
* The related documentation is located at: http://help.sap.com/download/documentation/sapjam/developer/index.html#opensocial/concepts/JAM_SEARCH-OpenSocial_Gadget_Data.html

### OpenSocial/Gadget/Tutorial
* Source code required for completing the "SAP Jam OpenSocial Tutorial" in the "SAP Jam Developer Guide".
* The "SAP Jam OpenSocial Tutorial" is a set of 7 lessons for developing a simple SAP Jam OpenSocial gadget.
* This tutorial is located at: http://help.sap.com/download/documentation/sapjam/developer/index.html#opensocial/concepts/tutorial-Intro.html

### SAP_Jam_OData_HCP
* Source code for the "Using the SAP Jam API to access data in Jam via OData" tutorial in the "SAP Jam Developer Guide".
  * http://help.sap.com/download/documentation/sapjam/developer/index.html#hcp/concepts/INTRO-API_integrate_features_data.html
  * Requirements - An account on a SAP Jam instance and an associated SAP HANA Cloud Platform trial account.
* This Java servlet uses your SAP HANA Cloud Platform and SAP Jam instance via OAuth2SAMLBearerAssertion to:
  * Get general information from SAP Jam about the currently logged-in user and the list of groups that user belongs to.
  * Get group specific information from SAP Jam.
  * Create a single-use token for SAP Jam div-embedded widget authentication.


### Widgets/Div/Feed
* Source code for the SAP Jam div-embedded feed widgets in "Using SAP Jam with embeddable widgets" in the "SAP Jam Developer Guide". These feed widgets demonstrate the following authentication types:
  * SuccessFactors IdentityProvider
  * Single Use Token
  * Pre-existing SAP Jam session
  * SAP Jam session with Sign In
  * SAP Jam session with Sign In pop-up
* The related documentation is located at: http://help.sap.com/download/documentation/sapjam/developer/index.html#hcp/concepts/INTRO-embeddable_widgets.html


# License
Copyright 2014, SAP AG

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
