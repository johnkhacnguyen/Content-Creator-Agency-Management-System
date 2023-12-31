# Content Creator Agency Information Management System

## Project Description

The Content Creator Agency Information Management System is a web application designed to hold and manage data related to content creators, products, and various relationships within a content creator agency. The system will provide a centralized platform for the agency to efficiently store and access information about their content creators, their work, and other relevant entities for future usage and decision-making.

## Quickstart

In order to log into Oracle for database access, a config.json file needs to be added to ~/public_html directory. This config.json file needs key-value pairs "oracle_username": "ora_cwl" and "oracle_password": "a12345678" to work, which can be seen in main.php lines 218, 219, and 222

## Project Scope

The application will primarily focus on the following aspects of the content creator agency domain:

1. **Content Creators:**
   - Each content creator will have a profile with details like name, age, contact information, and social media handles.
   - Content creators will be associated with various entities, including the content they create, the platforms they use, and any merchandise they sell.
   - The system will track performance metrics for content creators, such as follower count, engagement rate, and revenue generated.

2. **Agency Management:**
   - The agency will have a centralized dashboard to manage content creators, their contracts, and relationships with sponsors.
   - Managers within the agency will have restricted access levels to manage specific aspects of the system.
   - The agency will be able to define different types of contracts they offer to content creators.

3. **Products and Merchandise:**
   - Content creators can associate their merchandise with the application, including details like product name, description, and inventory status.
   - The agency can track merchandise sales and revenue generated from each product.

4. **Sponsors and Partnerships:**
   - The system will maintain a list of sponsors and partners associated with the agency.
   - Sponsors can be linked to specific content creators or campaigns.
