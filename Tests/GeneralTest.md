## Test Case ID
* LOGIN-001
## Test Script Location
* src/tests/login/login.spec.ts
## Test Case Name
* 正しいユーザー情報でログインできること
## Test Case Description
* 登録済みユーザーが正常にログインできることを確認する
* ログイン後にマイページへ遷移することを確認する
## Pre-conditions
* テストユーザー test01 が登録済みである
* パスワードが password123 で設定されている
* ログイン画面へアクセス済みである
## Post-conditions
* ユーザーセッションが作成されている
* 最終ログイン日時が更新されている
## Date Tested (mm/dd/yy hh:mm:ss)
* 05/08/26 14:30:00
## Test Case Results (Pass / Fail / Not executed / Suspended)
* Pass
---
## Test Steps
1. Step 1
  * Step Details
    * /login にアクセスする
  * Test Data
    * N/A
  * Expected Results
    * ログイン画面が表示される
  * Actual Results
    * ログイン画面が表示された
  * Pass / Fail / Not executed / Suspended
    * Pass
