# rpi-sensor-app-demo

## 環境構築（ラズパイの開発環境が整っている前提）
1. mobileフォルダに移動してnpm i
2. serverフォルダに移動してnpm i
3. ラズパイの環境で、raspberrypiフォルダに移動してnpm i
4. server > src > database > connect.ts > uriに自作したmongoDbの接続文字列を入れる
5. 各自スタートコマンドを実行（mobile: npm start, server: npm run dev, raspberrypi: npm start）