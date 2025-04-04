Data driven 
Just give love to your data.
The vision is to transform the company to follow a data-driven approach to every decision and process!
Data driven vs data informed 
Data driven means to rely on data ti guide the direction of the organasation. 
letting metrics lead the decision, this appoach is based on the idea that numbers don't lie.

A data-driven approach relies on data to guide decision-making, while a data-informed approach treats data as just one source of information that factors into decision-making. That’s the primary difference between the two.

Data-centric is the final stage of data evolution when data is being used at every level of the business. All approaches are valuable and worth considering.

https://medium.com/@hugh_data_science/the-pyramid-of-data-needs-and-why-it-matters-for-your-career-b0f695c13f11
https://nightingalehq.ai/blog/the-ai-hierarchy-of-needs-meets-the-minimum-viable-product/

Data platform 
A data platform creates a prosperous environment for data to thrive.
A data platform is a repository and processing house for all of the organization’s data.  ( often refered as modern data stack )

Data Architecture
Data architecture is the process of designing, building, and managing the structure of the organization’s data assets.
DWH -> DATA LAKE -> DATA LAKEHOUSE
OPERATIONAL WORKLOADS - ANALYTICAL WORKLOADS
Lakehouse are Databrics and Microsoft Fabric
the architecture design of lakehouse remains centralized requiring a team of hyper-specialized data engineers. 
https://delta.io/

Medallion, 
Bronze -> ingestion tables
Silver -> refined tables + feature engineering
Gold   -> feature/agg data + BI + analysis

Data Mesh (more like culture of loving data)
Data Mesh is a paradigm, while lakehouse is a platform.
Data mesh is focused on solving scalability of data ownership. 
Each domain is responsible for the data within its scope, including data modeling, storage, and governance and the architecture must provide a set of practices to enable each domain to manage its data independently.
Data Mesh has 4 core principles, 
Domain Ownership (by its respective domain team)
Data as Product
Self-serve data infra as platform
federated computational governance (global standards )


A platform is not just a
collection of features that Dev teams happened to ask for at specific points in the
past, but a holistic, well-crafted, consistent thing that takes into account the
direction of technology change in the industry as a whole and the changing
needs of the organization. A good platform will also serve to reduce the need for
security and audit teams to spend time with the Dev team
