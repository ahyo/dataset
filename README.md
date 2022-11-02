# Dataset Sounds Respiratory

Created for Thesis and Research at Bina Nusantara University

1. Respiratory sound saved in ***.wav** format
    format: **patientnumber_position_takendate.wav**
    - patientnumber, related to patient.txt
    - position, chest area recorded 
    | Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

    | Position | Notes |
    | --- | --- |
    | AL | Anterior Left |
    | AR | Anterior Right |
    | PL | Posterior Left | 
    | PR | Posterior Right | 
    | LL | Lateral Left |
    | LR | Laterat Right |
    | TR | Trachea |
    - takendate, yyyymmdd
2. diagnosa.txt, Diagnose patient record
 format: patientnumber<tab>takendate<tab>result
 Result are *Healthy, COPD, URTI, Bronchiectasis, Pneumonia and Bronchiolitis*
3. pasien.txt, Demography patients
 format: patientnumber<tab>dateofbirth<tab>gender     

