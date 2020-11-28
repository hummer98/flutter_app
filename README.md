# flutter_app

Flutter Architecture Sample Repository

## 各種アーキテクチャでflutter_appを書き直してみたの巻

* [`ChangeNotifierProvider`](https://github.com/hummer98/flutter_app/tree/change_notifier)
  * オーソドックスなアレ
* [`ChangeNotifierProvider` + `Builder`で局所化](https://github.com/hummer98/flutter_app/tree/change_notifier_and_builder)
  * 力技だがBuilderでRebuildスコープを縛るのはわりと簡単
* [`ValueNotifier` + `ValueListenableBuilder`](https://github.com/hummer98/flutter_app/tree/value_notifier_and_value_listenable_builder)
  * よくわっかんね...
* [`RxDart(BehaviorSubject)`](https://github.com/hummer98/flutter_app/tree/rxdart_behavior_subject)
  * 安心と安全のRxDart
* [`RxDart + 生Provider`](https://github.com/hummer98/flutter_app/tree/rxdart_and_raw_provider)
  * 生Providerに追い出す
* [`flutter_hooks`](https://github.com/hummer98/flutter_app/tree/flutter_hooks)
  * 圧倒的記述量の少なさだが、全面書き換えっすね...
* [`flutter_hooks` + `riverpod`](https://github.com/hummer98/flutter_app/tree/flutter_hooks_and_riverpods)
  * この記述量でRebuildスコープまで絞れる...人類の科学はここまで来た