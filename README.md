## 开发本项目的全过程笔记
### 数据库相关
采用padrino默认使用的SQLite数据库

```$ padrino g migration CreateUsers```

编辑`db/migrate/001_create_users.rb`参考：[sequel schema modification](http://sequel.jeremyevans.net/rdoc/files/doc/schema_modification_rdoc.html) 和 [sequel migration](http://sequel.jeremyevans.net/rdoc/files/doc/migration_rdoc.html)

`$ rake sq:migrate:up`参考：[padrino rake-tasks](http://www.padrinorb.com/guides/rake-tasks)
