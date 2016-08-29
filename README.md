# Sitecore-Sql-Perf-Addon
.sql file to create the sql job which recreates the table and index structure. This will also add the correct user to access TempDB

- Edit line 42 with the database user you want to check for
- Edit line 44 with the database user you want to create and the sql login to associate it with
- Edit line 45 and 46 with the database user you created on line 44 to assign the correct permissions
