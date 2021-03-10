# Microsoft Dataverse


## What is Dataverse?

According to the [documentation](https://docs.microsoft.com/en-us/powerapps/maker/data-platform/data-platform-intro?WT.mc_id=github-0000-ninarasi) _Dataverse_ is the new name for what used to be the "Common Data Service" or CDS. Think of Dataverse as a data service subsystem for Power Platform that lets you:

 * store and manage data _securely_ as a set of `tables`
 * where 
    - each table is a set of `rows` and `columns`
    - each column stores a specific `type` of data
    - data can be populated using [Power Query](https://support.microsoft.com/en-us/office/power-query-overview-and-learning-ed614c81-4b00-4291-bd3a-55d80767f81d?ui=en-us&rs=en-us&ad=us&WT.mc_id=github-0000-ninarasi)
 * such that
    - tables can be created with custom schema
    - apps can be built using that data over a unified interface

A key advantage of Dataverse is that it can integrate multiple data sources into a single data store that is exposed to Power Apps, Power Automate, Power BI or Power Virtual Agents for use.


## Articles

This section will link to related posts on this site, in chronological order.



## Relevant Reading

 * Docs / [Microsoft Dataverse](https://powerplatform.microsoft.com/en-us/dataverse/?WT.mc_id=github-0000-ninarasi)
 * Docs / [Microsoft Dataverse Documentation](https://docs.microsoft.com/en-us/powerapps/maker/data-platform/?WT.mc_id=github-0000-ninarasi)
 * Docs / [Microsoft Power Apps Documentation](https://docs.microsoft.com/en-us/powerapps/?WT.mc_id=github-0000-ninarasi)

## Learning Paths

 * Learn / 100.2. [Get started using Dataverse](https://docs.microsoft.com/en-us/learn/paths/get-started-cds/?WT.mc_id=github-0000-ninarasi)
 * Learn / 200.1 [Manage permissions and administration for Dataverse](https://docs.microsoft.com/en-us/learn/paths/manage-permissions-administration-common-data-service/?WT.mc_id=github-0000-ninarasi) 
 * Learn / 200.7 [Extending Power Platform Microsoft Dataverse](https://docs.microsoft.com/en-us/learn/paths/extend-power-platform-common-data-service/?WT.mc_id=github-0000-ninarasi) 
 * Learn / 200.8 [Create relationships, business rules, calculations, and rollups in Dataverse](https://docs.microsoft.com/en-us/learn/paths/create-relationships-common-data-service/?WT.mc_id=github-0000-ninarasi) 
 * Learn / 300.3 [Integrate with Power Platform and Dataverse](https://docs.microsoft.com/en-us/learn/paths/integrate-power-platform/) 

## Random Data Sources

Power Apps help you build mobile apps in a low-code (drag and drop) development environment, but you need to have data to power those experiences. The learning paths provide a sample dataset - but it can be useful to **curate** your own dataset so you understand exactly how and where that data (and the schema) are used in the app development process.

Mock data generators (that create fake or placeholder data) are super helpful. Here are a few resources you can explore. Please check each site for their usage policies or costs. 

  * [Random Data API](https://random-data-api.com/)
  * [Mockaroo](https://mockaroo.com/)
  * [RandomUser.me](https://randomuser.me/)
  * [Fake Store API](https://fakestoreapi.com/)
  * [Faker API](https://fakerapi.it/en)
  * [Dev.To Post with 20 resources](https://dev.to/iainfreestone/20-resources-for-generating-fake-and-mock-data-55g1)

Many will allow you to export the data in a format of your choosing (.CSV, .JSON, .XLS) or access it via an API, giving you various "real-world" options to explore, and workflows to setup, when building your app.
