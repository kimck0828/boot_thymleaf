# SpringBootのthymeleaf練習

## 参考したサイト
[ Spring Boot으로 웹 출시까지 ](https://www.youtube.com/playlist?list=PLPtc9qD1979DG675XufGs0-gBeb2mrona)

## tailwindcss関連で参考になったサイト

[【Spring Boot】Tailwind CSS 導入方法](https://qiita.com/dzs/items/e90653f9a74cb621ab3f)

**★注意するところ**  
tailwindcssインストールコマンドがうまくいかなかった場合
>npm install -D tailwindcss@3
> 
>npx tailwindcss init

### tailwindcssのwatch機能を起動
htmlやjsファイルを変更時に追加変更されるtailwindcssの属性を  
static/output.cssにリアルタイムで更新を行う。

> npm run tailwindcss:watch 