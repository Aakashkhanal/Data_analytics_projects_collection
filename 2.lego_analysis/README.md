Lego is a household name across the world, supported by a diverse toy line, hit movies, and a series of successful video games. In this project, we are going to explore a key development in the history of Lego: the introduction of licensed sets such as Star Wars, Super Heroes, and Harry Potter.

The introduction of its first licensed series, Star Wars, was a hit that sparked a series of collaborations with more themed sets. The partnerships team has asked you to perform an analysis of this success, and before diving into the analysis, they have suggested reading the descriptions of the two datasets to use, reported below.

The Data

You have been provided with two datasets to use. A summary and preview are provided below.

lego_sets.csv

Column	Description
"set_num"	A code that is unique to each set in the dataset. This column is critical, and a missing value indicates the set is a duplicate or invalid!
"name"	The name of the set.
"year"	The date the set was released.
"num_parts"	The number of parts contained in the set. This column is not central to our analyses, so missing values are acceptable.
"theme_name"	The name of the sub-theme of the set.
"parent_theme"	The name of the parent theme the set belongs to. Matches the name column of the parent_themes csv file.

### Set Data Columns Description

| Column         | Description                                                                                      |
|----------------|--------------------------------------------------------------------------------------------------|
| `set_num`      | A code that is unique to each set in the dataset. This column is critical — missing values may indicate duplicates or invalid entries. |
| `name`         | The name of the set.                                                                             |
| `year`         | The date the set was released.                                                                   |
| `num_parts`    | The number of parts contained in the set. This colum_



parent_themes.csv

Column	Description
"id"	A code that is unique to every theme.
"name"	The name of the parent theme.
"is_licensed"	A Boolean column specifying whether the theme is a licensed theme.



### Dataset Columns Description

| Column        | Description                                                  |
|---------------|--------------------------------------------------------------|
| `id`          | A code that is unique to every theme.                        |
| `name`        | The name of the parent theme.                                |
| `is_licensed` | A Boolean column specifying whether the theme is licensed.   |


