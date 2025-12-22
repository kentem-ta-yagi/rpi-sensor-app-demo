# React Native × Hono × Raspberry Pi 5(node-libgpiod) 人感検知＆検知履歴保存＆通知＆録画システム

## 環境構築（ラズパイの開発環境が整っている前提）
1. git clone https://github.com/kentem-ta-yagi/rpi-sensor-app-demo.git
2. mobileフォルダに移動してnpm i
3. serverフォルダに移動してnpm i
4. ラズパイの環境で、raspberrypiフォルダに移動してnpm i
5. server > src > database > connect.ts > uriに自作したmongoDbの接続文字列を入れる
6. 各自スタートコマンドを実行（mobile: npm start, server: npm run dev, raspberrypi: npm start）