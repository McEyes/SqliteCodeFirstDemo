# SqliteCodeFirstDemo
Sqlite Code First Demo by Migration 
采用了System.Data.SQLite.EF6.Migrations，实现了基本的迁移功能，
但由于sqlite不支持删除column，所以要切换sqlite最好是数据库基本上稳定的情况才使用，
又或者自己实现通过其他方式实现删除column
