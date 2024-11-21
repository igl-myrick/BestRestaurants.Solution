# Best Restaurants

#### _A website where users can track their favorite restaurants._

#### By _**India Lyon-Myrick**_

## Technologies Used

* _C#_
* _.NET_
* _MySQL_

## Description

_Users can add and view their favorite local restaurants, with the ability to add and sort by cuisine. The site opens to a landing page, with the option to either view added restaurants individually, or view restaurants within each added style of cuisine. Both restaurant and cuisine overviews have pages to view a specific restaurant or cuisine's details, an option to edit those details, and an option for deletion._

## Setup/Installation Requirements

* _You will need .NET (`https://dotnet.microsoft.com/en-us/download/dotnet/6.0`) and MySQL (`https://downloads.mysql.com/archives/get/p/25/file/mysql-installer-web-community-8.0.19.0.msi`) in order to run the program._

_1: Clone the repository to a folder of choice on your machine (by either using the "Code" button on the GitHub page, or in a terminal application using `git clone https://github.com/igl-myrick/BestRestaurants.Solution`)._

_2: Using a terminal application such as Git Bash or Windows Command Prompt, navigate to the top level of the program folder, then into the `BestRestaurants` folder._

_3: Next, run `dotnet build` in the command line to build the program._

_4: Once the program is built, run `dotnet run` to start the program._

_5: When the program is running, navigate to `https://localhost:5001` to view and use the website._

* _Additionally, you will need to create an `appsettings.json` file within the `BestRestaurants` folder, including the following code:_

```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[YOUR-DB-NAME];uid=[YOUR-USER-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```

_You will need to insert your own MySQL username in place of `[YOUR-USER-HERE]`, MySQL password in place of `[YOUR-PASSWORD-HERE]`, and the name of your database in place of `[YOUR-DB-NAME]`._

## Known Bugs

* _None at the moment_

## License

MIT:

Copyright (c) _11/21/2024_ _India Lyon-Myrick_

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.