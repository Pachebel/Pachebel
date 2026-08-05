# João Victor Schramm

**Senior Software Engineer — Flutter & Dart**
Balneário Camboriú, Brazil · Open to remote and relocation

I build production mobile applications with Flutter, with a focus on architecture and runtime performance. Five years shipping mobile, ten years in tech. Most of my public code lives upstream rather than in personal repos — see below.


## Flutter framework contribution

**[flutter/flutter#155260](https://github.com/flutter/flutter/pull/155260)** — *fix: CupertinoDatePicker.DateAndTime using showDayOfWeek* · `framework` `f: cupertino`

`CupertinoDatePicker` ignored the `showDayOfWeek: false` flag when running in `dateAndTime` mode — the weekday rendered regardless of what was passed in ([#153576](https://github.com/flutter/flutter/issues/153576)). I traced it through the date-formatting path and fixed the behavior so the parameter is respected in every mode.

Merged after 22 review comments and several rounds with the Flutter team.

## Ecosystem contributions

**[Baseflow/flutter-permission-handler#1544](https://github.com/Baseflow/flutter-permission-handler/issues/1544)** — Swift Package Manager migration

Diagnosed why `permission_handler_apple` reported as unsupported after Flutter's CocoaPods deprecation: under SPM, `Package.swift` resolves permissions from `Info.plist` keys, making the legacy `GCC_PREPROCESSOR_DEFINITIONS` macros in the Podfile obsolete and conflicting. Published a verified step-by-step migration path — the most-upvoted comment in the thread, confirmed as the working fix by other developers.

---

## What I work with

**Mobile** — Flutter, Dart, Riverpod, BLoC, MobX, GetX, Modular
**Architecture** — Clean Architecture, MVVM, SOLID, Repository Pattern
**Performance** — Flutter DevTools profiling, memory management, dependency injection
**Delivery** — GitHub Actions, Fastlane, CodeMagic, Firebase (Crashlytics, FCM, Analytics)
**Backend** — Java, Spring Boot, RESTful APIs, PostgreSQL

---

## Selected results

- Cut app cold start by **39.8%** (8.76s → 5.27s) and reduced RSS by **52 MB** by refactoring dependency injection
- Led an **Ionic → Flutter** migration end to end; deployment speed improved ~70% through CI/CD work
- Shipped a digital bank's loan module from architecture to production, coordinating across engineering, product and compliance

---

## Writing

Case studies and product engineering notes — *published in Portuguese*.

- [Redesigning search flow in a Flutter app](https://medium.com/@pachebel/transformando-a-experi%C3%AAncia-de-busca-minha-jornada-para-aprimorar-o-fluxo-de-pesquisa-dentro-de-um-428ea31848f6) — unifying fragmented categories into a single result set
- [Running quantitative research on a live product](https://medium.com/@pachebel/pesquisa-quantitativa-em-progresso-dba05d1cb703)
- [Why a company needs its own app: the Uliving case](https://medium.com/@pachebel/a-necessidade-em-ter-um-aplicativo-para-a-empresa-uma-an%C3%A1lise-do-desenvolvimento-na-uliving-c3f4e324bccf)

---

## Contact

[LinkedIn](https://www.linkedin.com/in/pachebel/) · joaovictorschramm@hotmail.com
