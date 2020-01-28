# **<u>About survey_compilation.xlsx</u>**

------

#### <u>How Excel sheet was generated</u>

Location of search:`All Files/3 Data Playground Dashboard/Team_1/Datasets`

1. Starting at the above location and looked up each country using it's full name **exactly** as listed in the `Country` column.
2. Filtered results by searching within `File and Folder Names` **only**.

***Assuming the same applies to** `All Files/3 Data Playground Dashboard/Team_2/Datasets` 

------

#### <u>Column information</u>

| **<u>Column Name</u>**           | **<u>Description</u>**                                       |
| -------------------------------- | ------------------------------------------------------------ |
| Country                          | Country name used to conduct search, in alphabetical order   |
| Number of datasets online        | 'Online' here refers to searching http://lapop.ccp.ucr.ac.cr/en by country |
| Years (20xx)                     | Years available online ***Note that some go as far back as the 70s** |
| Comments                         | Notes on datasets available online                           |
| Merged time frame on box         | Merged years taken from respective country's `.zip` filename in `Datasets`folder |
| Years on box (within `Datasets`) | y: if count of `.dta` files `==`Number of datasets online, n: if count is less |
| Files on box: Tech Info          | Count of technical information files                         |
| `.dta`                           | Count of `.dta` files                                        |
| `.sav`                           | Count of `.sav` files                                        |
| `.zip`                           | Count of `.zip` files (Usually 2; 1 for `.dta` and 1 for `.sav`) |
| Questionnaires/Cuestionario      | Count of questionnaire/cuestionario files                    |
| Change logs                      | Count of change logs (Always 2)                              |
| Misc                             | Count and type of files not included in 6 prior columns but still present in each country's search results. Some of these are actually questionnaires. It's just that that word wasn't included in the filename and I noticed this only when I happened to open one. |
| Total                            | Total count of 7 prior columns                               |
| Additional file count (I-VI)     | Count of files in `Datasets` that the country search didn't capture. |
| Filename (I-VI)                  | Filenames of files in `Datasets` that the country search didn't capture. |

<u>Additional information</u>

- Underneath the **Total** and **Additional file count (I-VI)** columns are totals of those columns.
- The **Grand total** is the sum of those totals. 

------

#### <u>A few things to note</u>

- Some of the individual year datasets didn't seem to be present on box as indicated by the `years on box` column but in **most** cases the merged dataset includes those missing years.
- `Additional` files are those not included in the search results. Some were missing because country names were abbreviated or spelled differently in the file name.
- Some `Additional` files seem to be multiple versions of similar (same?) files like the Core Questionnaire, for example.
- The grand total listed in the Excel sheet (962) is **not** the same number as that listed on box for the total number of files in the path mentioned above (951). So, it is likely this manual method of checking counted some files more than once. The priority was not so much the additional files but getting a sense of the core `.dta` files and years covered which should (hopefully!) be correct.

------

Author: Mehnaaz Asad

