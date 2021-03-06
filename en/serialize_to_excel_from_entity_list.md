# Serialize to Excel from entity list

**Action Grid** too offers the possibility to serialize to CSV, and now with the Excel addon you can serialize from entity list - basically some or all the entries of a grid of your choice. Similar to Serialize from Text, add a grid button with Action Serialize > Serialize from Entity List. You have the possibility to choose which entities to export to XLS, and even to include all fields at once by ticking one single button. 

**Entity Name** 

Name of the enitity you want to use. (Optional, can be used with the Load Entity (Sql) action)

**Fields**

Provide a list of fields you want to serialize. (Optional)

**Include all fields**

Check this option if you want to serialize all fields.

**Remove Fields Names**

Check this option if you do not want to serialize the names of the fields.

**Use excel formulas**

With this option checked all formulas found will be applied. When a cell has a value that starts with = it will write it as an excel formula.
Example: =Sum(A1,A2)
To escape the = add a ' in front of it.
Example: '=Sum(A1,A2) this will be considered a normal string.

**Criteria**

Add a criteria that fielters the data. (Optional)

**Pattern**

You can provide a pattern for the excel file. (Optional)

**Handle duplicates**

You can choose how to handle when you already have a file with the same name. (Optional, default value is "Rename")

**File password**

Will add a password to the whole file, this way other users will not be able to see the content of the file. (Optional)

**Worksheet password**

Will add a password to the excel worksheet, now users are able to see the content of the file but are not able to edit it. (Optional)

**Folder**

Select the destination where the file will be stored.

**Store Absolute URL**

Provide a token name where to Store Absolute URL. (Optional)

**Store Relative URL**

Provide a token name where to Store Relative URL. (Optional)

**Store Physical Path**

Provide a token name where to Store Physical Path. (Optional)

This extension is also available for DNN Api Endpoint and Sharp Scheduler. 

{% youtube %} https://www.youtube.com/watch?v=vAAjBXPbdIw {% endyoutube %}
