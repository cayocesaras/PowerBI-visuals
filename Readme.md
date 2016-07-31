#Power BI Visuals Documentation

Learn how to build Power BI visuals. We're still working on these docs, but they should be ready by 8/2/2016.
 
##Developing Your First PowerBI Visual
 
This section is to provide you with a step by step tutorial of developing your first PowerBI visual.
In this tutorial, you will be building a simple bar chart. The source code is located here in the [Sample Bar Chart Repo](https://github.com/Microsoft/PowerBI-visuals-sampleBarChart).

![](Tutorial/images/SampleBarChart.png)

1. [Install PowerBI visuals CLI tool](tools/README.md#installation)
2. [Install SSL certifications to enable live preview of visuals](tools/CertificateSetup.md)
3. [Enable Developer Tools in PowerBI](tools/DebugVisualSetup.md)
4. [Create New PowerBI Visual Project](tools/usage.md#creating-a-new-visual)
5. [Start Development Server for Live Update and Incremental Development](tools/usage.md#testing-your-visual-in-powerbi)
6. [Adding the Debug Visual from the Visual Well into your Favorite Report](tools/usage.md#viewing-your-visual-in-powerbi)
7. [Adding External Libraries](Tutorial/ExternalLibraries.md)
8. [Installing Typings for Libraries](Tutorial/Typings.md)
9. [Building a Visual with Static Data](Tutorial/StaticVisual.md)
10. [Adding Databinding to the Bar Chart](Tutorial/DataBinding.md)
11. [Adding Color to the Bar Chart](Tutorial/ColorPalette.md)
12. [Adding Selection and Interaction with Other Visuals](Tutorial/Selection.md)
13. [Adding Static Objects to Property Pane](Tutorial/StaticObjects.md)
14. [Adding Databound Objects to Property Pane](Tutorial/DataBoundObjects.md)

##Table of Contents

* [Anatomy of a Visual Project](VisualProject.md)
* [Installing PowerBI Visuals Tool](tools/README.md#installation)
    * [Install SSL Certifications](tools/CertificateSetup.md)
    * [Enable Developer Tools](tools/DebugVisualSetup.md)
    * [Tools Usage Guide](tools/usage.md)
* [Adding External Libraries](Tutorial/ExternalLibraries.md)
    * [Installing Typings for Libraries](Tutorial/Typings.md)
* [Visual Capabilities Definition](Capabilities/Capabilities.md)
    * [Data Roles](Capabilities/Capabilities.md#define-the-data-fields-your-visual-expects---dataroles)
    * [Data View Mappings](Capabilities/DataViewMappings.md)
    * [Objects](Capabilities/Objects.md)
* [Visual Documentation](Visual/Visual.md)
    * [Visual/IVisual Api](Visual/IVisualApi.md)
    * [Handling Selection in Visuals](Visual/Selection.md)
* [PowerBI Glossary](Glossary.md)
* [Change Log](ChangeLog.md)
* [Roadmap](Roadmap/README.md)
