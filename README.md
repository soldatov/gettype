Class that contains options for the return data of the `gettype($var)` function.

```php
class Types
 {
     const TYPE_BOOLEAN = 'boolean';
     const TYPE_INTEGER = 'integer';
     const TYPE_FLOAT = 'double';
     const TYPE_STRING = 'string';
     const TYPE_ARRAY = 'array';
     const TYPE_OBJECT = 'object';
     const TYPE_RESOURCE_OPEN = 'resource';
     const TYPE_RESOURCE_CLOSED = 'resource (closed)';
     const TYPE_NULL = 'NULL';
 
     /** @deprecated */
     const TYPE_RESOURCE_UNKNOWN = 'unknown type';
 }
```