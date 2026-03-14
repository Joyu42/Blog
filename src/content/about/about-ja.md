---
lang: ja
---
![](src/content/about/background-about.JPG)
# Blog
```c++
/**
 * @note このサイトの目的は、知識をひけらかすことではなく、無知を記録することです。
 * @since 2025-10-22T09:07:46.286Z
 */
#include <iostream>
#include <string>
class Blog{
public:
    std::string name, author, url;

<<<<<<< HEAD
Retypeset は、日本語では「再組版」と呼ばれる、[Astro](https://astro.build/) フレームワークをベースにした静的ブログテーマです。[活版印字](https://astro-theme-typography.vercel.app/) からデザインのインスピレーションを得て、新しい視覚的な規範を確立し、すべてのページのレイアウトを再構成することで、紙の書籍のような読書体験を提供し、版面の美しさを蘇らせます。見るものすべてが細部にこだわり、限られたスペースの中に優雅さを表現しています。
=======
    Blog(const std::string& name, const std::string& author, const std::string& url)
    : name(name), author(author), url(url) {}
};
int main(){
    Blog site("Joyu's Blog","Joyu Ng","https://www.joyu.ink");
    std::cout<<"Thoughts into Bytes."<<std::endl;
    return 0;
}
```
# 私について
こんにちは！

Joyuです。まだ学習の途上にいる学部生です。\
技術いじりが好きで、たまに本や映画、音楽の世界に耽っています。
:::fold[♥️]
*    **Book**: 『罪と罰』、『三日間の幸福』、『シーシュポスの神話』
*    **Music**: 『老人と海』、『Merry Christmas Mr. Lawrence』
*    **Movie**: 『海の上のピアニスト』
*    **Anime**: 『STEINS;GATE』、『新世紀エヴァンゲリオン』
:::
インターネットでお会いできて嬉しいです。😊

お話ししたいことがあれば、**お気軽にメール（gbc@joyu.ink）を送ってください。**

---
> ### _**会えない時のために、こんにちは、こんばんは、そしておやすみ。**_
>
> -- <cite>『トゥルーマン・ショー』</cite>

>>>>>>> ebb1fae (26-2-3 00:16)
