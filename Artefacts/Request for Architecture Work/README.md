# Background Context and Drivers

WebStreet is a web agency that specializes in quickly creating websites for clients by using industry and style templates. Developing teams have been overwhelmed by increasing sales of our services to customers all over the world. Several years of development have resulted in a complex software environment, which is clearly not scaling with the business and possibly impeding our growth.

Development times must be reduced and leveraged with new tools and techniques so our developers will be able to deliver faster and cheaper using building blocks and templates for websites. Software building blocks in WebStreet are called Site Atoms. This goal could only be achieved through a new software architecture that will create an agile environment and allow fluid communication and a common language among our development teams all over the world.


# WebStreet Strategic Plan

We plan to reduce cycle times by half. Typical time to deliver to clients is 72 hours, we want to shorten this cycle to 36 hours. Our delivery process has always been based on the “Follow The Sun” principle: the customer orders a website and our Master Team starts developing it during the first day, wherever the team is located. If the the Master Team finishes their work at the end of the first day, they transfer the development package to another team located 8 to 12 hours away. If they do not finish on the first day, they work on the package one more day. The package can be transferred more than once in the development cycle until the site is finished. The Master Team must approve the whole cycle at the end and notify the customer.

We need to get to the point where packages are transferred only 3 to 4 times instead of 6 to 7 times like today. We need a new software architecture to achieve this.

This project is scheduled to finish in 8 weeks (see [High Level Plan](../../Images/13_High_level_plan.png)). A project team, project sponsors and external providers have been appointed to participate. Some other key areas in the organization will be involved (See [RACI Matrix](../../Images/11_RACI.xlsx) and [Stakeholders Map](../../Images/12_Stakeholders_Map.png)).


# Current Architecture

The current architecture at WebStreet is irregular and does not follow a common pattern. Site developers rely on their own templates and they usually ask for templates from colleagues based on personal relations. This causes problems when the package is transferred: the new team in another country has to “discover” what templates have been used and must read a lot of documentation before start coding. This fact delays the delivery cycle at least 12 hours. To clearly describe the current architecture we could say “the current architecture was not based in any design, it is the result of quick measures to manage exponential growth”.

For a diagram of the current architecture see [Tailored Architecture Framework](../Tailored%20Architecture%20Framework/README.md)


# Business Agility

All of our business will be based on Site Atoms and templates. We need a new architecture not only as a starting point but as a platform for new tools, templates, designs and Site Atoms. The new architecture must support our growing variety of sites, our broad coverage of different industries and new technical tools that appear in the market.

While providing the exact capability required three-years ago, the current platform has been designed in such a way as to make it very hard to change any of those historic decisions. The new platform should allow our product teams to rapidly innovate technologies and methods.


# Organizational Constraints

These are some important organizational constraints that we must take into account for this project:

1. While our staff will dedicate many hours to this project, we cannot ignore our constant deadlines with customers. Serving our customers and fulfilling their expectations in time, budget and quality has been and always will be our #1 priority. Our normal service operations cannot be interrupted because of this project.

2. We do not have all the knowledge and experience required for this project inside our organization. We will hire external SMEs (Subject Matter Experts) as freelancers for some technical aspects of this project.

3. The project sponsors and the project team will agree on frequency, dynamics and support documents of project status meetings at the beginning of the project. All stakeholders will comply with these agreed principles (See [RACI Matrix](../../Images/11_RACI.xlsx) and [Stakeholders Map](../../Images/12_Stakeholders_Map.png)).


# Open Issues

These are some open issues that have not been resolved yet:

1. There will be customers that require a high level of customization. We will not be able to use our Site Atoms and templates for these customers. Do we want them as a customer?

2. We currently have Site Atoms and templates only for left-to-right languages (English, French, Spanish, Russian, etc.). Do our architecture, Site Atoms and templates have to support right-to-left languages? (Arabic, Farsi, Hebrew, etc.)

3. If we discover new technologies, methods or tools in the market we currently do not have clear criteria for compliance with our architecture: what if the tool changes the way we handle Site Atoms? What if the new technology makes us change the way templates are built?

