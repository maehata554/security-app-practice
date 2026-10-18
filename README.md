# security-app-practice

## 概要

COACHTECH 教材 Tutorial 10-6「Webセキュリティ ハンズオン」で作成した成果物です。
CSRF保護とXSS対策の実装

## 使用技術

- PHP 8.x
- Laravel 10.x
- CSRF 保護（`@csrf`）、XSS 対策（Blade の自動エスケープ）

## 学んだこと

- ビューのどのあたりに記述するか。
- コントローラーの内容
- セキュリティー対策をしなかった時の反応

## 動作確認

http://localhost/contact
アクセスして入力・送信できるかどうか。@csrfを削除した時のエラー、メッセージに入力した時にXSS対策が作動しているか
