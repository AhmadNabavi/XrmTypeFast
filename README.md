# XrmTypeFast
XrmTypeFast is a tool to easily work with Dynamics CRM API Odata service. With the help of TypeScript language, the developer can write his JS code with a syntax so close to C# style and away from all the complexities of the API Odata service such as odatabinding, _xyz_values, etc.

XrmTypeFast is composed of two main components: XrmTypeExtraction & XrmClientService:
	1) XrmTypeExtraction is a C# class library by running which, Object Types such as Entity Types, or Action Types are extracted
	2) XrmClientService is a TypeScript Class file which acts similare to IOrganizationServiceProxy in the XrmSDK so that it handles all CRUD operations in the C# style

