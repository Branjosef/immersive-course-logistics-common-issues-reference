# Common Terminal Issues

## Error: Authentication Failed
1. `git remote -v`
2. The remote will probably be learn-co-students instead of the individual's github account
2. `git remote rm origin `
3. go to the lab on Github, fork the lab, hit the ‘clone or download’ button and copy SSH
4. `git remote add origin git@github.com:user/repo.git `

## ERROR: Sqlite database not being created in Terminal
1. sqlite3 test.db ".databases"

## Error: Sqlite unable to view created database
1. In Atom, go to Preferences >> packages
2. Search tree-view
3. In tree-view, uncheck hide ignored names

## Resources
 - <a href="https://learn.co/manual_setup">manual setup instructions</a>


