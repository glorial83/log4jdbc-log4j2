# resolved log4jdbc-log4j2 [unread] issue

## forked from [joarof/log4jdbc-log4j2](https://github.com/joaoraf/log4jdbc-log4j2/commit/227af0bb2504ea5b717b99233293175617be1f94)

```java
DefaultResultSetCollector.java

//same getters in JDBC 4.2
private static final List<String> GETTERS = Arrays.asList(new String[] {"getArray", 
        "getAsciiStream", "getBigDecimal", "getBinaryStream", "getBlob", "getBoolean", 
        "getByte", "getBytes", "getCharacterStream", "getClob", "getDate", "getDouble", 
        "getFloat", "getInt", "getLong", "getNCharacterStream", "getNClob", "getNString", 
        "getObject", "getRef", "getRowId", "getShort", "getSQLXML", "getString",  
        "getTime", "getTimestamp", "getUnicodeStream", "getURL"});
```
