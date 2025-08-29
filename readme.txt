add-migration "Initial"

I used

Enable-Migrations -EnableAutomaticMigrations -Force

then

Update-Database

And this migrated my changes (additional columns) while preserving my test data. I think this is the laziest option while prototyping.