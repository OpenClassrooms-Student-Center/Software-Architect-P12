# Tailored Architecture Framework

WebStreet has a strict architecture framework directly related to the business. This framework is a main competitive advantage for the company since it allows customizing and setting up a client website in less than 72 hours.

These are the principles of WebStreet’s architecture methodology:

1. No code is written from scratch. All customizations must maximize the use of templates and building blocks.

2. If a part of the site is customized, it has to be documented at the beginning of the code using our [Customization Dictionary](../../Images/18_Customization_Dictionary.png), which describes what customizations we have been performed for a client, what template or building block has been customized and how.

3. All documentation must be written with a global team approach: several WebStreet teams located in different time zones are going to develop the website for a specific client and maintain it later.

4. Templates are a collection of building blocks. Templates do not contain specific code.

5. Building blocks may receive parameters such as language, color, style, placement, etc.

6. All client websites are a collection of templates plus some customization. See diagram [here](../../Images/19_Website_Encapsulation.jpg).


# Tailored Architecture Content

Our templates and building blocks are divided into two groups:
1. Back-end (procedural) templates and building blocks
2. Front-end (graphical) templates and building blocks.

Example of a back-end building block: a login object. This object receives a username and password and validates the input in a user database.

Example of a front-end building block: a site header. This object displays a site header with a standard style, color and font. There are site headers for login pages, landing pages and website internal pages.

Example of a back-end template: a new user registration. This template validates a new registered user and sends an email to validate that the user is real, asking to change the password to a new one.  This template uses the login object mentioned above, and other back-end objects.

Example of a front-end template: a site style. This object displays a whole page in the website using front end building blocks such as site header, site footer, site left column, pull down menus, etc.


# Configured and deployed tools

These tools are deployed in the organization to help with the website development and setup. They are available to all development teams:

**Building Blocks and Templates Dictionary:** a database of all building blocks and templates to start with the design and development of a website for a client. Each entry in the dictionary describes the purpose of the component, the description, updates to the component and typical use. It also has links to projects where this component has been used.

**Configuration Control Dictionary:** a database of relationships between templates and building blocks. What calls what, what is called by.

**Customization Dictionary:** a detailed description of all customizations done to WebStreet clients, with links to real websites.


# Interface with Governance Models

This strict architecture method used in WebStreet could not be a main competitive advantage without the formal support of the organization and internal culture. See [RACI Matrix](../../Images/11_RACI.png) and [Stakeholders Map](../../Images/12_Stakeholders_Map.png). The following interfaces have contributed to its success and WebStreet success in the market:

**Interface with the Recruitment Department:** no programmer or designer writes one line of code if she or he is not trained in WebStreet Architecture Method. This is carefully synchronized between technical teams and WebStreet Recruitment Department (part of HR Department).

**Interface with AMG:** there is a dedicated group at WebStreet called AMG (Architecture Method Guardians) whose sole responsibility is to maintain the consistency and improve the dictionary of building blocks and templates. The AMG group act as SME (Subject Matter Expert) on template topics, building blocks and building methods. Technical groups consult informally them on a variety of topics. At the same time, the AMG group is responsible for imparting courses on WebStreet Architecture Method to new recruits as well as experienced developers. 

**Interface with CMG:** there is another dedicated group called CMG (Customization Dictionary Guardians) whose main responsibility is to register all customizations for all clients. This group is a link between the WebStreet technical team that has developed the website and the sales team that has been in contact with the client. They usually join the last part of the sales cycle in order to assess the quantity and size of customization for a particular client, and they work down the road with technical teams in the documentation of the customization process.

**Interface with the Sourcing Department:** all external vendors must be certified to work with our existing structure. This certification process is implemented jointly by the Sourcing Department and the AMG.

**Interface with the Sales Department:** the CMG group participates actively in the sales process and advises the sale team on customization effort.
 
**Interface with the E-PMO:** there is an E-PMO (Enterprise Project Management Office) in WebStreet that manages a portfolio of projects deployed in all offices of the company. This project will have to be included in that portfolio and will be observed and monitored by the E-PMO.

