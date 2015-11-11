#####类型  
_id：默认。unique  
单字段：用户定义的。对于sort操作，方向无所谓。  
复合字段：用户在多个字段上定义的index。index中的字段先后会影响query和sort操作。  
朵键索引：如果index建立的字段包含array，mongodb会为array中每一个元素创建index。这样，就可以选择包含一个或多个元素的document。MultiKey是mongodb自动创建的（根据索引字段是否包含array）
