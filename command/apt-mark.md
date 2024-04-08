[](ファイル名はコマンド名.md)
# apt-mark
パッケージを自動/手動インストール済みとマークできる。自動/手動インストール済みとは、パッケージをインストールすると要求されるもので、別のパッケージが依存関係を満たすためにインストールされた場合に依存関係に自動インストール済みとマークされる。自動的にインストールされたパッケージは手動でインストールしたパッケージに依存されなくなると、apt-get や aptitude により削除が提案される。

  実行例 [](変更しない)
  
  ```
  なし
  ```


  実行結果　[](変更しない)


  ```
  なし
  ```

### オプション一覧


- **auto**
  
  パッケージを自動インストール済みとマークする。このパッケージに依存する手動でインストールされたパッケージがなくなると、このパッケージを削除する。

  実行例 [](変更しない)
  
  ```
  sudo apt-mark auto nano
  ```


  実行結果　[](変更しない)


  ```
  nano は自動でインストールしたと設定されました。
  ```
- **manual** 
    
  パッケージを手動インストール済みとマークする。このパッケージに依存するほかのパッケージがなくなっても、このパッケージを自動的に削除するのを防ぐ。
  
  実行例　[](変更しない)
  
  ```
  sudo apt-mark manual nano
  ```


  実行結果　[](変更しない)


  ```
  nano は手動でインストールしたと設定されました。
  ```
- **showauto** 
    
  手動でインストールされたパッケージを、パッケージごとに改行して表示する。パッケージを指定しないと、手動でインストールされたパッケージをすべて一覧表示する。パッケージを指定すると、そのパッケージが手動でインストールされている場合に表示する。
  
  実行例　[](変更しない)
  
  ```
  sudo apt-mark showauto
  ```


  実行結果　[](変更しない)


  ```
  accountsservice
  acl
  acpi-support
  acpid
  ~略~
  ```
- **showmanual** 
    
  自動的にインストールされたパッケージを、パッケージごとに改行して表示する。パッケージを指定しないと、自動的にインストールされたパッケージをすべて一覧表示する。パッケージを指定すると、そのパッケージが自動的にインストールされている場合に表示する。
  
  実行例　[](変更しない)
  
  ```
  sudo apt-mark showmanual
  ```


  実行結果　[](変更しない)


  ```
  apparmor-notify
  apparmor-profiles
  apparmor-profiles-extra
  apparmor-utils
  ~略~
  ```
- **hold** 
    
  パッケージを保留としてマークする。パッケージを自動的なインストール、アップグレード、削除から防ぐ。
  
  実行例　[](変更しない)
  
  ```
  sudo apt-mark hold nano
  ```


  実行結果　[](変更しない)


  ```
  nano は保留に設定されました。
  ```
- **unhold** 
    
  以前保留したパッケージを、また操作できるようキャンセルするのに使用する。
  
  実行例　[](変更しない)
  
  ```
  sudo apt-mark unhold nano
  ```


  実行結果　[](変更しない)


  ```
  nano の保留を解除しました。
  ```
- **showhold** 
    
  保留されたパッケージを、パッケージごとに改行して表示する。パッケージを指定しないと、保留されたパッケージをすべて一覧表示する。パッケージを指定すると、そのパッケージが保留されている場合に表示する。
  
  実行例　[](変更しない)
  
  ```
  sudo apt-mark showhold
  ```


  実行結果　[](変更しない)


  ```
  nano
  ```