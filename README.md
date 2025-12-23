# TestRepositorya

hello, WORLD

こんにちは、世界

@startuml
left to right direction

actor 学生
actor 教員
actor 職員

rectangle "OTM System\n(el-Campus + UNIVERSAL PASSPORT)" {

  学生 -- (ログイン)
  学生 -- (履修登録)
  学生 -- (成績確認)
  学生 -- (授業資料閲覧)
  学生 -- (課題提出)
  学生 -- (出欠確認)
  学生 -- (お知らせ確認)

  教員 -- (ログイン)
  教員 -- (授業情報登録)
  教員 -- (授業資料アップロード)
  教員 -- (課題作成)
  教員 -- (成績登録)
  教員 -- (出欠管理)

  職員 -- (ユーザー管理)
  職員 -- (履修データ管理)
  職員 -- (成績データ管理)
  職員 -- (システム運用管理)
}

@enduml
