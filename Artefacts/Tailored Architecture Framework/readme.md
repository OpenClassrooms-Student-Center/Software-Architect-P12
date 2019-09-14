# Tailored Architecture Method

WebStreet has a strict architecture method directly related to the business. This method is a main competitive advantage for the company since it allows customizing and setting up a client website in less than 72 hours.

These are the principles of WebStreet’s architecture method:

1. All customizations must maximize the use of templates and building blocks.

2. If a part of the site is customized, it has to be documented at the beginning of the code using our Customization Dictionary.

3. Our Customization Dictionary describes what customizations we have performed for a client, what template or building block has been customized and how.

4. All documentation must be written with a global team approach: several WebStreet teams located in different time zones are going to develop the website for a specific client and maintain it later.

5. Templates are a collection of building blocks. Templates do not contain specific code.

6. Building blocks may receive parameters such as language, color, style, placement, etc.

7. No programmer or designer writes one line of code if she or he is not trained in WebStreet Architecture Method.

8. There is a dedicated group at WebStreet called AMG (Architecture Method Guardians) whose sole responsibility is to maintain the consistency and improve the dictionary of building blocks and templates.

9. There is another dedicated group called CMG (Customization Dictionary Guardians) whose main responsibility is to register all customizations for all clients. This group is a link between the WebStreet technical team that has developed the website and the sales team that has been in contact with the client.


# Tailored Architecture Content

Our templates and building blocks are divided into two groups:
1. Back-end (procedural) templates and building blocks
2. Front-end (graphical) templates and building blocks.

Example of a back-end building block: a login object. This object receives a username and password and validates the input in a user database.

Example of a front-end building block: a site header. This object displays a site header with a standard style, color and font. There are site headers for login pages, landing pages and website internal pages.

Example of a back-end template: a new user registration. This template validates a new registered user and sends an email to validate that the user is real, asking to change the password to a new one.  This template uses the login object mentioned above, and other back-end objects.

Example of a front-end template: a site style. This object displays a whole page in the website using front end building blocks such as site header, site footer, site left column, pull down menus, etc.

