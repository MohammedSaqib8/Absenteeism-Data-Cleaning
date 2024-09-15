# Absenteeim Data Cleaning in Pandas

Absenteeism is defined as employee absence from work for unusual hours.
It is one among the various factors affecting the operations of a company, and understanding the cause of this situation is vital to prevent this from occurring.

The dataset provided by a company contains employee information, reason for absence, dates, and many more factors that are intertwined with this occurence.

- Cleaning this data involved preserving vital elements of the dataset and removing unrelated or unimportant information (such as Emp ID).
- Reason for Absence column contained numerical values, as descriptive string values take up a lot of space and aren't really beneficial for analysis.
- Different reasons were categorised under the common health concern, ranging from severe to mild, using Pandas dummies function.
- As a good practice, checkpoints were created after every vital change that was made, while preserving the raw dataset in it's true form.
- Dates were further divided into months and days of the week, to facilitate a broader understanding of absenteeism occurrence thoughout the week.
