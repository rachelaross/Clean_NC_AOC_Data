# Clean_NC_AOC_Data
This is one of three Jupyter Notebooks used to tackled the cleaning of a 35GB data set from the N.C. Administrative Office of the Courts. The three notebooks were used to clean different "types" of records: Case, Support and Abstract. Within each of these types, there is a given amount of different "record types," each associated with a different number, representing a different tpye of information on a court case (fees, for example), and each with a different fixed width format. The original files given to us by the A.O.C. were organized such that all information for a court case were grouped in rows near each other, but different record types with different fixed widths were all mixed in together. So, I separated the files by record type and then used this notebook to convert them to CSVs.

Cleaning this data was for the purpose of a journalistic story about evictions in Guilford and Forsyth Counties.

I also did not make good use of the CSV library, because I did not know much about it. This was my first python project.
