The idea with this project is to allow for the easy creation of JSON data, without having to understand JSON. With this in place anyone who can understand basic spreadsheet use will be able to contribute towards compiling JSON data, even if they have no idea the effect of what they are doing. The structure is this, the first Column, "N", has a single integer in its first cell, and all its other cells are ignored. There are then N columns on Object Name variables, with the value in those cells being attatched to a title variable, and the parent-child relationships being established by location in thh Object Name columns. Each row represents a single object in the resulting JSON, and all objects there contain all the same attributes, although I could establish that if there is a null value then the attribute is never instantiated.

# Spreadhseet Example:

| N   | Object_Name_1 | Object_Name_2     | ... | Object_Name_N-1 | Object_Name_N | Attribute_1 | Attribute_2 | Attribute_3 | Attribute_4 |
| --- | ------------- | ----------------- | --- | --------------- | ------------- | ----------- | ----------- | ----------- | ----------- |
| N   | Parent_Name   |                   |     |                 |               |             |             |             |             |
|     |               | Parent_Child_Name |     |                 |               |             |             |             |             |
|     |               |                   |     | Child_Name      |               |             |             |             |             |
|     |               |                   |     | Child_Name      |               |             |             |             |             |
|     |               | Child_Name        |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
|     |               |                   |     |                 |               |             |             |             |             |
