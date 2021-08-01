# __Eau Claire's Salon__
### by [John Blalock](https://github.com/simpledimplejohn) 

### __Description__
A webapp with a database that is designed to show my ability to use ASP.Net Core and MYSQL.  This app can take an input of both hair stylists and clients and push that information to a database using a one to many relationship.


### __Technologies Used__

* _C#_
* _ASP.Net Core_
* _NuGet_
* _MySQL Database_
* _Razor_


### __Setup/Installation__

1. _Download repo from github_
2. _Launch in VS Code_
3. _Navigate to the HairSalon directory_
4. _add a filed called `appsettings.json`_
5. _include this code in the file:_
    `{`
`  "ConnectionStrings": {`
`      "DefaultConnection": "Server=localhost;Port=3306;=john_blalock;uid=root;pwd=[PASSWORD];"`
`  }`
`}`
6. _Open MySQL Workbench_
7. _Log in and connected to the Local instance 3306_
8. _Navigate to the Administration tab_
9. _Select Data Import/Restore_
10. _Import the john_blalock.sql database from the root directory_
11. _Now navigate to the root directory in the consol.
12. _run `dotnet run` in the consol_
13. _This should run the app on local server 5000_
14. _Navigate to HTTP://localhost:5000_


### __Known Bugs / Future Goals__
No bugs have been found or reported. Please contact the authors if you experience poor performance.



### __License__
This software is licensed under the [BSD license](license.txt).

[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)

Copyright (c) 2021 

### __Contact Information__
 __John Blalock simpledimplejohn@gmail.com__
