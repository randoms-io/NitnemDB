<p align="center"> <img width="286px" height="auto" src="https://github.com/randomsdeveloper/NitnemDB/blob/master/nitnemdb-repo-logo.png"> </p>

# NitnemDB
Open source database for **Gurbani Nitnem** and **Sundar Gutka** projects

## Features
- Separate tables for Index and Gurbanis
- Pivot between aforementioned tables - baniID
- Covers 100+ Gurbanis
- Available in following formats
  + Realm database
  + SQLite database
  + JSON
- Multiple language support such as
  + Gurmukhi - Non-Unicode
  + Gurmukhi - Unicode
  + English
  + Punjabi - Non-Unicode
  + Punjabi - Unicode
  + Hindi - Unicode
  + Spanish

## Realm Database
Realm is an open source designed for use on iOS and Android, with cross-platform data modeling made easy. With Realm Studio, you can open and edit local and synced Realms, and administer any Realm Object Server instance. Use this link to download realm studio for [macOS](https://studio-releases.realm.io/latest/download/mac-dmg), [Windows](https://studio-releases.realm.io/latest/download/win-setup) and [GNU/Linux](https://studio-releases.realm.io/latest/download/linux-appimage).

Beside iOS and Android, realm can be used with Node.js, React Native and Xamarin. For more information, visit [here.](https://realm.io/)

<p align="center"> <img width="676px" height="auto" src="https://github.com/randomsdeveloper/NitnemDB/blob/master/nitnemDB-realm-list.png"> </p>

## SQLite Database
SQLite is one of the most used stored-database management system in the world. SQLite is _'de-facto'_ lightweight embedded and mobile database system and comes bundled with phones and most computers. With third party software like open source [DB Browser for SQLite](https://sqlitebrowser.org/), or paid alternatives like [TablePlus](https://tableplus.com/), SQLite files can be viewed and modified easily. For more information, visit [here.](https://www.sqlite.org/index.html)

<p align="center"> <img width="676px" height="auto" src="https://github.com/randomsdeveloper/NitnemDB/blob/master/nitnemDB-sqlite-bani.png"> </p>

## Schema
NitnemDB follows a simple approach to save only the most useful data and leave the rest for developer to explore or create. Schema for this database is followed same in both realm and SQLite. It gives an insight into the number of fields available and their data types. Schema shown below is for SQLite version, but is exactly the same in Realm.

<p align="center"> <img width="676px" height="auto" src="https://github.com/randomsdeveloper/NitnemDB/blob/master/nitnemDB-sqlite-schema.png"> </p>

## JSON
JSON format files are also available for easy access as an api request or for creation of other kind of database systems such as MySQL, Maria, Mongo, PostgreSQL or almost any type. These files are available under two categories, List.json (contains indices or indexes) and Banis.json (contains Gurbanis).

## Fonts
To work with Gurmukhi and Punjabi written in Non-Unicode fonts, system must have **GurbaniAkhar**/**AnmolLipi** or any other compatible fonts with key bindings similar to these two installed for compatibility. For Unicode data, any compatible font with Punjabi and Hindi Unicode support is sufficient.

## License
Contents of this repository are published under GNU General Public License version 2.0. You may copy and distribute verbatim copies of the Program's source code as you receive it.
