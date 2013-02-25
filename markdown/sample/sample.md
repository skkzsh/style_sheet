<link href="../markdown.css" rel="stylesheet" title="test"></link>

<link href="http://google-code-prettify.googlecode.com/svn/trunk/src/prettify.css" type="text/css" rel="stylesheet" />
<script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>
<script type="text/javascript" src="http://google-code-prettify.googlecode.com/svn/trunk/src/prettify.js"></script>
<script type="text/javascript">
$(function(){
$('pre').css({
'background-color': '#f6f6f6',
'border': '1px dotted #ccc',
'padding': '0.8em'
});
$('pre code').addClass('prettyprint');
prettyPrint();
});
</script>

# レベル1のスライムがあらわれた

## レベル2のスライムがあらわれた

### レベル3のスライムがあらわれた

#### レベル4のスライムがあらわれた

##### レベル5のスライムがあらわれた

###### レベル6のスライムがあらわれた


# 下線

---


# 強調

- __太山を挟みて北海を超ゆ__
- _Happy Hacking Keyboard_


# リスト

- フシギダネ
- ヒトカゲ
- ゼニガメ

<!-- dummy -->

1. りゅうおう
2. シドー
3. ゾーマ

# リンク

[github.com/skkzsh/style_sheet](https://github.com/skkzsh/style_sheet)


# 画像

![Android](http://i.minus.com/ibeZeA0UxKPOC9.png "Androidのアイコン")


# 引用

> これは箱男についての記録である。
> ぼくは今、この記録を箱のなかで書きはじめている。
> 頭からかぶると、すっぽり、ちょうと腰の辺まで届くダンボールの箱の中だ。
> つまり、今のところ、箱男はこのぼく自身だということでもある。
> 箱男が、箱の中で、箱男の記録をつけているというわけだ。


# コード

`perl`のサンプル

    @lines = `perldoc -u -f atan2`;
    foreach (@lines) {
        s/\w<([^>]+)>/\U$1/g;
        print;
    }
