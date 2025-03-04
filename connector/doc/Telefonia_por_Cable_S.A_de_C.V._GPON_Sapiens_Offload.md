---
uid: Connector_help_Telefonia_por_Cable_S.A_de_C.V._GPON_Sapiens_Offload
---

# Telefonia por Cable S.A de C.V. GPON Sapiens Offload

The connector is responsible for saving the topology KPI data from all the configured Skyline EPM GPON Platform clusters in a system. This input data is available in CSV files generated by the DataMiner Aggregator.

### Version Info

| Range                | Key Features     | Based on     | System Impact     |
|----------------------|------------------|--------------|-------------------|
| 1.0.0.x \[SLC Main\] | Initial version  | \-           | \-                |

### System Info

| Range     | DCF Integration     | Cassandra Compliant     | Linked Components     | Exported Components     |
|-----------|---------------------|-------------------------|-----------------------|-------------------------|
| 1.0.0.x   | No                  | Yes                     | \-                    | \-                      |

## Configuration

### Connections

#### Virtual Connection - Main

This connector uses a virtual connection and does not require any input during element creation.

## How to use

The connector is self-sufficient and does not require any configuration.

The topology offload actions are activated by the GQI SAPIENS GPON Offload Automation script, which must be scheduled to be executed through the DataMiner Scheduler module.

The connector includes a read me on the General page with more information.
