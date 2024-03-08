# Flutter Package Roadmap

In order to learn Flutter comprehensively, we decided to use Roadmap to learn it.
This article summarizes useful and popular flutter packages for those who are new to Flutter, those who are just starting to learn Flutter and those who research needed packages for our application feature target.When learn the packages,I think that getstart from examples provided by packages.So added the **package examples**

## 📚 Contents
- [State Management Packages](#State-Management-Packages)
- [Notification Packages](#Notification-Packages)
- [Local Storage Packages](#Local-Storage-Packages)
- [Other Packages](#Other-Packages)


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

  A feaure that use in Most of Applications is Notification Feature. Notification Feature is useful in Social Apps and Apps that need to run in the foreground and background such as File downloaders,Video Players,Audio Players,VPN Apps etc.. The following packages are notification packages
- [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications)
    - [example](https://github.com/MaikuB/flutter_local_notifications/tree/master/flutter_local_notifications/example)
- [awesome_notifications](https://pub.dev/packages/awesome_notifications)
    - [example](https://github.com/rafaelsetragni/awesome_notifications/tree/master/example)

# Local Storage Packages



# Other Packages







