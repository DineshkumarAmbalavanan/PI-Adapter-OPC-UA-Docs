---
uid: OSIsoftAdapterForOPCUAOverview
---

# OSIsoft Adapter for OPC UA overview

OPC UA is an open standard, which ensures interoperability, security, and reliability of industrial automation devices and systems. OPC UA is recognized as one of the key communication and data modeling technologies of Industry 4.0, due to the fact that it works with many software platforms, and is completely scalable and flexible.

All adapters are developed operating system-agnostic.  You can add a single adapter during installation. For more information, see [Installation](xref:Installation).

The OPC UA adapter is configured with data source and data selection JSON files. It transfers time series data from the data source devices to a defined endpoint. The data source configurations are identical with other adapters, but OPC UA supports an option to generate a data selection file template that you can manually edit and use for subsequent configuration. For details, see [OSIsoft Adapter for OPC UA data selection configuration](xref:OSIsoftAdapterForOPCUADataSelectionConfiguration). Once you create a template file, you can reuse it on both Linux and Windows without changes.