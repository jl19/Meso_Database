# Table: MiST_centre_prescreening_information

## Purpose:
This table stores information related to prescreening activities at MiST (Medical Screening and Testing) centres. It includes data about prescreening IDs, MiST centre IDs, and corresponding patient IDs.

## Columns:
- INTERNAL_ID: Integer, Auto-incremented primary key for internal reference.
- pre_screening_ID: VARCHAR(11), Unique identifier for each prescreening activity.
- MiST_Centre_ID: VARCHAR(11), Identifier for the MiST centre associated with the prescreening.
- MiST_Patient_ID: VARCHAR(11), Identifier linking to the stable ID of patients in the MiST system.

## Primary Key:
- INTERNAL_ID

## Sample Data:
| INTERNAL_ID | pre_screening_ID | MiST_Centre_ID | MiST_Patient_ID |
|-------------|-------------------|-----------------|------------------|
| 1           | MPS-001-001       | M1-001-001      | MiST1_001        |
| 2           | MPS-001-003       | M1-001-002      | MiST1_002        |
| ...         | ...               | ...             | ...              |

## Author and Date:
- Created by: Jinli Luo
- Date: 10/12/2023
  

## Dependencies:
- The MiST_Patient_ID column is linked to the Stable_ID in the patient table.

## Backup and Recovery:
- Regular backups of this table are performed [Specify backup frequency and procedures].
- In case of data loss, recovery can be done using [Specify recovery procedures].
