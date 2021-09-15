<!-- loio11d77aa154f64c2e83cc9652a78bb985 -->

# Developing HTML5 Applications in the Cloud Foundry Environment

SAP BTP enables you to access and run HTML5 applications in a cloud environment without the need to maintain your own runtime infrastructure.

HTML5 applications consist of static content that runs on a browser. Then you develop your applications - either in SAP Business Application Studio, or in your own IDE \(integrated development environment\) - and deploy them to the [HTML5 application repository](HTML5_Application_Repository_f8520f5.md).

Depending on your backed application setup, you either configure the destinations during development, or define them after deploying the application. Finally, to consume the applications, you can create a site in SAP Cloud Portal, build the URL, and define custom domains.

On the Cloud Foundry environment of SAP BTP you can run an application that was uploaded to HTML5 application repository using one of the following options:

-   Use the application router that is managed by SAP.

    For more information, see [Managed Application Router](Managed_Application_Router_589a239.md).

-   Set up and maintain your own application router in your own space.

    For more information, see [Application Router](Application_Router_01c5f9b.md).


Both options allow you to serve static content from HTML5 application repository, authenticate users, rewrite URLs, and forward or proxy requests to other micro services while propagating user information. However, the [managed application router](Managed_Application_Router_589a239.md) brings many benefits, such as:

-   Simplify and speed up your development and deployment experience

-   Save resources by running a serverless HTML5 application, which doesn’t require any application runtime

-   Lower maintenance efforts by leveraging the most up-to-date routing capabilities

-   Meet the changing demand for HTML5 applications by automatically adjusting the service to maintain consistent and predictable performance


Therefore, we recommend running your own [application router](Application_Router_01c5f9b.md) only in advanced cases, for example when application router extensibility is required.

-   **[HTML5 Application Repository](HTML5_Application_Repository_f8520f5.md "HTML5 application repository enables central storage of HTML5 applications' static
		content on the SAP BTP, Cloud Foundry
                                    environment. This service can be consumed from the SAP BTP, Cloud Foundry
                                    Runtime and the
			SAP BTP, Kyma runtime.")**  
HTML5 application repository enables central storage of HTML5 applications' static content on the SAP BTP, Cloud Foundry environment. This service can be consumed from the SAP BTP, Cloud Foundry Runtime and the SAP BTP, Kyma runtime.
-   **[Application Router](Application_Router_01c5f9b.md "The application router is the single point-of-entry for an application running in the
			Cloud
                                Foundry
		environment on SAP BTP.
		The application router is used to serve static content, authenticate users, rewrite URLs,
		and forward or proxy requests to other micro services while propagating user
		information.")**  
The application router is the single point-of-entry for an application running in the Cloud Foundry environment on SAP BTP. The application router is used to serve static content, authenticate users, rewrite URLs, and forward or proxy requests to other micro services while propagating user information.
-   **[Managed Application Router](Managed_Application_Router_589a239.md "")**  

-   **[Sizing Guide](Sizing_Guide_7f07a54.md "This guide explains how much application runtime you must purchase to run HTML5
		applications. ")**  
This guide explains how much application runtime you must purchase to run HTML5 applications.
-   **[Getting Support](Getting_Support_9220a2f.md "If you have questions or encounter an issue while working with HTML5 Application
		Repository, there are various ways to address them.")**  
If you have questions or encounter an issue while working with HTML5 Application Repository, there are various ways to address them.
-   **[Troubleshooting](Troubleshooting_ae1d53e.md "A troubleshooting guide for HTML5 application repository. ")**  
A troubleshooting guide for HTML5 application repository.

**Related Information**  


[HTML5 Application Repository](HTML5_Application_Repository_f8520f5.md "HTML5 application repository enables central storage of HTML5 applications' static content on the SAP BTP, Cloud Foundry environment. This service can be consumed from the SAP BTP, Cloud Foundry Runtime and the SAP BTP, Kyma runtime.")

[Application Router](Application_Router_01c5f9b.md "The application router is the single point-of-entry for an application running in the Cloud Foundry environment on SAP BTP. The application router is used to serve static content, authenticate users, rewrite URLs, and forward or proxy requests to other micro services while propagating user information.")

[Managed Application Router](Managed_Application_Router_589a239.md "")
