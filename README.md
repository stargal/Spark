# Spark
Spark is a application that can easily keep diary and the sparks

```mermaid
flowchart LR
Spark --> user[用户模块]
user --> signin[登陆]
user -.-> cloud[云同步]
signin --> cloud

Spark --> application[功能模块]
application --> diary[记日记]
diary --> addDiary[添加日记]
diary --> reviewDiary[编辑日记]
diary --> showDiary[查看日记]

application --> sparks[记灵感]

application --> calendarView[日历视图]


```

