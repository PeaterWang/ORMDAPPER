# Markdown syntax guide

## Headers



## Lists

### ORMDapper

* BatchDeleteByEntity<T>(IEnumerable<T> _EntityObjectList);
* BatchExecute(List<SQLBox> lstSQL); 
* BatchExecute(List<SQLBox> lstSQL, int commitCount);
* Delete<T>(T entity);
* DeleteByEntity<T>(T _EntityObject);
* Execute<T>(T entity);
* ExecuteBySQLScript(string _SQLScript, Dictionary<string, object> paras);
* FindToList<T>(string _SQLScript, Dictionary<string, object> paras = null);
* GetEntitiesBySQLScript<T>(string _SQLScript, Dictionary<string, object> paras = null);
* GetPageingEntities<T>(string _SQLScript, int currentPage, int pageSize, Dictionary<string, object> paras = null);
* GetPageingEntitiesBySQLScript<T>(string _SQLScript, string _countSQL, int currentPage, Dictionary<string, object> paras = null);
* GetPageingEntitiesBySQLScript<T>(string template, string fields, string tableName, QuerySetting<T> qs, Dictionary<string, object> paras = null);
* GetPageingEntitiesBySQLScript<T>(string _SQLScript, string _countSQL, int currentPage, int pageSize, Dictionary<string, object> paras = null);
* Insert<T>(T entity);


### ToolStrip

* ExportExcel<T>(this IEnumerable<T> dataList);
* ExportExcel<T>(this IEnumerable<T> dataList, string fileName);
* ExportExcel<T, T2>(IEnumerable<T> dataList, IEnumerable<T2> dataList2, string fileName);




