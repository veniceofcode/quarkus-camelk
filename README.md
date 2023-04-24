# Camel-K/Quarkus - Use Cases

* Develop integration message processors (ROUTES in camel or micro services or serverless services) to integrate and fetch data from backbends systems(Databases –oracle, Teradata , REST endpoints, TCP Endpoints, LDAP endpoints, MQ Endpoints and File endpoints)

* Develop reusable SHARED services or components (Error Handlers, Audit Handlers, Endpoint Lookup, JSON Schema validation Handlers and XML schema validation handlers), Integration camel ROUTES or server less micro services should be able to seamlessly add and remove shared components as needed.

* Integrate quarkus with password/certificate vault (conjure). integration ROUTES or SHARED components should fetch certs and passwords from vault while establishing connectivity with backend systems (Databases (oracle, Teradata), REST Endpoints, TCP Endpoints, LDAP Endpoints, MQ Endpoints and File Endpoints etc.). Usage of applicaiton.properties or environment variables to store sensitive content should be avoided.

* Usage of Camel Quarkus built-in extensions and components to convert structured (xml, soap, pipe delimited, database result sets) payloads to JSON payloads

* Usage of Camel Quarkus built-in extensions and data-transformation components to perform data mapping activities (identifying the fields or attributes in source data set and map to target data set).

* Develop reusable widgets (REST Connectors, SOAP Connectors, Data Transformation, SQL Component, JDBC Component) using quarkus externsions,  Developers should be able to refer these widgets(Jars) while building Integration routes.  
