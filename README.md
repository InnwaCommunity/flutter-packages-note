# Flutter Package Roadmap

In order to learn Flutter comprehensively, we decided to use Roadmap to learn it.
This article summarizes useful and popular flutter packages for those who are new to Flutter, those who are just starting to learn Flutter and those who research needed packages for our application feature target.When learn the packages,I think that should getstart from examples provided by packages.So added the **package examples**

## 📚 Contents
- [State Management Packages](#State-Management-Packages)
- [Notification Packages](#Notification-Packages)
- [Local Storage Packages](#Local-Storage-Packages)
- [UI & UX Packages](#UI-&-UX-Packages)
- [Cloud DataBase Packages](#Cloud-DataBase-Packages)
- [Gaming Packages](#Gaming-Packages)


# State Management Packages

  In Flutter,need to handle the states well,especially in applications with **multiple features** and **various apicalls**. So, you need to know well state management packages.The following packages are state management packages.
  - [flutter_bloc](https://pub.dev/packages/flutter_bloc)
    - [example](https://github.com/felangel/bloc/tree/master/packages/flutter_bloc/example)
  - [GetX](https://pub.dev/packages/get)
    - [example](https://github.com/jonataslaw/getx/tree/master/example)
  - [flutter_riverpod](https://pub.dev/packages/flutter_riverpod)
    - [example](https://github.com/rrousselGit/riverpod/tree/master/packages/flutter_riverpod/example)
  - [provider](https://pub.dev/packages/provider)
    - [example](https://github.com/rrousselGit/provider/tree/master/packages/provider/example)

If use [flutter_bloc](https://pub.dev/packages/flutter_bloc),you should also use [equatable](https://pub.dev/packages/equatable). [Equatable](https://pub.dev/packages/equatable) use to compare the emitted states from [flutter_bloc](https://pub.dev/packages/flutter_bloc)

# Notification Packages

  A feaure that use in Most of Applications is Notification Feature. Notification Feature is useful in Social Apps and Apps that need to run in the foreground and background such as File downloaders,Video Players,Audio Players,Alarm, VPN Apps etc.. The following packages are notification packages
- [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications)
    - [example](https://github.com/MaikuB/flutter_local_notifications/tree/master/flutter_local_notifications/example)
- [awesome_notifications](https://pub.dev/packages/awesome_notifications)
    - [example](https://github.com/rafaelsetragni/awesome_notifications/tree/master/example)

# Local Storage Packages

  Local Storage is very important to store and manage data in one app.Local Storage can be divided two types(SQL and NoSQL).The following is Local Storage Packages.
  
  **SQL**
  - [sqflite](https://pub.dev/packages/sqflite)
    - [example](https://github.com/tekartik/sqflite/tree/master/sqflite/example)
- [drift](https://pub.dev/packages/drift)
    - [example](https://github.com/simolus3/drift/tree/develop/drift/example)
 - [floor](https://pub.dev/packages/floor)
    - [example](https://github.com/pinchbv/floor/tree/develop/example)

  **NoSQL**
  - [shared_preferences](https://pub.dev/packages/shared_preferences)
    - [example](https://github.com/flutter/packages/tree/main/packages/shared_preferences/shared_preferences)
- [hive](https://pub.dev/packages/hive)
    - [example](https://github.com/isar/hive/tree/main/hive/example)
 - [sembast](https://pub.dev/packages/sembast)
    - [example](https://github.com/tekartik/sembast.dart/tree/master/sembast/example)
- [objectbox](https://pub.dev/packages/objectbox)
    - [example](https://github.com/objectbox/objectbox-dart/tree/main/objectbox/example)
 - [realm](https://pub.dev/packages/realm)
    - [example](https://github.com/realm/realm-dart/tree/main/packages/realm/example)

If you want to store data in secure storage.you can use this.
- [flutter_secure_storage](https://pub.dev/packages/flutter_secure_storage)
    - [example](https://github.com/mogol/flutter_secure_storage/tree/develop/flutter_secure_storage/example)

# UI & UX Packages
UI & UX packages in Flutter empower developers to elevate the overall user experience. The following is UI & UX Packages.

**Calendar,Date and Time UI Packages**
  - [flutter_secure_storage](https://pub.dev/packages/syncfusion_flutter_calendar)
    - [example](https://github.com/syncfusion/flutter-widgets/tree/master/packages/syncfusion_flutter_calendar/example)
  - [table_calendar](https://pub.dev/packages/table_calendar)
    - [example](https://github.com/aleksanderwozniak/table_calendar/tree/master/example)
  - [calendar_date_picker2](https://pub.dev/packages/calendar_date_picker2)
    - [example](https://github.com/theideasaler/calendar_date_picker2/tree/main/example)
  - [calendar_view](https://pub.dev/packages/calendar_view)
    - [example](https://github.com/SimformSolutionsPvtLtd/flutter_calendar_view/tree/master/example)
  - [add_2_calendar](https://pub.dev/packages/add_2_calendar)
    - [example](https://github.com/ja2375/add_2_calendar/tree/master/example)

# Cloud DataBase Packages
  
# Gaming Packages







