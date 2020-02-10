{
	"Create a Table": {
		"prefix": "ct",
		"body": [
		  "DROP TABLE IF EXISTS `$TableName`;",
		  "CREATE TABLE `$TableName` (",
		  "  `id` INT PRIMARY KEY,",
		  "  `name` Text",
		  ") ",
		  ""
		],
		"description": "Create a Table"
	  },
	  "Create Database": {
		"prefix": "cd",
		"body": [
		  "CREATE DATABASE `$DatabaseName`; ",
		  ""
		],
		"description": "Create Database"
	  },
	  "Drop the database": {
		"prefix": "dd",
		"body": [
		  "DROP DATABASE `$db_name`;"
		],
		"description": "Drop the database"
	  },
	  "custom search": {
		"prefix": "wh",
		"body": [
		  "Select * from ${1:TableName} where ${2:Condition1} = ${3:Value};"
		],
		"description": "custom search"
	  },
	  "Add a column Table": {
		"prefix": "alter",
		"body": [
		  "ALTER TABLE ${1:TableName} ADD COLUMN `${2:ColumnName}`;",
		  ""
		],
		"description": "Create a Table"
	  },
	  "Insert into the Table": {
		"prefix": "ins",
		"body": [
		  "insert into ${1:TableName} (${2:Arg1},${3:Arg2},${4:Arg3}) values (${5:V1},${6:V2},${7:V3});"
		],
		"description": "Insert into the Table"
	  },
	  "Show whole table": {
		"prefix": "show",
		"body": [
		  "Select * from ${TableName};"
		],
		"description": "Show whole table"
	  },
	  "And condition": {
		"prefix": "And",
		"body": [
		  "select * from ${1:TableName} where ${2:Condition1} = ${3:Value} and ${4:Condition2} = ${5:Value}; "
		],
		"description": "And condition"
	  },
	  "Update the table": {
		"prefix": "up",
		"body": [
		  "update ${1:Table} set ${2:Column} = ${3:Value} where ${4:ID} = ${5:Value};"
		],
		"description": "Update the table"
	  },
	  "Delete the entry": {
		"prefix": "del",
		"body": [
		  "delete from ${1:Table} where ${2:ID} = ${3:Value};"
		],
		"description": "Delete the entry"
	  },
	  "get limited queries": {
		"prefix": "limit",
		"body": [
		  "SELECT * FROM ${1:TableName}",
		  "LIMIT ${2:5};"
		],
		"description": "get limited queries"
	  },
	  "get percentage": {
		"prefix": "perc",
		"body": [
		  "SELECT TOP ${1:50} PERCENT * FROM ${2:TableName};"
		],
		"description": "get percentage"
	  },
	  "Get union": {
		"prefix": "union",
		"body": [
		  "select ${1:Field} from ${2:TableName1}",
		  "union",
		  "select ${1:Field} from ${3:TableName2}",
		  "order by ${1:Field};"
		],
		"description": "Get union"
	  },
	  "Assending order": {
		"prefix": "asc",
		"body": [
		  "select * from ${1:TableName} order by ${2:Field} asc;"
		],
		"description": "Assending order"
	  },
	  "Dessending order": {
		"prefix": "desc",
		"body": [
		  "select * from ${1:TableName} order by ${2:Field} desc;"
		],
		"description": "Dessending order"
	  },
	  "Wildcards": {
		"prefix": "wild",
		"body": [
		  "select * from ${1:TableName} where ${2:Field} LIKE '${3:}%';"
		],
		"description": "Wildcards"
	  },
	  "In condition": {
		"prefix": "in",
		"body": [
		  "select * from ${1:TableName} where ${2:Field} IN ('${3:V1}', '${4:V2}','${5:V3}');"
		],
		"description": "In condition"
	  },
	  "Not in condition": {
		"prefix": "notin",
		"body": [
		  "select * from ${1:TableName} where ${2:Field} not in ('${3:V1}', '${4:V2}','${5:V3}');"
		],
		"description": "Not in condition"
	  },
	  "Between condition": {
		"prefix": "bet",
		"body": [
		  "select * from ${1:TableName} where ${2:field} between ${3:} and ${4:};"
		],
		"description": "Between condition"
	  },
	  "Shifting data": {
		"prefix": "shift",
		"body": [
		  "insert into ${1:TargetTableName} (${2:Field1}, ${3:Field2}, ${4:Field3})",
		  "select ${5:Source1}, ${6:Source2}, ${7:Source3} from ${8:SourceTable};"
		],
		"description": "Shifting data"
	  },
	  "Relative shift": {
		"prefix": "shiftf",
		"body": [
		  "insert into ${1:TargetTableName} (${2:Field1}, ${3:Field2}, ${4:Field3})",
		  "select ${2:Source1}, ${3:Source2}, ${4:Source3} from ${5:SourceTable};"
		],
		"description": "Relative shift"
	  },
	  "Case statement": {
		"prefix": "case",
		"body": [
		  "-- conditionField = ${1:Condition}",
		  "select ${2:Field1}, ${3:Field2},",
		  "case",
		  "    when ${1:} > 30 then \"${4:Result 1}\"",
		  "    when ${1:} = 30 then \"${5:Result 2}\"",
		  "    else \"${6:Result 3}\"",
		  "end as ${1:}",
		  "from ${7:TableName};"
		],
		"description": "Case statement"
	  }
	  
}
