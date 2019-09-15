# Tailored Architecture Framework

WebStreet has a strict architecture framework directly related to the business. This framework is a main competitive advantage for the company since it allows customizing and setting up a client website in less than 72 hours. WebStreet marketing strategy has always communicated this message to the market, and the market has responded. The Board of the company has always made an effort to make technical teams aware of this advantage and respect deadlines accordingly. 

These are the principles of WebStreet’s architecture methodology:

1. No code is written from scratch. All customizations must maximize the use of templates and Site Atoms.

2. If a part of the site is customized, it has to be documented at the beginning of the code using our [Customization Dictionary](../../Images/18_Customization_Dictionary.png), which describes what customizations we have been performed for a client, what template or Site Atom has been customized and how.

3. All documentation must be written with a global team approach: several WebStreet teams located in different time zones are going to develop the website for a specific client and maintain it later.

4. Templates are a collection of Site Atoms. Templates do not contain specific code.

5. Site Atoms may receive parameters such as language, color, style, placement, etc.

6. All client websites are a collection of templates plus some customization. See diagram [here](../../Images/19_Website_Encapsulation.jpg).


# Tailored Architecture Content

Our templates and Site Atoms are divided into two groups:
1. Back-end (procedural) templates and Site Atoms.
2. Front-end (graphical) templates and Site Atoms.

**Example of a back-end Site Atoms:** a login object. This object receives a username and password and validates the input in a user database.

**Example of a front-end Site Atoms:** a site header. This object displays a site header with a standard style, color and font. There are site headers for login pages, landing pages and website internal pages.

**Example of a back-end template:** a new user registration. This template validates a new registered user and sends an email to validate that the user is real, asking to change the password to a new one.  This template uses the login object mentioned above, and other back-end objects.

**Example of a front-end template:** a site style. This object displays a whole page in the website using front end building blocks such as site header, site footer, site left column, pull down menus, etc.


# Configured and deployed tools

These tools are deployed in the organization to help with the website development and setup. They are available to all development teams:

**Site Atoms Dictionary:** a database of all Site Atoms to start with the design and development of a website for a client. See example [here](../../Images/20_Site_Atom_Dictionary.png). Each entry in the dictionary describes the purpose of the Site Atoms, the description, updates to the component, parameters it may receive, typical use and links to projects where this component has been used.

**Configuration Control Dictionary:** a database of relationships between templates and Site Atoms. What calls what, what is called by what. See diagram [here](../../Images/15_Configuration_Control_Dictionary.png).

**Customization Dictionary:** a detailed description of all customizations done to WebStreet clients, with links to real websites. See diagram [here](../../Images/18_Customization_Dictionary.png).

# Interface with Governance Models

This strict architecture method used in WebStreet could not be a main competitive advantage without the formal support of the organization and internal culture. See [RACI Matrix](../../Images/11_RACI.png) and [Stakeholders Map](../../Images/12_Stakeholders_Map.png). The following interfaces have contributed to its success and WebStreet success in the market:

**Interface with the Recruitment Department:** no programmer or designer writes one line of code if she or he is not trained in WebStreet architecture methodology. This is carefully synchronized between technical teams and WebStreet Recruitment Department (part of HR Department).

**Interface with AMG:** there is a dedicated group at WebStreet called AMG (Architecture Method Guardians) whose main responsibility is to maintain the consistency and improve the dictionary of Site Atoms and templates. The AMG group acts as SMEs (Subject Matter Experts) on template topics, Site Atoms and building methods. Technical groups consult them informally on a variety of topics. The AMG group is usually responsible for imparting courses on WebStreet architecture methodology to new recruits as well as to experienced developers. 

**Interface with CMG:** there is another dedicated group called CMG (Customization Dictionary Guardians) whose main responsibility is to register all customizations for all clients. This group is a link between the WebStreet technical team that has developed the website and the sales team that has been in contact with the client. They usually join the last part of the sales cycle in order to assess the quantity and size of customization for a particular client, and they work down the road with technical teams in the documentation of the customization process. No website is delivered to a client without the approval of the CMG.

**Interface with the Sourcing Department:** all external vendors must be certified to work with our existing software architecture. This certification process is implemented jointly by the Sourcing Department and the AMG.

**Interface with the Sales Department:** the CMG group participates actively in the sales process and advises the sale team on customization efforts.
 
**Interface with the E-PMO:** there is an E-PMO (Enterprise Project Management Office) in WebStreet that manages a portfolio of projects deployed in all offices of the company. These projects are internal and do not involve clients. This project will have to be included in that portfolio and will be observed and monitored by the E-PMO.

