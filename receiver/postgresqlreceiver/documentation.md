[comment]: <> (Code generated by mdatagen. DO NOT EDIT.)

# postgresql

## Metrics

These are the metrics available for this scraper.

| Name | Description | Unit | Type | Attributes |
| ---- | ----------- | ---- | ---- | ---------- |
| postgresql.backends | The number of backends. | 1 | Sum | <ul> <li>database</li> </ul> |
| postgresql.blocks_read | The number of blocks read. | 1 | Sum | <ul> <li>database</li> <li>table</li> <li>source</li> </ul> |
| postgresql.commits | The number of commits. | 1 | Sum | <ul> <li>database</li> </ul> |
| postgresql.db_size | The database disk usage. | By | Sum | <ul> <li>database</li> </ul> |
| postgresql.operations | The number of db row operations. | 1 | Sum | <ul> <li>database</li> <li>table</li> <li>operation</li> </ul> |
| postgresql.rollbacks | The number of rollbacks. | 1 | Sum | <ul> <li>database</li> </ul> |
| postgresql.rows | The number of rows in the database. | 1 | Sum | <ul> <li>database</li> <li>table</li> <li>state</li> </ul> |

## Attributes

| Name | Description |
| ---- | ----------- |
| database | The name of the database. |
| operation | The database operation. |
| source | The block read source type. |
| state | The tuple (row) state. |
| table | The schema name followed by the table name. |