# BlueBattery

A macOS battery widget for supported Bluetooth accessories.

**[Download the latest release](https://github.com/doil6317/BlueBattery-Releases/releases/latest)**

This public repository hosts downloads and documentation only. The application source code is maintained separately in a private repository.

## Features

- Battery rings with device icons, charging indicators and low-battery colors.
- Small, medium and large widgets, including two medium layouts.
- Choose which devices appear in widgets.
- Local battery history and charging-session graphs for selected devices.
- Background collection with a configurable interval.
- English, Korean and Japanese interfaces.

Battery data and charging status depend on what macOS exposes for each device. macOS controls the actual widget redraw schedule; a collection interval does not guarantee the same widget redraw interval.

## Requirements and installation

- macOS 14 or later; Apple Silicon and Intel Macs.
- Download the DMG attached to a release, open it, and drag **BlueBattery** into **Applications**.
- Open BlueBattery, choose the devices to display, and add a BlueBattery desktop widget.
- Enable background collection in settings to keep collecting after quitting the app.

The published DMG and app are Developer ID signed and Apple notarized. A SHA-256 file is provided alongside the DMG. GitHub's automatic “Source code” archives contain this repository's documentation, not the application.

## 한국어

지원되는 Bluetooth 기기의 배터리 잔량과 충전 상태를 macOS 위젯으로 표시합니다. 선택한 기기의 기록과 충전 구간을 그래프로 볼 수 있습니다.

[최신 릴리즈](https://github.com/doil6317/BlueBattery-Releases/releases/latest)에서 **DMG**를 내려받아 열고, BlueBattery를 **응용 프로그램** 폴더로 옮기세요. 앱에서 표시할 기기를 선택한 뒤 데스크탑에 위젯을 추가하면 됩니다. 앱 종료 후에도 수집하려면 설정에서 백그라운드 수집을 켜세요.

macOS 14 이상, Apple Silicon·Intel Mac을 지원합니다. 위젯의 실제 갱신 시점은 macOS가 결정합니다. 이 저장소에는 배포 파일과 안내 문서만 공개되며 앱 소스는 포함되지 않습니다.

## 日本語

対応するBluetooth機器のバッテリー残量と充電状態をmacOSウィジェットに表示します。選択した機器の履歴や充電セッションをグラフで確認できます。

[最新リリース](https://github.com/doil6317/BlueBattery-Releases/releases/latest)から **DMG** をダウンロードして開き、BlueBatteryを **アプリケーション** フォルダに移動してください。アプリで表示する機器を選び、デスクトップにウィジェットを追加します。アプリ終了後も収集するには、設定でバックグラウンド収集を有効にしてください。

macOS 14以降、Apple Silicon・Intel Macに対応しています。ウィジェットの実際の更新タイミングはmacOSが決定します。このリポジトリは配布ファイルとドキュメント専用で、アプリのソースコードは含まれません。

## Feedback

Please use [Issues](https://github.com/doil6317/BlueBattery-Releases/issues) for bug reports and feature requests. Include your macOS version, Mac architecture and affected device model. Avoid posting private device identifiers or other personal information.
