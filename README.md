# React Native × Hono × Raspberry Pi 5(node-libgpiod) 人感検知＆録画＆検知履歴保存＆通知システム

## 環境構築（ラズパイにOSとnodeが入っている前提）
1. git clone https://github.com/kentem-ta-yagi/rpi-sensor-app-demo.git
2. mobileフォルダに移動してnpm i
3. serverフォルダに移動してnpm i
4. server > src > database > connect.ts > uriに自作したmongoDbの接続文字列を入れる
5. mobileとraspberrypiフォルダのconstant > constにローカルIPアドレスを入力する
6. ラズパイの環境で、sudo apt updateを実行
7. ラズパイの環境で、sudo apt install -y gpiod libgpiod-dev build-essential python3 make gcc g++ libnode-devを実行
8. ラズパイの環境で、raspberrypiフォルダに移動してnpm i
9. 各自スタートコマンドを実行（mobile: npm start, server: npm run dev, raspberrypi: npm start）