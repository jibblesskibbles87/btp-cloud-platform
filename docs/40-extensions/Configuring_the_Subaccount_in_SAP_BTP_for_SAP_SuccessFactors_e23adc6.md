<!-- loioe23adc699fe64160a56d445e3dae1685 -->

# Configuring the Subaccount in SAP BTP for SAP SuccessFactors

Use this procedure to configure the Single-Sign On \(SSO\) between a subaccount in SAP BTP and the SAP SuccessFactors system.

The authentication to SAP SuccessFactors applications is restricted to the authorized users. The identification of a user is verified by the identity provider, as specified by SAML 2.0. The Identity Authentication service stores a list of all users that are allowed to access the SAP SuccessFactors system along with their credentials. The integration between the SAP SuccessFactors and the idetity provider is based on a trust configuration. When a user attempts to access SAP SuccessFactors for the first time, the system redirects the user to the identity provider for identification. From then on, the user session is kept active, and the user is no longer prompted for credentials when trying to use the SAP SuccessFactors application. This is called single sign-on \(SSO\).

To ensure the required security for accessing the applications, you need to configure the single sign-on between the subaccount and the SAP SuccessFactors system using a SAML identity provider. The single sign-on requires both solutions to be configured as trusted SAML service providers for the identity provider, and at the same time, the identity provider to be configured as trusted identity provider for the two solutions.

If you have an account in the SAP BTP, Cloud Foundry environment, you need to set up the single sign-on \(SSO\) according to this environment.

**Related Information**  


[Establish Trust Between SAP SuccessFactors and SAP BTP](Establish_Trust_Between_SAP_SuccessFactors_and_SAP_BTP_80a3fd1.md "Use this procedure to configure the subaccount in SAP BTP trust settings and add SAP SuccessFactors as an identity provider.")

[Register the Assertion Consumer Service of the Subaccount in SAP BTP in SAP SuccessFactors](Register_the_Assertion_Consumer_Service_of_the_Subaccount_in_SAP_BTP_in_SAP_SuccessFactors_de3a1b3.md "You need to register the assertion consumer service of the subaccount in SAP BTP as an authorized assertion consumer service in Provisioning of SAP SuccessFactors.")

