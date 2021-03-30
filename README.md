# Flutter Task for recruitment
_____________________

## Task
Create a blogger app, where anyone is able to signup with email and post a mini blog.

## Use Firebase for backend 
- Firebase Firestore as database
- Firebase Authentication for sign in and sign up [simple Email auth]
- Firebase Storage for media
[flutter firebase](https://firebase.flutter.dev/)

## Requirements:
- A user should be able to sign up
- A user should be able to login
- A user should be able to reset its password (Firebase style)
- A user should be able to create , edit and delete his blog post
- A user should be able to see blogs from everyone in REAL TIME

Blog can contain a max of 1000 words, and a photo [ optional ]

...Use [stacked architecture](https://www.filledstacks.com/) to achieve the requirements
...Using [stacked](https://pub.dev/packages/stacked) and [stacked-services](http://stacked_services) is a must

All the remaining technicalities are open ended, use your creativity to make an app ready to be published.

## UI requirements:
Design, Colors and Pages have no strict requirements, but the end product should look good and experience should be intuitive.

Use `Themedata` in root widget as much as possible to eliminate duplication of design code in widgets,

Darkmode compatibility will be a plus

## Deliverables:
Github repo
App apk
_If you are confident in you code that it will run on ios do mention it_

Note: 
1. Make sure that code is formatted according to these [guidelines](https://flutter.dev/docs/development/tools/formatting) [use your ide flutter plugin to format code], 
2. There should not be any code Warnings.
3. Be very careful while handling streams, memory leaks etc.
4. For new Coders Don’t be afraid to commit code, do as many commits as it takes.

Total size of all Dart files(in `/lib` folder) will also be considered during evaluation, so keep it compact to the best of your ability.


## Bonus:
Since flutter web is official now, try to Deploy flutter web version on [netlify](https://www.netlify.com/)  [design will not be included in evaluation, but every other feature should work] [flutter firebase ]

## Time Requirements:
Since it is a complete app there is no time limit, but we expect it to take ~4 day work
