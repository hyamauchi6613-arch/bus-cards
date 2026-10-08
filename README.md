# bus-cards
<!DOCTYPE html><html lang="ja"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#0a7d4f">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-title" content="路線カード">
<meta name="apple-mobile-web-app-status-bar-style" content="default">
<link rel="manifest" href="manifest.json">
<link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALQAAAC0CAYAAAA9zQYyAAADcklEQVR42u3dr3YTQRTA4W1OFLh4Tk1kTUUfAgWadwHRh0HzHhX1nBoOHoemL0Ag2cyfe+9+n4VuZnd+mUyadnvz5vOHPwsUsXMJEDQIGgQNgkbQIGgQNAgaBI2gQdAgaBA0CBpBg6BB0CBoEDSCBkGDoEHQIGgEDYIGQYOgQdAIGgQNggZBg6ARNAgaBA2CZtv2WQb6+/Gb2Zrs7ZeP4cd4E/kPb4pY3CWCFrKwy+yhxZxLtPkKs0IL2UpdZoUWs5W67JYDUacO2uos6jJBi1nUthwQMWirs1XaCg3/sc802Nbf62yxivT4/mvEcWV5RZ2yQq+5OD3CufaYvT5MiDiuNcec8SRIseXo+SnU2mP3/mQs4rgy/LTdbssxr32MURMbcVzRo/amkFIEjaBB0CBoEDSCBkGDoEHQIGgEDYIGQYOgQdAIGgQNggZBg6ARNAgaBA2ChoRBj7g/2qWPMeqebRHHFf2mjSlW6J4Xce2xe09sxHFluANpmi1Hj4t57TF7TXDEcWW5ne6Uv1Po7v3bMfrmjt4U4k0hCBoEDYJmw4b/Faznp5fl+/s7V34rHo5WaBA0CBpBg6BB0CBoBA2CBkFDZ8M/+r5/OPoB/y3xA/4gaBA0ggZBg6BB0AgaBA2CBkGDoBE0CBoEDYKGs0y5g/+yjLuL/7vj/cl/+/nyXHZiT533yHMefff+ZZnwGyuzIz71/yrEfc55Vzvn8luOc2Nu9XWZzzv7OYfacvTYdrSYoGyrVqsoW5/3jO1GqRW61cRmWrVajrXKaj016FbP4taTUfGlOOO8plyhrz35XvFFj7rH+Focc2bMYbYcay9C7+iiRt1zXNcce3bMofbQES4G+edv56JQad52WS/OqO1AtG3HiPFc8hjRFqF95Ge8e+BZlUsE/beLJm4Rpw/6XxfzsNGJPIg31x4aBA2CRtCB/Pp0W+pxIo0n2jlbobFCg6CLv/xGfentOa7M240SK3SvCYg+sT3Glz3mMluO1hNRYWJtOUSdLuaWY63yJJ76S7I9HL7+2OSkrj3vaq9G5b7LsXaCsk/smvFX3FqVW6EvWbkq75VPnXf19wflg8abQhA0CBoEDYJG0CBoEDQIGgSNoEHQIGgQNAgaQYOgQdAgaBA0ggZBg6BB0AgaBA2CBkGDoBE0CBoEDYIGQbM9r/Pi53D11Vf5AAAAAElFTkSuQmCC">
<link rel="icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALQAAAC0CAYAAAA9zQYyAAADcklEQVR42u3dr3YTQRTA4W1OFLh4Tk1kTUUfAgWadwHRh0HzHhX1nBoOHoemL0Ag2cyfe+9+n4VuZnd+mUyadnvz5vOHPwsUsXMJEDQIGgQNgkbQIGgQNAgaBI2gQdAgaBA0CBpBg6BB0CBoEDSCBkGDoEHQIGgEDYIGQYOgQdAIGgQNggZBg6ARNAgaBA2CZtv2WQb6+/Gb2Zrs7ZeP4cd4E/kPb4pY3CWCFrKwy+yhxZxLtPkKs0IL2UpdZoUWs5W67JYDUacO2uos6jJBi1nUthwQMWirs1XaCg3/sc802Nbf62yxivT4/mvEcWV5RZ2yQq+5OD3CufaYvT5MiDiuNcec8SRIseXo+SnU2mP3/mQs4rgy/LTdbssxr32MURMbcVzRo/amkFIEjaBB0CBoEDSCBkGDoEHQIGgEDYIGQYOgQdAIGgQNggZBg6ARNAgaBA2ChoRBj7g/2qWPMeqebRHHFf2mjSlW6J4Xce2xe09sxHFluANpmi1Hj4t57TF7TXDEcWW5ne6Uv1Po7v3bMfrmjt4U4k0hCBoEDYJmw4b/Faznp5fl+/s7V34rHo5WaBA0CBpBg6BB0CBoBA2CBkFDZ8M/+r5/OPoB/y3xA/4gaBA0ggZBg6BB0AgaBA2CBkGDoBE0CBoEDYKGs0y5g/+yjLuL/7vj/cl/+/nyXHZiT533yHMefff+ZZnwGyuzIz71/yrEfc55Vzvn8luOc2Nu9XWZzzv7OYfacvTYdrSYoGyrVqsoW5/3jO1GqRW61cRmWrVajrXKaj016FbP4taTUfGlOOO8plyhrz35XvFFj7rH+Focc2bMYbYcay9C7+iiRt1zXNcce3bMofbQES4G+edv56JQad52WS/OqO1AtG3HiPFc8hjRFqF95Ge8e+BZlUsE/beLJm4Rpw/6XxfzsNGJPIg31x4aBA2CRtCB/Pp0W+pxIo0n2jlbobFCg6CLv/xGfentOa7M240SK3SvCYg+sT3Glz3mMluO1hNRYWJtOUSdLuaWY63yJJ76S7I9HL7+2OSkrj3vaq9G5b7LsXaCsk/smvFX3FqVW6EvWbkq75VPnXf19wflg8abQhA0CBoEDYJG0CBoEDQIGgSNoEHQIGgQNAgaQYOgQdAgaBA0ggZBg6BB0AgaBA2CBkGDoBE0CBoEDYIGQbM9r/Pi53D11Vf5AAAAAElFTkSuQmCC">
<title>路線ごとの停留所カード</title>
<meta name="apple-mobile-web-app-capable" content="yes">
<style>
:root{--bg:#f6f7f9;--fg:#1c2330;--card:#fff;--ac:#0a7d4f;--mut:#6b7385;--bd:#dde1e8;--ng:#c0392b;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#12161d;--fg:#e8ebf1;--card:#1b212b;--ac:#3fbf88;--mut:#98a1b3;--bd:#2c3442;--ng:#ef7a6c}}
:root[data-theme="dark"]{--bg:#12161d;--fg:#e8ebf1;--card:#1b212b;--ac:#3fbf88;--mut:#98a1b3;--bd:#2c3442;--ng:#ef7a6c}
html{-webkit-text-size-adjust:100%}*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}button,select,input,.c{touch-action:manipulation}button{min-height:46px;min-width:46px}.c{-webkit-user-select:none;user-select:none}body{margin:0;background:var(--bg);color:var(--fg);font-family:"Hiragino Sans","Hiragino Kaku Gothic ProN","Yu Gothic",YuGothic,"Noto Sans JP","Noto Sans CJK JP",Meiryo,system-ui,-apple-system,sans-serif;padding:calc(10px + env(safe-area-inset-top,0px)) calc(10px + env(safe-area-inset-right,0px)) calc(24px + env(safe-area-inset-bottom,0px)) calc(10px + env(safe-area-inset-left,0px));max-width:760px;margin:0 auto;font-size:16px;overflow-x:hidden}
.stat{display:flex;gap:8px;flex-wrap:wrap}.stat div{flex:1;min-width:30%;text-align:center;background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:8px 4px}.stat b{display:block;font-size:22px}.wk{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:8px 0;border-bottom:1px solid var(--bd)}
h1{font-size:17px;margin:2px 0 8px}.row{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:8px;align-items:center}
button,input,select,textarea{font:inherit;color:var(--fg);background:var(--card);border:1px solid var(--bd);border-radius:10px;padding:8px 11px}
button.on{background:var(--ac);color:#fff;border-color:var(--ac)}select{max-width:100%}
.card{background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:10px;margin-bottom:8px}
.hint{font-size:14px;color:var(--mut);line-height:1.6}.ok{color:var(--ac);font-weight:600}.ng{color:var(--ng);font-weight:600}
#dg{padding:6px 0 10px}
.rw{display:flex;padding:0 0 28px}
.rw.r{flex-direction:row}.rw.l{flex-direction:row-reverse}
.rw.r.t{border-right:8px solid var(--c)}.rw.l.t{border-left:8px solid var(--c)}
.c{position:relative;flex:0 0 var(--w);padding:0 2px;text-align:center;cursor:pointer;min-width:0}
.c:before{content:"";position:absolute;left:0;right:0;top:0;height:8px;background:var(--c)}
.dot{position:relative;z-index:1;margin:-9px auto 0;width:24px;height:24px;border-radius:50%;background:var(--card);border:3px solid var(--c);font-size:11px;line-height:18px;color:var(--fg);font-weight:600}
.lb,.pk{writing-mode:vertical-rl;margin:10px auto 0;font-size:var(--fs,18px);line-height:1.3;display:block;width:1.5em;text-align:left;font-weight:500;white-space:nowrap}
.lb{color:var(--fg)}
.pk{background:#ffe066;border:1px solid #c9a400;border-radius:4px}
.cur .pk,.cur .lb{outline:2px solid #e6194b;outline-offset:2px}
.good{color:var(--ac);font-weight:600}.bad{color:var(--ng);font-weight:600}
textarea{width:100%;height:280px;font-size:13px}
</style></head><body>
<div id="fallback" style="border:2px solid #c0392b;border-radius:12px;padding:10px;margin:8px 0;background:#fff;color:#1c2330;font-size:15px;line-height:1.6">
<b>読み込み中です。</b>この表示が消えない時は、ページのプログラムが動いていません。LINEやファイルのプレビュー画面では動かないので、SafariやChromeなどのブラウザで開き直してください。下の一覧は、予備として表示しています。
<details style="margin-top:8px"><summary><b>路線一覧（予備表示）</b></summary><details><summary>みなみ線 17（内回り・中田・短大経由）（32）</summary><p>競輪場前 → 三菱電機前 → 県立短大 → 小鹿局前 → 済生会病院正面 → 農業会館前 → 曲金三丁目・歯科医師会館 → 小黒二丁目東 → 小黒二丁目 → 八幡二丁目 → 八幡三丁目 → 稲川町 → 静岡駅南口 → 稲川町 → 伊河麻神社前 → 中田小学校 → 中田二丁目 → 中田三丁目西 → 中田四丁目 → 石田イオンセントラルスクエア → 駿河区役所静岡新聞社前 → ポリテクセンター静岡 → 駿河総合高校前 → 有明町南 → 静岡総合庁舎前 → 豊田中学ツインメッセ前 → 豊田一丁目 → 済生会病院南 → 県立短大 → 三菱電機前 → 競輪場前 → 小鹿営業所</p><p>※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。</p></details><details><summary>みなみ線 17（内回り・中田経由）（31）</summary><p>競輪場前 → 三菱電機前 → 県立短大 → 小鹿局前 → 済生会病院正面 → 農業会館前 → 曲金三丁目・歯科医師会館 → 小黒二丁目東 → 小黒二丁目 → 八幡二丁目 → 八幡三丁目 → 稲川町 → 静岡駅南口 → 稲川町 → 伊河麻神社前 → 中田小学校 → 中田二丁目 → 中田三丁目西 → 中田四丁目 → 石田イオンセントラルスクエア → 駿河区役所静岡新聞社前 → ポリテクセンター静岡 → 駿河総合高校前 → 有明町南 → 静岡総合庁舎前 → 豊田中学ツインメッセ前 → 豊田一丁目 → 済生会病院南 → 競輪場入口 → 競輪場前 → 小鹿営業所</p><p>※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。</p></details><details><summary>みなみ線 17（内回り・静岡総合庁舎前まで）（25）</summary><p>競輪場前 → 三菱電機前 → 県立短大 → 小鹿局前 → 済生会病院正面 → 農業会館前 → 曲金三丁目・歯科医師会館 → 小黒二丁目東 → 小黒二丁目 → 八幡二丁目 → 八幡三丁目 → 稲川町 → 静岡駅南口 → 稲川町 → 伊河麻神社前 → 中田小学校 → 中田二丁目 → 中田三丁目西 → 中田四丁目 → 石田イオンセントラルスクエア → 駿河区役所静岡新聞社前 → ポリテクセンター静岡 → 駿河総合高校前 → 有明町南 → 静岡総合庁舎前</p><p>※ジョルダンの停車順をもとに作成。平日の運行です。内回り・外回りは路線図の矢印の向きから判断しています。</p></details><details><summary>みなみ線 18（外回り・小鹿経由）（31）</summary><p>競輪場前 → 三菱電機前 → 県立短大 → 済生会病院南 → 豊田一丁目 → 豊田中学ツインメッセ前 → 静岡総合庁舎前 → 有明町南 → 駿河総合高校前 → ポリテクセンター静岡 → 駿河区役所静岡新聞社前 → 石田イオンセントラルスクエア → 中田四丁目 → 中田三丁目西 → 中田二丁目 → 中田小学校 → 伊河麻神社前 → 稲川町 → 静岡駅南口 → 稲川町 → 八幡三丁目 → 八幡二丁目 → 小黒二丁目 → 小黒二丁目東 → 曲金三丁目・歯科医師会館 → 農業会館前 → 済生会病院正面 → 小鹿局前 → 競輪場入口 → 競輪場前 → 小鹿営業所</p><p>※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。</p></details><details><summary>みなみ線 18（外回り・小鹿・短大経由）（32）</summary><p>競輪場前 → 三菱電機前 → 県立短大 → 済生会病院南 → 豊田一丁目 → 豊田中学ツインメッセ前 → 静岡総合庁舎前 → 有明町南 → 駿河総合高校前 → ポリテクセンター静岡 → 駿河区役所静岡新聞社前 → 石田イオンセントラルスクエア → 中田四丁目 → 中田三丁目西 → 中田二丁目 → 中田小学校 → 伊河麻神社前 → 稲川町 → 静岡駅南口 → 稲川町 → 八幡三丁目 → 八幡二丁目 → 小黒二丁目 → 小黒二丁目東 → 曲金三丁目・歯科医師会館 → 農業会館前 → 済生会病院正面 → 小鹿局前 → 県立短大 → 三菱電機前 → 競輪場前 → 小鹿営業所</p><p>※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。</p></details><details><summary>みなみ線（静岡駅南口〜小黒経由）（13）</summary><p>静岡駅南口 → 稲川町 → 八幡三丁目 → 八幡二丁目 → 小黒二丁目 → 小黒二丁目東 → 曲金三丁目・歯科医師会館 → 農業会館前 → 済生会病院正面 → 小鹿局前 → 競輪場入口 → 競輪場前 → 小鹿営業所</p><p>※ジョルダンの停車順をもとに作成。平日の運行です。</p></details><details><summary>日本平線 41（新静岡〜英和学院大学池田山団地）（18）</summary><p>新静岡 → 静岡駅前 → 静岡ガスエネリアＳＲ静岡入口 → 八幡一丁目 → 八幡二丁目 → 小黒二丁目 → 小黒二丁目東 → 曲金三丁目・歯科医師会館 → 曲金六丁目 → 曲金七丁目 → 東静岡駅南口 → 池田橋 → 長沼大橋南 → 東豊田小学校前 → 西峯田 → 畑守稲荷前 → 動物園入口 → 英和学院大学池田山団地</p><p>※ジョルダンの停車順をもとに作成。行きは栄町を通らず、帰りは静岡ガスエネリアＳＲ静岡入口を通りません。</p></details><details><summary>日本平線 42（新静岡〜日本平ロープウェイ）（24）</summary><p>新静岡 → 静岡駅前 → 静岡ガスエネリアＳＲ静岡入口 → 八幡一丁目 → 八幡二丁目 → 小黒二丁目 → 小黒二丁目東 → 曲金三丁目・歯科医師会館 → 曲金六丁目 → 曲金七丁目 → 東静岡駅南口 → 池田橋 → 長沼大橋南 → 東豊田小学校前 → 西峯田 → 畑守稲荷前 → 動物園入口 → 英和学院大学池田山団地 → 舞台芸術公園 → 日本平メモリアルガーデン → 遊木の森入口 → 日本平ホテル → 日本平夢テラス入口 → 日本平ロープウェイ</p><p>※ジョルダンの停車順をもとに作成。行きは栄町を通らず、帰りは静岡ガスエネリアＳＲ静岡入口を通りません。</p></details><details><summary>日本平線（日本平動物園〜新静岡）（18）</summary><p>日本平動物園 → 動物園入口 → 畑守稲荷前 → 西峯田 → 東豊田小学校前 → 長沼大橋南 → 池田橋 → 東静岡駅南口 → 曲金七丁目 → 曲金六丁目 → 曲金三丁目・歯科医師会館 → 小黒二丁目東 → 小黒二丁目 → 八幡二丁目 → 八幡一丁目 → 栄町 → 静岡駅前 → 新静岡</p><p>※ジョルダンの停車順をもとに作成。土日祝の運行です。</p></details><details><summary>美和大谷線 33（新静岡〜東大谷）（21）</summary><p>新静岡 → 静岡駅前 → 栄町 → 日の出町 → 下横田 → 曲金するが視覚総合特別支援学校 → 済生会病院前 → 小鹿局前 → 競輪場入口 → 小鹿 → 小鹿公民館前 → 堀ノ内 → 片山 → 片山南 → 宮川 → 井庄 → 大谷小学校前 → 洋光台入口 → 大谷 → 大谷中 → 東大谷</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線 34（新静岡〜静岡大学〜東大谷）（21）</summary><p>新静岡 → 静岡駅前 → 栄町 → 日の出町 → 下横田 → 曲金するが視覚総合特別支援学校 → 済生会病院前 → 小鹿局前 → 競輪場入口 → 小鹿 → 小鹿公民館前 → 堀ノ内 → 静大片山 → 静岡大学 → 静大宮川 → 井庄 → 大谷小学校前 → 洋光台入口 → 大谷 → 大谷中 → 東大谷</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線 35（静岡駅〜静岡大学）（13）</summary><p>静岡駅前 → 栄町 → 日の出町 → 下横田 → 曲金するが視覚総合特別支援学校 → 済生会病院前 → 小鹿局前 → 競輪場入口 → 小鹿 → 小鹿公民館前 → 堀ノ内 → 静大片山 → 静岡大学</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線 36（新静岡〜静岡大学〜ふじのくに地球環境史ミュージアム）（18）</summary><p>新静岡 → 静岡駅前 → 栄町 → 日の出町 → 下横田 → 曲金するが視覚総合特別支援学校 → 済生会病院前 → 小鹿局前 → 競輪場入口 → 小鹿 → 小鹿公民館前 → 堀ノ内 → 静大片山 → 静岡大学 → 静大宮川 → 井庄 → 駿河台公園 → ふじのくに地球環境史ミュージアム</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線 37（新静岡〜ふじのくに地球環境史ミュージアム）（18）</summary><p>新静岡 → 静岡駅前 → 栄町 → 日の出町 → 下横田 → 曲金するが視覚総合特別支援学校 → 済生会病院前 → 小鹿局前 → 競輪場入口 → 小鹿 → 小鹿公民館前 → 堀ノ内 → 片山 → 片山南 → 宮川 → 井庄 → 駿河台公園 → ふじのくに地球環境史ミュージアム</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線 126（静岡駅前〜奥長島）（36）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居・浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 新伝馬 → 伊呂波町 → 秋山町 → 西ヶ谷運動場入口 → 下与北 → 安倍口新田 → 安倍口郵便局前 → 安倍口小学校前 → 中の郷 → 美和団地前 → 美和小学校入口 → 遠藤新田 → 美和中学校前 → 原田 → 八十岡入口 → 一面 → 舟沢 → 舟沢上 → 敷地 → 敷地上 → 湯権現 → 栗島 → 谷沢 → 口長島 → 奥長島</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線 126（静岡駅前〜奥長島・安倍口団地経由）（38）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居・浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 新伝馬 → 伊呂波町 → 秋山町 → 西ヶ谷運動場入口 → 下与北 → 安倍口新田 → 安倍口郵便局前 → 安倍口小学校前 → 安倍口団地南 → 安倍口団地北 → 中の郷 → 美和団地前 → 美和小学校入口 → 遠藤新田 → 美和中学校前 → 原田 → 八十岡入口 → 一面 → 舟沢 → 舟沢上 → 敷地 → 敷地上 → 湯権現 → 栗島 → 谷沢 → 口長島 → 奥長島</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線 126（静岡駅前〜足久保団地・安倍口団地経由）（29）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居・浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 新伝馬 → 伊呂波町 → 秋山町 → 西ヶ谷運動場入口 → 下与北 → 安倍口新田 → 安倍口郵便局前 → 安倍口小学校前 → 安倍口団地南 → 安倍口団地北 → 中の郷 → 美和団地前 → 美和小学校入口 → 遠藤新田 → 美和中学校前 → 足久保こども園 → 谷口北公園上 → 足久保団地</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>美和大谷線（静岡駅前〜美和団地）（21）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居・浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 新伝馬 → 伊呂波町 → 秋山町 → 西ヶ谷運動場入口 → 下与北 → 安倍口新田 → 安倍口郵便局前 → 安倍口小学校前 → 中の郷 → 美和団地前</p><p>※ジョルダンの停車順をもとに作成。土日祝の運行です。</p></details><details><summary>県立病院高松線 20（静岡駅前〜登呂コープタウン）（16）</summary><p>静岡駅前 → 静岡ガスエネリアＳＲ静岡入口 → 八幡一丁目 → 八幡二丁目 → 小黒二丁目 → 小黒三丁目南部体育館入口 → 南郵便局ツインメッセ前 → 静岡総合庁舎前 → 有明町南 → 富士見台・駿河総合高校入口 → 登呂一丁目 → 登呂二丁目 → 登呂二丁目南 → 宮竹一丁目 → 高松公園 → 登呂コープタウン</p><p>※ジョルダンの停車順をもとに作成。静岡駅前→登呂は栄町を通らず、登呂→静岡駅前は静岡ガスエネリアＳＲ静岡入口を通りません。</p></details><details><summary>県立病院高松線 69（静岡駅前〜唐瀬営業所）（23）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 西草深町 → 英和女学院前 → 長谷通り → アイセル21 → 安東二丁目 → 岩成不動 → 中電社宅前 → 城北高校前 → 柳新田上 → 柳新田辻 → 県営住宅前 → 北安東五丁目 → 城北二丁目 → 静岡中央高校入口 → 県立総合病院入口 → 若葉町 → 唐瀬入口 → 岳美 → 唐瀬営業所</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>県立病院高松線 70（静岡駅前〜県立総合病院）（20）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 西草深町 → 英和女学院前 → 長谷通り → アイセル21 → 安東二丁目 → 岩成不動 → 中電社宅前 → 城北高校前 → 柳新田上 → 柳新田辻 → 県営住宅前 → 北安東五丁目 → 城北二丁目 → 静岡中央高校入口 → 県立総合病院入口 → 県立総合病院</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>県立病院高松線（唐瀬営業所〜登呂コープタウン）（38）</summary><p>唐瀬営業所 → 岳美 → 唐瀬入口 → 若葉町 → 県立総合病院入口 → 静岡中央高校入口 → 城北二丁目 → 北安東五丁目 → 県営住宅前 → 柳新田辻 → 柳新田上 → 城北高校前 → 中電社宅前 → 岩成不動 → 安東二丁目 → アイセル21 → 長谷通り → 英和女学院前 → 西草深町 → 中町 → 県庁・静岡市役所葵区役所前 → 新静岡 → 静岡駅前 → 静岡ガスエネリアＳＲ静岡入口 → 八幡一丁目 → 八幡二丁目 → 小黒二丁目 → 小黒三丁目南部体育館入口 → 南郵便局ツインメッセ前 → 静岡総合庁舎前 → 有明町南 → 富士見台・駿河総合高校入口 → 登呂一丁目 → 登呂二丁目 → 登呂二丁目南 → 宮竹一丁目 → 高松公園 → 登呂コープタウン</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>大浜麻機線 72（静岡駅前〜麻機北）（29）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 西草深町 → 英和女学院前 → 長谷通り → 安東一丁目 → 安東二丁目北 → 安東小学校前 → 記念碑前 → 大岩二丁目 → 北安東三丁目 → 池ヶ谷 → 唐瀬 → 時ヶ谷 → 小時 → 谷久保 → 草場 → 八津口 → 中村 → 麻機小学校 → 有永 → 有永上 → 羽高 → 北大門公園入口 → 麻機不動山 → 麻機ヶ丘 → 麻機北</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>大浜麻機線 72（静岡駅前〜麻機）（26）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 西草深町 → 英和女学院前 → 長谷通り → 安東一丁目 → 安東二丁目北 → 安東小学校前 → 記念碑前 → 大岩二丁目 → 北安東三丁目 → 池ヶ谷 → 唐瀬 → 時ヶ谷 → 小時 → 谷久保 → 草場 → 八津口 → 中村 → 麻機小学校 → 有永 → 有永上 → 羽高 → 麻機</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>大浜麻機線 26（静岡駅前〜大浜）（14）</summary><p>静岡駅前 → 静岡商工会議所前 → 馬渕一丁目 → 馬渕二丁目 → 馬渕三丁目 → 馬渕四丁目 → 見瀬Daiichi-TV入口 → 中村町上 → 中村町下 → 西脇ハローワーク静岡入口 → 西脇下 → 西島 → 大浜公園入口 → 大浜</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>石田街道線 11（登呂遺跡系統）（8）</summary><p>静岡駅南口 → 稲川町 → 大坪町 → 城南静岡高入口 → 中田三丁目ダイワハウス前 → 石田ＳＢＳ学苑入口 → 登呂遺跡入口 → 登呂遺跡</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>石田街道線 12（敷地北経由）（19）</summary><p>静岡駅南口 → 稲川町 → 大坪町 → 城南静岡高入口 → 中田三丁目ダイワハウス前 → 石田ＳＢＳ学苑入口 → 登呂遺跡入口 → 登呂南 → 登呂コープタウン入口 → 下島北 → 敷地二丁目 → 敷地北 → 宮竹二丁目 → 宮竹児童公園前 → 高松公民館 → 高松 → 大谷 → 大谷中 → 東大谷</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>石田街道線 15（下島経由）（18）</summary><p>静岡駅南口 → 稲川町 → 大坪町 → 城南静岡高入口 → 中田三丁目ダイワハウス前 → 石田ＳＢＳ学苑入口 → 登呂遺跡入口 → 登呂南 → 登呂コープタウン入口 → 下島北 → 下島 → 浜敷地 → 宮竹 → 高松公民館 → 高松 → 大谷 → 大谷中 → 東大谷</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>石田街道線 14（東大谷〜久能山下）（11）</summary><p>東大谷 → 大谷境 → 西平松 → 中平松 → 青沢 → 久能こども園前 → 古宿 → 久能学校前 → 安居 → 久能局前 → 久能山下</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>石田街道線（静岡駅南口〜高松）（15）</summary><p>静岡駅南口 → 稲川町 → 大坪町 → 城南静岡高入口 → 中田三丁目ダイワハウス前 → 石田ＳＢＳ学苑入口 → 登呂遺跡入口 → 登呂南 → 登呂コープタウン入口 → 下島北 → 下島 → 浜敷地 → 宮竹 → 高松公民館 → 高松</p><p>※ジョルダンの停車順をもとに作成。平日の運行です。</p></details><details><summary>中原池ヶ谷線 71（静岡駅前〜唐瀬営業所）（19）</summary><p>静岡駅前 → 新静岡 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居・浅間神社入口 → 浅間神社 → 丸山町 → 大岩本町 → 臨済寺前 → 大岩町 → 大在家 → 大岩北 → 平ヶ谷 → 池ヶ谷 → 唐瀬 → 唐瀬入口 → 岳美 → 唐瀬営業所</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>中原池ヶ谷線 27（静岡駅前〜徳洲会病院）（21）</summary><p>静岡駅前 → 静岡商工会議所前 → 馬渕一丁目 → 馬渕二丁目 → 馬渕三丁目 → 新川 → 中原町 → 寿町 → 西中原 → 緑が丘 → 中野新田 → 大里中学校 → 静岡ＩＣ入口 → 中島上公民館前 → 中島団地前 → 中島 → 南安倍川橋 → 下川原五丁目 → マイホームセンター前 → 下川原団地 → 徳洲会病院</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>中原池ヶ谷線（唐瀬営業所〜徳洲会病院・八千代経由）（39）</summary><p>唐瀬営業所 → 岳美 → 唐瀬入口 → 唐瀬 → 池ヶ谷 → 平ヶ谷 → 大岩北 → 大在家 → 大岩町 → 臨済寺前 → 大岩本町 → 丸山町 → 浅間神社 → 赤鳥居・浅間神社入口 → 八千代町 → 中町 → 県庁・静岡市役所葵区役所前 → 新静岡 → 静岡駅前 → 静岡商工会議所前 → 馬渕一丁目 → 馬渕二丁目 → 馬渕三丁目 → 新川 → 中原町 → 寿町 → 西中原 → 緑が丘 → 中野新田 → 大里中学校 → 静岡ＩＣ入口 → 中島上公民館前 → 中島団地前 → 中島 → 南安倍川橋 → 下川原五丁目 → マイホームセンター前 → 下川原団地 → 徳洲会病院</p><p>※ジョルダンの停車順をもとに作成。</p></details><details><summary>こども病院線 67（静岡駅前〜静岡神経医療センター）（17）</summary><p>静岡駅前 → 新静岡 → 市民文化会館入口 → 水落町もくせい会館入口・常葉大学静岡水落キャンパス前 → 横内町静岡学園入口 → 巴町 → 銭座町 → 三松 → 沓谷三丁目 → 沓谷四丁目 → 千代田小学校前 → 沓谷五丁目 → 千代田六丁目 → 千代田七丁目・東部体育館入口 → 下足洗 → こども病院 → 静岡神経医療センター</p><p>※唐瀬営業所の路線図の写真から作成。千代田七丁目・東部体育館入口は、1つの停留所として扱っています（要確認）。</p></details><details><summary>こども病院線 67（静岡駅前〜流通センター入口）（16）</summary><p>静岡駅前 → 新静岡 → 市民文化会館入口 → 水落町もくせい会館入口・常葉大学静岡水落キャンパス前 → 横内町静岡学園入口 → 巴町 → 銭座町 → 三松 → 沓谷三丁目 → 沓谷四丁目 → 千代田小学校前 → 沓谷五丁目 → 千代田六丁目 → 千代田七丁目・東部体育館入口 → 下足洗 → 流通センター入口</p><p>※唐瀬営業所の路線図の写真から作成。下足洗の先で分かれる支線です。</p></details><details><summary>上足洗線 75（静岡駅前〜唐瀬営業所）（18）</summary><p>静岡駅前 → 新静岡 → 市民文化会館入口 → 水落町もくせい会館入口・常葉大学静岡水落キャンパス前 → 横内町静岡学園入口 → 巴町 → 銭座町 → 千代田三丁目 → 上足洗 → 上足洗北 → 柳新田西 → 柳新田北 → 北安東四丁目・静岡社会健康医学大学院大学前 → 北安東四丁目西 → 北安東保育園前 → 県立総合病院 → 若葉町 → 唐瀬営業所</p><p>※唐瀬営業所の路線図の写真から作成。終盤（北安東保育園前・県立総合病院・若葉町）の順序は要確認。</p></details><details><summary>唐瀬線 77（静岡駅前〜唐瀬営業所）（20）</summary><p>静岡駅前 → 新静岡 → 市民文化会館入口 → 水落町もくせい会館入口・常葉大学静岡水落キャンパス前 → 横内町静岡学園入口 → 巴町 → 銭座町 → 三松 → 市立高校前 → 千代田四丁目 → 竜南二丁目 → 柳新田 → 北安東五丁目 → 城北二丁目 → 静岡中央高校入口 → 県立総合病院入口 → 若葉町 → 唐瀬入口 → 岳美 → 唐瀬営業所</p><p>※唐瀬営業所の路線図の写真から作成。</p></details><details><summary>唐瀬線 78（静岡駅前〜県立総合病院〜唐瀬営業所）（21）</summary><p>静岡駅前 → 新静岡 → 市民文化会館入口 → 水落町もくせい会館入口・常葉大学静岡水落キャンパス前 → 横内町静岡学園入口 → 巴町 → 銭座町 → 三松 → 市立高校前 → 千代田四丁目 → 竜南二丁目 → 柳新田 → 北安東五丁目 → 城北二丁目 → 静岡中央高校入口 → 県立総合病院入口 → 県立総合病院 → 若葉町 → 唐瀬入口 → 岳美 → 唐瀬営業所</p><p>※唐瀬営業所の路線図の写真から作成。県立総合病院を経由する便です。経由の順序は要確認。</p></details><details><summary>安倍線 111（静岡駅前〜梅ヶ島温泉）（75）</summary><p>静岡駅前 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 籠上北秀英予備校前 → 昭府一丁目 → 昭府二丁目 → 松富団地入口 → 御新田 → 御新田上 → 松富 → 賤機南小学校前 → 中部運転免許センター入口 → 福田ヶ谷新田 → 福田ヶ谷 → 福田ヶ谷上 → 下 → 下公民館前 → 鯨ヶ池入口 → 桜峠入口 → 門屋南 → 門屋 → 牛妻笹子 → 牛妻原 → 賤機中小学校前 → 牛妻 → 牛妻坂下 → 油山 → 松野小学校前 → 松野 → 十二天 → 津渡野 → 郷島宮前 → 郷島 → 野田平入口 → 俵沢 → 六番 → 相渕 → 蕨野 → 蕨野温泉 → 八重沢 → 横山 → 真富士の里 → 平野原 → 平野 → 大河内学校前 → 中平 → 北沢 → 下渡 → 上渡 → 渡本 → 大和田 → 藤代入口 → 珠数落 → 入島 → 湯の森 → 六郎木 → 関の沢入口 → 本村 → 孫佐島 → 大野木 → 草木 → 赤水 → 池尻橋 → 新田 → 新田温泉黄金の湯 → 安倍大滝入口 → 梅ヶ島温泉入口 → 梅ヶ島温泉</p><p>※唐瀬営業所の路線図の写真から作成。※赤鳥居浅間神社入口は、地図上で2つの文字に分かれて見えますが、1つの停留所として扱っています。松野〜十二天付近の順序も要確認。</p></details><details><summary>安倍線 111（静岡駅前〜横沢）（64）</summary><p>静岡駅前 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 籠上北秀英予備校前 → 昭府一丁目 → 昭府二丁目 → 松富団地入口 → 御新田 → 御新田上 → 松富 → 賤機南小学校前 → 中部運転免許センター入口 → 福田ヶ谷新田 → 福田ヶ谷 → 福田ヶ谷上 → 下 → 下公民館前 → 鯨ヶ池入口 → 桜峠入口 → 門屋南 → 門屋 → 牛妻笹子 → 牛妻原 → 賤機中小学校前 → 牛妻 → 牛妻坂下 → 油山 → 松野小学校前 → 松野 → 十二天 → 津渡野 → 郷島宮前 → 郷島 → 野田平入口 → 俵沢 → 六番 → 中沢 → 中沢上 → 金久保 → 桂山原 → 長光寺前 → 桂山 → 唯間 → 玉川診療所 → 上助 → 上助上 → 下平瀬 → 上平瀬 → 川島下 → 川島 → 大和 → 内匠 → 下腰越 → 腰越 → 大沢入口 → 集会所前 → 横沢</p><p>※唐瀬営業所の路線図の写真から作成。※赤鳥居浅間神社入口は、地図上で2つの文字に分かれて見えますが、1つの停留所として扱っています。松野〜十二天付近の順序も要確認。</p></details><details><summary>安倍線 111（静岡駅前〜上落合）（66）</summary><p>静岡駅前 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 籠上北秀英予備校前 → 昭府一丁目 → 昭府二丁目 → 松富団地入口 → 御新田 → 御新田上 → 松富 → 賤機南小学校前 → 中部運転免許センター入口 → 福田ヶ谷新田 → 福田ヶ谷 → 福田ヶ谷上 → 下 → 下公民館前 → 鯨ヶ池入口 → 桜峠入口 → 門屋南 → 門屋 → 牛妻笹子 → 牛妻原 → 賤機中小学校前 → 牛妻 → 牛妻坂下 → 油山 → 松野小学校前 → 松野 → 十二天 → 津渡野 → 郷島宮前 → 郷島 → 野田平入口 → 俵沢 → 六番 → 中沢 → 中沢上 → 金久保 → 桂山原 → 長光寺前 → 桂山 → 唯間 → 玉川診療所 → 上助 → 玉川中学校前 → 奥の原 → 奥の原上 → 森腰 → 森腰上 → 長熊 → 長熊上 → 郷土 → 奥池ヶ谷 → 柿島 → 長妻田 → 粟駒 → 油野 → 上落合</p><p>※唐瀬営業所の路線図の写真から作成。※赤鳥居浅間神社入口は、地図上で2つの文字に分かれて見えますが、1つの停留所として扱っています。松野〜十二天付近の順序も要確認。</p></details><details><summary>安倍線 109（麻機系統）（29）</summary><p>静岡駅前 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 籠上北秀英予備校前 → 昭府一丁目 → 昭府二丁目 → 松富団地入口 → 御新田 → 御新田上 → 松富 → 賤機南小学校前 → 中部運転免許センター入口 → 福田ヶ谷新田 → 福田ヶ谷 → 福田ヶ谷上 → 下 → 下公民館前 → 鯨ヶ池入口 → 桜峠入口 → 老人福祉センター → 鯨ヶ池 → 麻機</p><p>※唐瀬営業所の路線図の写真から作成。老人福祉センターと鯨ヶ池の順序は要確認。</p></details><details><summary>安倍線 110（運転免許センター系統）（20）</summary><p>静岡駅前 → 県庁・静岡市役所葵区役所前 → 中町 → 八千代町 → 赤鳥居浅間神社入口 → 材木町 → 井の宮局前 → 妙見下 → 籠上 → 籠上中 → 籠上北秀英予備校前 → 昭府一丁目 → 昭府二丁目 → 松富団地入口 → 御新田 → 御新田上 → 松富 → 松富北 → 北部体育館入口 → 中部運転免許センター</p><p>※唐瀬営業所の路線図の写真から作成。分岐から先の順序は要確認。</p></details></details></div>
<h1>🚌 路線ごとの停留所カード</h1>
<div class="row"><button id="tV" class="on">学習</button><button id="tS">系統</button><button id="tR">成績</button><button id="tD">路線データ</button></div>
<div id="vw">
 <div class="row"><select id="dp"></select><select id="rs" style="flex:1;min-width:0"></select></div>
 <div class="row"><select id="md"><option value="see">見る</option><option value="peel">付箋をめくる</option><option value="type">順番に入力</option></select>
 <select id="hp"><option value="1">全部隠す</option><option value=".5">半分隠す</option><option value="weak">苦手だけ隠す</option></select><button id="rh">隠し直す</button><button id="sa">全部見る</button></div>
 <div class="row"><span class="hint">文字の大きさ</span><button class="fz" data-f="15">小</button><button class="fz" data-f="18">中</button><button class="fz" data-f="22">大</button><button class="fz" data-f="26">特大</button></div>
 <div class="card" id="qa" style="display:none"><div id="qt" style="margin-bottom:6px"></div>
  <div class="row" style="margin:0"><input id="qi" placeholder="バス停名" style="flex:1;min-width:0"><button id="qb" class="on">回答</button><button id="qk">わからない</button></div>
  <div id="qr" class="hint" style="margin-top:6px"></div></div>
 <div class="hint" id="inf"></div>
 <div id="dg"></div>
</div>
<div id="sy" style="display:none"><div class="card"><div class="row"><select id="sm"><option value="n2l">系統番号 → 路線名</option><option value="l2n">路線名 → 系統番号</option></select><button id="sgo" class="on">次の問題</button><b id="ss"></b></div>
<div id="sq" style="font-size:16px;margin:8px 0;min-height:44px"></div>
<div class="row"><input id="si" placeholder="答え" style="flex:1;min-width:0"><button id="sb" class="on">回答</button><button id="sk">わからない</button></div><div id="sr"></div></div></div>
<div id="rp" style="display:none"></div>
<div id="dt" style="display:none">
 <p class="hint">1路線ごとに「路線名」→「バス停を1行ずつ（運行順）」の順に書き、路線の間は空行で区切ります。保存するとこの端末のブラウザに記録されます。最初に入っている路線は、小鹿営業所・唐瀬営業所の路線図の写真から作りました。路線名は「路線名 番号（区間）」の形で書くと、「系統」タブの問題に使えます。「※」で始まる行はメモとして表示され、「＠」で始まる行は営業所の区分です（複数ならスペースで区切ります）。向きや順序に読み違いがあるかもしれないので、会社の資料と照らして直してください。</p>
 <textarea id="ta"></textarea>
 <div class="row" style="margin-top:8px"><button id="sv" class="on">保存</button><button id="cp">全部コピー</button><button id="rst">最初の状態に戻す</button></div>
</div>
<script>
const $=id=>document.getElementById(id),K='shizuoka_route_cards_v5';
const SAMPLE=`みなみ線 17（内回り・中田・短大経由）
競輪場前
三菱電機前
県立短大
小鹿局前
済生会病院正面
農業会館前
曲金三丁目・歯科医師会館
小黒二丁目東
小黒二丁目
八幡二丁目
八幡三丁目
稲川町
静岡駅南口
稲川町
伊河麻神社前
中田小学校
中田二丁目
中田三丁目西
中田四丁目
石田イオンセントラルスクエア
駿河区役所静岡新聞社前
ポリテクセンター静岡
駿河総合高校前
有明町南
静岡総合庁舎前
豊田中学ツインメッセ前
豊田一丁目
済生会病院南
県立短大
三菱電機前
競輪場前
小鹿営業所
※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。
＠小鹿営業所

みなみ線 17（内回り・中田経由）
競輪場前
三菱電機前
県立短大
小鹿局前
済生会病院正面
農業会館前
曲金三丁目・歯科医師会館
小黒二丁目東
小黒二丁目
八幡二丁目
八幡三丁目
稲川町
静岡駅南口
稲川町
伊河麻神社前
中田小学校
中田二丁目
中田三丁目西
中田四丁目
石田イオンセントラルスクエア
駿河区役所静岡新聞社前
ポリテクセンター静岡
駿河総合高校前
有明町南
静岡総合庁舎前
豊田中学ツインメッセ前
豊田一丁目
済生会病院南
競輪場入口
競輪場前
小鹿営業所
※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。
＠小鹿営業所

みなみ線 17（内回り・静岡総合庁舎前まで）
競輪場前
三菱電機前
県立短大
小鹿局前
済生会病院正面
農業会館前
曲金三丁目・歯科医師会館
小黒二丁目東
小黒二丁目
八幡二丁目
八幡三丁目
稲川町
静岡駅南口
稲川町
伊河麻神社前
中田小学校
中田二丁目
中田三丁目西
中田四丁目
石田イオンセントラルスクエア
駿河区役所静岡新聞社前
ポリテクセンター静岡
駿河総合高校前
有明町南
静岡総合庁舎前
※ジョルダンの停車順をもとに作成。平日の運行です。内回り・外回りは路線図の矢印の向きから判断しています。
＠小鹿営業所

みなみ線 18（外回り・小鹿経由）
競輪場前
三菱電機前
県立短大
済生会病院南
豊田一丁目
豊田中学ツインメッセ前
静岡総合庁舎前
有明町南
駿河総合高校前
ポリテクセンター静岡
駿河区役所静岡新聞社前
石田イオンセントラルスクエア
中田四丁目
中田三丁目西
中田二丁目
中田小学校
伊河麻神社前
稲川町
静岡駅南口
稲川町
八幡三丁目
八幡二丁目
小黒二丁目
小黒二丁目東
曲金三丁目・歯科医師会館
農業会館前
済生会病院正面
小鹿局前
競輪場入口
競輪場前
小鹿営業所
※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。
＠小鹿営業所

みなみ線 18（外回り・小鹿・短大経由）
競輪場前
三菱電機前
県立短大
済生会病院南
豊田一丁目
豊田中学ツインメッセ前
静岡総合庁舎前
有明町南
駿河総合高校前
ポリテクセンター静岡
駿河区役所静岡新聞社前
石田イオンセントラルスクエア
中田四丁目
中田三丁目西
中田二丁目
中田小学校
伊河麻神社前
稲川町
静岡駅南口
稲川町
八幡三丁目
八幡二丁目
小黒二丁目
小黒二丁目東
曲金三丁目・歯科医師会館
農業会館前
済生会病院正面
小鹿局前
県立短大
三菱電機前
競輪場前
小鹿営業所
※ジョルダンの停車順をもとに作成。内回り・外回りは路線図の矢印の向きから判断しています。
＠小鹿営業所

みなみ線（静岡駅南口〜小黒経由）
静岡駅南口
稲川町
八幡三丁目
八幡二丁目
小黒二丁目
小黒二丁目東
曲金三丁目・歯科医師会館
農業会館前
済生会病院正面
小鹿局前
競輪場入口
競輪場前
小鹿営業所
※ジョルダンの停車順をもとに作成。平日の運行です。
＠小鹿営業所

日本平線 41（新静岡〜英和学院大学池田山団地）
新静岡
静岡駅前
静岡ガスエネリアＳＲ静岡入口
八幡一丁目
八幡二丁目
小黒二丁目
小黒二丁目東
曲金三丁目・歯科医師会館
曲金六丁目
曲金七丁目
東静岡駅南口
池田橋
長沼大橋南
東豊田小学校前
西峯田
畑守稲荷前
動物園入口
英和学院大学池田山団地
※ジョルダンの停車順をもとに作成。行きは栄町を通らず、帰りは静岡ガスエネリアＳＲ静岡入口を通りません。
＠小鹿営業所

日本平線 42（新静岡〜日本平ロープウェイ）
新静岡
静岡駅前
静岡ガスエネリアＳＲ静岡入口
八幡一丁目
八幡二丁目
小黒二丁目
小黒二丁目東
曲金三丁目・歯科医師会館
曲金六丁目
曲金七丁目
東静岡駅南口
池田橋
長沼大橋南
東豊田小学校前
西峯田
畑守稲荷前
動物園入口
英和学院大学池田山団地
舞台芸術公園
日本平メモリアルガーデン
遊木の森入口
日本平ホテル
日本平夢テラス入口
日本平ロープウェイ
※ジョルダンの停車順をもとに作成。行きは栄町を通らず、帰りは静岡ガスエネリアＳＲ静岡入口を通りません。
＠小鹿営業所

日本平線（日本平動物園〜新静岡）
日本平動物園
動物園入口
畑守稲荷前
西峯田
東豊田小学校前
長沼大橋南
池田橋
東静岡駅南口
曲金七丁目
曲金六丁目
曲金三丁目・歯科医師会館
小黒二丁目東
小黒二丁目
八幡二丁目
八幡一丁目
栄町
静岡駅前
新静岡
※ジョルダンの停車順をもとに作成。土日祝の運行です。
＠小鹿営業所

美和大谷線 33（新静岡〜東大谷）
新静岡
静岡駅前
栄町
日の出町
下横田
曲金するが視覚総合特別支援学校
済生会病院前
小鹿局前
競輪場入口
小鹿
小鹿公民館前
堀ノ内
片山
片山南
宮川
井庄
大谷小学校前
洋光台入口
大谷
大谷中
東大谷
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線 34（新静岡〜静岡大学〜東大谷）
新静岡
静岡駅前
栄町
日の出町
下横田
曲金するが視覚総合特別支援学校
済生会病院前
小鹿局前
競輪場入口
小鹿
小鹿公民館前
堀ノ内
静大片山
静岡大学
静大宮川
井庄
大谷小学校前
洋光台入口
大谷
大谷中
東大谷
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線 35（静岡駅〜静岡大学）
静岡駅前
栄町
日の出町
下横田
曲金するが視覚総合特別支援学校
済生会病院前
小鹿局前
競輪場入口
小鹿
小鹿公民館前
堀ノ内
静大片山
静岡大学
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線 36（新静岡〜静岡大学〜ふじのくに地球環境史ミュージアム）
新静岡
静岡駅前
栄町
日の出町
下横田
曲金するが視覚総合特別支援学校
済生会病院前
小鹿局前
競輪場入口
小鹿
小鹿公民館前
堀ノ内
静大片山
静岡大学
静大宮川
井庄
駿河台公園
ふじのくに地球環境史ミュージアム
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線 37（新静岡〜ふじのくに地球環境史ミュージアム）
新静岡
静岡駅前
栄町
日の出町
下横田
曲金するが視覚総合特別支援学校
済生会病院前
小鹿局前
競輪場入口
小鹿
小鹿公民館前
堀ノ内
片山
片山南
宮川
井庄
駿河台公園
ふじのくに地球環境史ミュージアム
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線 126（静岡駅前〜奥長島）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居・浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
新伝馬
伊呂波町
秋山町
西ヶ谷運動場入口
下与北
安倍口新田
安倍口郵便局前
安倍口小学校前
中の郷
美和団地前
美和小学校入口
遠藤新田
美和中学校前
原田
八十岡入口
一面
舟沢
舟沢上
敷地
敷地上
湯権現
栗島
谷沢
口長島
奥長島
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線 126（静岡駅前〜奥長島・安倍口団地経由）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居・浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
新伝馬
伊呂波町
秋山町
西ヶ谷運動場入口
下与北
安倍口新田
安倍口郵便局前
安倍口小学校前
安倍口団地南
安倍口団地北
中の郷
美和団地前
美和小学校入口
遠藤新田
美和中学校前
原田
八十岡入口
一面
舟沢
舟沢上
敷地
敷地上
湯権現
栗島
谷沢
口長島
奥長島
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線 126（静岡駅前〜足久保団地・安倍口団地経由）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居・浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
新伝馬
伊呂波町
秋山町
西ヶ谷運動場入口
下与北
安倍口新田
安倍口郵便局前
安倍口小学校前
安倍口団地南
安倍口団地北
中の郷
美和団地前
美和小学校入口
遠藤新田
美和中学校前
足久保こども園
谷口北公園上
足久保団地
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

美和大谷線（静岡駅前〜美和団地）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居・浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
新伝馬
伊呂波町
秋山町
西ヶ谷運動場入口
下与北
安倍口新田
安倍口郵便局前
安倍口小学校前
中の郷
美和団地前
※ジョルダンの停車順をもとに作成。土日祝の運行です。
＠小鹿営業所 唐瀬営業所

県立病院高松線 20（静岡駅前〜登呂コープタウン）
静岡駅前
静岡ガスエネリアＳＲ静岡入口
八幡一丁目
八幡二丁目
小黒二丁目
小黒三丁目南部体育館入口
南郵便局ツインメッセ前
静岡総合庁舎前
有明町南
富士見台・駿河総合高校入口
登呂一丁目
登呂二丁目
登呂二丁目南
宮竹一丁目
高松公園
登呂コープタウン
※ジョルダンの停車順をもとに作成。静岡駅前→登呂は栄町を通らず、登呂→静岡駅前は静岡ガスエネリアＳＲ静岡入口を通りません。
＠小鹿営業所 唐瀬営業所

県立病院高松線 69（静岡駅前〜唐瀬営業所）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
西草深町
英和女学院前
長谷通り
アイセル21
安東二丁目
岩成不動
中電社宅前
城北高校前
柳新田上
柳新田辻
県営住宅前
北安東五丁目
城北二丁目
静岡中央高校入口
県立総合病院入口
若葉町
唐瀬入口
岳美
唐瀬営業所
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

県立病院高松線 70（静岡駅前〜県立総合病院）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
西草深町
英和女学院前
長谷通り
アイセル21
安東二丁目
岩成不動
中電社宅前
城北高校前
柳新田上
柳新田辻
県営住宅前
北安東五丁目
城北二丁目
静岡中央高校入口
県立総合病院入口
県立総合病院
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

県立病院高松線（唐瀬営業所〜登呂コープタウン）
唐瀬営業所
岳美
唐瀬入口
若葉町
県立総合病院入口
静岡中央高校入口
城北二丁目
北安東五丁目
県営住宅前
柳新田辻
柳新田上
城北高校前
中電社宅前
岩成不動
安東二丁目
アイセル21
長谷通り
英和女学院前
西草深町
中町
県庁・静岡市役所葵区役所前
新静岡
静岡駅前
静岡ガスエネリアＳＲ静岡入口
八幡一丁目
八幡二丁目
小黒二丁目
小黒三丁目南部体育館入口
南郵便局ツインメッセ前
静岡総合庁舎前
有明町南
富士見台・駿河総合高校入口
登呂一丁目
登呂二丁目
登呂二丁目南
宮竹一丁目
高松公園
登呂コープタウン
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

大浜麻機線 72（静岡駅前〜麻機北）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
西草深町
英和女学院前
長谷通り
安東一丁目
安東二丁目北
安東小学校前
記念碑前
大岩二丁目
北安東三丁目
池ヶ谷
唐瀬
時ヶ谷
小時
谷久保
草場
八津口
中村
麻機小学校
有永
有永上
羽高
北大門公園入口
麻機不動山
麻機ヶ丘
麻機北
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

大浜麻機線 72（静岡駅前〜麻機）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
西草深町
英和女学院前
長谷通り
安東一丁目
安東二丁目北
安東小学校前
記念碑前
大岩二丁目
北安東三丁目
池ヶ谷
唐瀬
時ヶ谷
小時
谷久保
草場
八津口
中村
麻機小学校
有永
有永上
羽高
麻機
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

大浜麻機線 26（静岡駅前〜大浜）
静岡駅前
静岡商工会議所前
馬渕一丁目
馬渕二丁目
馬渕三丁目
馬渕四丁目
見瀬Daiichi-TV入口
中村町上
中村町下
西脇ハローワーク静岡入口
西脇下
西島
大浜公園入口
大浜
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

石田街道線 11（登呂遺跡系統）
静岡駅南口
稲川町
大坪町
城南静岡高入口
中田三丁目ダイワハウス前
石田ＳＢＳ学苑入口
登呂遺跡入口
登呂遺跡
※ジョルダンの停車順をもとに作成。
＠小鹿営業所

石田街道線 12（敷地北経由）
静岡駅南口
稲川町
大坪町
城南静岡高入口
中田三丁目ダイワハウス前
石田ＳＢＳ学苑入口
登呂遺跡入口
登呂南
登呂コープタウン入口
下島北
敷地二丁目
敷地北
宮竹二丁目
宮竹児童公園前
高松公民館
高松
大谷
大谷中
東大谷
※ジョルダンの停車順をもとに作成。
＠小鹿営業所

石田街道線 15（下島経由）
静岡駅南口
稲川町
大坪町
城南静岡高入口
中田三丁目ダイワハウス前
石田ＳＢＳ学苑入口
登呂遺跡入口
登呂南
登呂コープタウン入口
下島北
下島
浜敷地
宮竹
高松公民館
高松
大谷
大谷中
東大谷
※ジョルダンの停車順をもとに作成。
＠小鹿営業所

石田街道線 14（東大谷〜久能山下）
東大谷
大谷境
西平松
中平松
青沢
久能こども園前
古宿
久能学校前
安居
久能局前
久能山下
※ジョルダンの停車順をもとに作成。
＠小鹿営業所

石田街道線（静岡駅南口〜高松）
静岡駅南口
稲川町
大坪町
城南静岡高入口
中田三丁目ダイワハウス前
石田ＳＢＳ学苑入口
登呂遺跡入口
登呂南
登呂コープタウン入口
下島北
下島
浜敷地
宮竹
高松公民館
高松
※ジョルダンの停車順をもとに作成。平日の運行です。
＠小鹿営業所

中原池ヶ谷線 71（静岡駅前〜唐瀬営業所）
静岡駅前
新静岡
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居・浅間神社入口
浅間神社
丸山町
大岩本町
臨済寺前
大岩町
大在家
大岩北
平ヶ谷
池ヶ谷
唐瀬
唐瀬入口
岳美
唐瀬営業所
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

中原池ヶ谷線 27（静岡駅前〜徳洲会病院）
静岡駅前
静岡商工会議所前
馬渕一丁目
馬渕二丁目
馬渕三丁目
新川
中原町
寿町
西中原
緑が丘
中野新田
大里中学校
静岡ＩＣ入口
中島上公民館前
中島団地前
中島
南安倍川橋
下川原五丁目
マイホームセンター前
下川原団地
徳洲会病院
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

中原池ヶ谷線（唐瀬営業所〜徳洲会病院・八千代経由）
唐瀬営業所
岳美
唐瀬入口
唐瀬
池ヶ谷
平ヶ谷
大岩北
大在家
大岩町
臨済寺前
大岩本町
丸山町
浅間神社
赤鳥居・浅間神社入口
八千代町
中町
県庁・静岡市役所葵区役所前
新静岡
静岡駅前
静岡商工会議所前
馬渕一丁目
馬渕二丁目
馬渕三丁目
新川
中原町
寿町
西中原
緑が丘
中野新田
大里中学校
静岡ＩＣ入口
中島上公民館前
中島団地前
中島
南安倍川橋
下川原五丁目
マイホームセンター前
下川原団地
徳洲会病院
※ジョルダンの停車順をもとに作成。
＠小鹿営業所 唐瀬営業所

こども病院線 67（静岡駅前〜静岡神経医療センター）
静岡駅前
新静岡
市民文化会館入口
水落町もくせい会館入口・常葉大学静岡水落キャンパス前
横内町静岡学園入口
巴町
銭座町
三松
沓谷三丁目
沓谷四丁目
千代田小学校前
沓谷五丁目
千代田六丁目
千代田七丁目・東部体育館入口
下足洗
こども病院
静岡神経医療センター
※唐瀬営業所の路線図の写真から作成。千代田七丁目・東部体育館入口は、1つの停留所として扱っています（要確認）。
＠唐瀬営業所

こども病院線 67（静岡駅前〜流通センター入口）
静岡駅前
新静岡
市民文化会館入口
水落町もくせい会館入口・常葉大学静岡水落キャンパス前
横内町静岡学園入口
巴町
銭座町
三松
沓谷三丁目
沓谷四丁目
千代田小学校前
沓谷五丁目
千代田六丁目
千代田七丁目・東部体育館入口
下足洗
流通センター入口
※唐瀬営業所の路線図の写真から作成。下足洗の先で分かれる支線です。
＠唐瀬営業所

上足洗線 75（静岡駅前〜唐瀬営業所）
静岡駅前
新静岡
市民文化会館入口
水落町もくせい会館入口・常葉大学静岡水落キャンパス前
横内町静岡学園入口
巴町
銭座町
千代田三丁目
上足洗
上足洗北
柳新田西
柳新田北
北安東四丁目・静岡社会健康医学大学院大学前
北安東四丁目西
北安東保育園前
県立総合病院
若葉町
唐瀬営業所
※唐瀬営業所の路線図の写真から作成。終盤（北安東保育園前・県立総合病院・若葉町）の順序は要確認。
＠唐瀬営業所

唐瀬線 77（静岡駅前〜唐瀬営業所）
静岡駅前
新静岡
市民文化会館入口
水落町もくせい会館入口・常葉大学静岡水落キャンパス前
横内町静岡学園入口
巴町
銭座町
三松
市立高校前
千代田四丁目
竜南二丁目
柳新田
北安東五丁目
城北二丁目
静岡中央高校入口
県立総合病院入口
若葉町
唐瀬入口
岳美
唐瀬営業所
※唐瀬営業所の路線図の写真から作成。
＠唐瀬営業所

唐瀬線 78（静岡駅前〜県立総合病院〜唐瀬営業所）
静岡駅前
新静岡
市民文化会館入口
水落町もくせい会館入口・常葉大学静岡水落キャンパス前
横内町静岡学園入口
巴町
銭座町
三松
市立高校前
千代田四丁目
竜南二丁目
柳新田
北安東五丁目
城北二丁目
静岡中央高校入口
県立総合病院入口
県立総合病院
若葉町
唐瀬入口
岳美
唐瀬営業所
※唐瀬営業所の路線図の写真から作成。県立総合病院を経由する便です。経由の順序は要確認。
＠唐瀬営業所

安倍線 111（静岡駅前〜梅ヶ島温泉）
静岡駅前
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
籠上北秀英予備校前
昭府一丁目
昭府二丁目
松富団地入口
御新田
御新田上
松富
賤機南小学校前
中部運転免許センター入口
福田ヶ谷新田
福田ヶ谷
福田ヶ谷上
下
下公民館前
鯨ヶ池入口
桜峠入口
門屋南
門屋
牛妻笹子
牛妻原
賤機中小学校前
牛妻
牛妻坂下
油山
松野小学校前
松野
十二天
津渡野
郷島宮前
郷島
野田平入口
俵沢
六番
相渕
蕨野
蕨野温泉
八重沢
横山
真富士の里
平野原
平野
大河内学校前
中平
北沢
下渡
上渡
渡本
大和田
藤代入口
珠数落
入島
湯の森
六郎木
関の沢入口
本村
孫佐島
大野木
草木
赤水
池尻橋
新田
新田温泉黄金の湯
安倍大滝入口
梅ヶ島温泉入口
梅ヶ島温泉
※唐瀬営業所の路線図の写真から作成。※赤鳥居浅間神社入口は、地図上で2つの文字に分かれて見えますが、1つの停留所として扱っています。松野〜十二天付近の順序も要確認。
＠唐瀬営業所

安倍線 111（静岡駅前〜横沢）
静岡駅前
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
籠上北秀英予備校前
昭府一丁目
昭府二丁目
松富団地入口
御新田
御新田上
松富
賤機南小学校前
中部運転免許センター入口
福田ヶ谷新田
福田ヶ谷
福田ヶ谷上
下
下公民館前
鯨ヶ池入口
桜峠入口
門屋南
門屋
牛妻笹子
牛妻原
賤機中小学校前
牛妻
牛妻坂下
油山
松野小学校前
松野
十二天
津渡野
郷島宮前
郷島
野田平入口
俵沢
六番
中沢
中沢上
金久保
桂山原
長光寺前
桂山
唯間
玉川診療所
上助
上助上
下平瀬
上平瀬
川島下
川島
大和
内匠
下腰越
腰越
大沢入口
集会所前
横沢
※唐瀬営業所の路線図の写真から作成。※赤鳥居浅間神社入口は、地図上で2つの文字に分かれて見えますが、1つの停留所として扱っています。松野〜十二天付近の順序も要確認。
＠唐瀬営業所

安倍線 111（静岡駅前〜上落合）
静岡駅前
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
籠上北秀英予備校前
昭府一丁目
昭府二丁目
松富団地入口
御新田
御新田上
松富
賤機南小学校前
中部運転免許センター入口
福田ヶ谷新田
福田ヶ谷
福田ヶ谷上
下
下公民館前
鯨ヶ池入口
桜峠入口
門屋南
門屋
牛妻笹子
牛妻原
賤機中小学校前
牛妻
牛妻坂下
油山
松野小学校前
松野
十二天
津渡野
郷島宮前
郷島
野田平入口
俵沢
六番
中沢
中沢上
金久保
桂山原
長光寺前
桂山
唯間
玉川診療所
上助
玉川中学校前
奥の原
奥の原上
森腰
森腰上
長熊
長熊上
郷土
奥池ヶ谷
柿島
長妻田
粟駒
油野
上落合
※唐瀬営業所の路線図の写真から作成。※赤鳥居浅間神社入口は、地図上で2つの文字に分かれて見えますが、1つの停留所として扱っています。松野〜十二天付近の順序も要確認。
＠唐瀬営業所

安倍線 109（麻機系統）
静岡駅前
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
籠上北秀英予備校前
昭府一丁目
昭府二丁目
松富団地入口
御新田
御新田上
松富
賤機南小学校前
中部運転免許センター入口
福田ヶ谷新田
福田ヶ谷
福田ヶ谷上
下
下公民館前
鯨ヶ池入口
桜峠入口
老人福祉センター
鯨ヶ池
麻機
※唐瀬営業所の路線図の写真から作成。老人福祉センターと鯨ヶ池の順序は要確認。
＠唐瀬営業所

安倍線 110（運転免許センター系統）
静岡駅前
県庁・静岡市役所葵区役所前
中町
八千代町
赤鳥居浅間神社入口
材木町
井の宮局前
妙見下
籠上
籠上中
籠上北秀英予備校前
昭府一丁目
昭府二丁目
松富団地入口
御新田
御新田上
松富
松富北
北部体育館入口
中部運転免許センター
※唐瀬営業所の路線図の写真から作成。分岐から先の順序は要確認。
＠唐瀬営業所`;
const COL=['#d9482b','#1e6fe6','#0a9b4f','#c020d0','#e08a00','#008b8b','#7a5230','#6b46c1'];
const cm={};const colorOf=n=>{const l=n.split(/\s/)[0];if(!(l in cm))cm[l]=COL[Object.keys(cm).length%COL.length];return cm[l]};
const parse=t=>t.split(/\n\s*\n/).map(b=>b.split('\n').map(x=>x.trim()).filter(Boolean)).map(a=>({name:a[0],stops:a.slice(1).filter(x=>x[0]!=='※'&&x[0]!=='＠'),note:a.slice(1).filter(x=>x[0]==='※').join(' '),dep:a.slice(1).filter(x=>x[0]==='＠').join(' ').replace(/＠/g,'').split(/\s+/).filter(Boolean),color:colorOf(a[0])})).filter(r=>r.stops.length>=2);
const toText=r=>r.map(x=>x.name+'\n'+x.stops.join('\n')+(x.note?'\n'+x.note:'')+(x.dep.length?'\n＠'+x.dep.join(' '):'')).join('\n\n');
const esc=t=>String(t).replace(/[&<>]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;'}[c]));
// ---- 保存（localStorage が使えない環境でも落ちないように、メモリにも持つ）----
const mem={};
const store={get(k,d){try{const v=localStorage.getItem(k);if(v!=null)return JSON.parse(v)}catch(e){}return k in mem?mem[k]:d},
 set(k,v){mem[k]=v;try{localStorage.setItem(k,JSON.stringify(v));return true}catch(e){return false}}};
const SK='shizuoka_cards_stats_v1',PK='shizuoka_cards_prefs_v1';
let S=store.get(SK,null)||{n:0,ok:0,days:{},stops:{},routes:{}},P=store.get(PK,{});
const today=(d=new Date())=>d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0')+'-'+String(d.getDate()).padStart(2,'0');
// 1回答を記録する（成績・苦手の判定に使う）
function rec(rt,stop,ok){const k=rt+'|'+stop,dk=today();S.n++;if(ok)S.ok++;
 const d=S.days[dk]=S.days[dk]||[0,0];d[0]++;if(ok)d[1]++;
 const s=S.stops[k]=S.stops[k]||[0,0,1];if(ok)s[0]++;else s[1]++;s[2]=ok?1:0;
 const r=S.routes[rt]=S.routes[rt]||[0,0,0];r[0]++;if(ok)r[1]++;r[2]=Date.now();
 store.set(SK,S)}
// 苦手＝間違いがあり、(正解より間違いが多い か 直近が不正解)
const isWeak=v=>!!v&&v[1]>0&&(v[1]>v[0]||v[2]===0);
const weakIdx=r=>r.stops.map((s,i)=>isWeak(S.stops[r.name+'|'+s])?i:-1).filter(i=>i>=0);
let routes=[];try{const s=localStorage.getItem(K);if(s)routes=parse(s)}catch(e){}
if(!routes.length)routes=parse(SAMPLE);
let hid=new Set(),st={},p=-1,sc=[0,0];
const R=()=>routes[+$('rs').value]||routes[0];
const norm=t=>t.normalize('NFKC').replace(/[\s・･･]/g,'').toLowerCase();
const vis=r=>!$('dp').value||r.dep.includes($('dp').value);
function fillSel(){const d=$('dp'),cur=d.value,ds=[...new Set(routes.flatMap(r=>r.dep))];d.innerHTML='<option value="">すべての営業所</option>'+ds.map(x=>`<option>${x}</option>`).join('');d.value=ds.includes(cur)?cur:'';
 $('rs').innerHTML=routes.map((r,i)=>vis(r)?`<option value="${i}">${r.name}（${r.stops.length}）</option>`:'').join('')}
function reset(){const r=R(),n=r.stops.length,m=$('md').value,hv=$('hp').value,q=hv==='weak'?1:+hv;hid=new Set();st={};sc=[0,0];p=-1;let msg='';
 if(m!=='see'){if(hv==='weak'){weakIdx(r).forEach(i=>hid.add(i));if(!hid.size){msg='この路線の苦手なバス停はまだありません。全部隠して出題します。';r.stops.forEach((_,i)=>hid.add(i))}}
  else r.stops.forEach((_,i)=>{if(q===1||Math.random()<q)hid.add(i)})}
 if(m!=='see'&&!hid.size)hid.add(0);
 if(m==='type'){p=first()}$('qa').style.display=m==='type'?'':'none';$('qr').textContent=msg;savePrefs();render();ask()}
const first=()=>{for(let i=0;i<R().stops.length;i++)if(hid.has(i)&&!st[i])return i;return -1};
let FS=18;try{FS=+(localStorage.getItem('shizuoka_cards_fs')||18)}catch(e){}
function render(){const r=R(),dg=$('dg'),W=Math.max(300,dg.clientWidth-8),per=Math.max(3,Math.floor(W/(FS*3.3+10))),cw=(100/per)+'%';dg.style.setProperty('--fs',FS+'px');document.querySelectorAll('.fz').forEach(b=>b.className='fz'+(+b.dataset.f===FS?' on':''));dg.innerHTML='';
 for(let i=0,ri=0;i<r.stops.length;i+=per,ri++){const row=document.createElement('div');row.className='rw '+(ri%2?'l':'r')+(i+per<r.stops.length?' t':'');row.style.setProperty('--c',r.color);row.style.setProperty('--w',cw);
  for(let k=i;k<Math.min(i+per,r.stops.length);k++){const c=document.createElement('div');c.className='c'+(k===p?' cur':'');
   const d=document.createElement('div');d.className='dot';d.textContent=k+1;c.appendChild(d);
   const l=document.createElement('span');const s=r.stops[k];
   if(hid.has(k)&&!st[k]){l.className='pk';l.style.height=(s.length*1.3+.8)+'em'}else{l.className='lb'+(st[k]==='g'?' good':st[k]==='b'?' bad':'');l.textContent=s;l.style.height=(s.length*1.08+.4)+'em'}
   c.appendChild(l);c.onclick=()=>tap(k);row.appendChild(c)}
  dg.appendChild(row)}
 $('inf').textContent=`${r.stops.length} 停留所　始点：${r.stops[0]}　終点：${r.stops[r.stops.length-1]}`+(r.note?'　'+r.note:'')}
function tap(k){const m=$('md').value;
 if(m==='peel'){if(hid.has(k)&&!st[k])st[k]='v';else if(hid.has(k))delete st[k];else hid.add(k);render()}
 else if(m==='type'&&hid.has(k)&&!st[k]){p=k;render();ask()}}
function ask(){if($('md').value!=='type')return;const r=R();
 if(p<0||st[p]){p=first()}
 if(p<0){$('qt').innerHTML=`<b>終了：${sc[0]} / ${sc[1]} 正解</b>`;$('qi').value='';render();return}
 $('qt').innerHTML=`<b>${p+1}番目</b>のバス停は？　<span class="hint">（前：${p>0?r.stops[p-1]:'始点'}）</span>`;render();$('qi').focus()}
function ans(skip){if($('md').value!=='type'||p<0)return;const s=R().stops[p],ok=!skip&&norm($('qi').value)===norm(s);
 st[p]=ok?'g':'b';rec(R().name,s,ok);sc[1]++;if(ok)sc[0]++;$('qr').innerHTML=ok?'<span class="ok">⭕ 正解！</span>':`<span class="ng">${skip?'答え':'❌ 正解は'}</span>：${s}`;$('qi').value='';p=first();ask()}
$('qb').onclick=()=>ans(false);$('qk').onclick=()=>ans(true);$('qi').addEventListener('keydown',e=>{if(e.key==='Enter')ans(false)});
$('dp').onchange=()=>{fillSel();reset();ssc=[0,0];$('ss').textContent=''};$('rs').onchange=$('md').onchange=$('hp').onchange=$('rh').onclick=reset;
$('sa').onclick=()=>{hid=new Set();st={};p=-1;$('qt').textContent='';render()};
const TABS={tV:'vw',tD:'dt',tS:'sy',tR:'rp'};
Object.keys(TABS).forEach(k=>$(k).onclick=()=>{Object.entries(TABS).forEach(([b,p])=>{$(p).style.display=b===k?'':'none';$(b).className=b===k?'on':''});if(k==='tV')render();if(k==='tD')$('ta').value=toText(routes);if(k==='tR')renderStats();if(k==='tS'&&!sq&&!$('sr').textContent)snext()});
const info=r=>{const m=r.name.match(/^(\S+)\s+(\d+)(?:（(.*)）)?/);return m?{line:m[1],num:m[2],sec:m[3]||''}:null};
let sq=null,ssc=[0,0];
function snext(){const pool=routes.filter(vis).map(info).filter(Boolean);if(!pool.length){$('sq').textContent='「路線名 番号（区間）」の形式の路線がありません';return}
 sq=pool[Math.floor(Math.random()*pool.length)];const m=$('sm').value;
 $('sq').innerHTML=m==='n2l'?`系統 <b>${sq.num}</b>${sq.sec?'（'+esc(sq.sec)+'）':''} の路線名は？`:`<b>${esc(sq.line)}</b>${sq.sec?'（'+esc(sq.sec)+'）':''} の系統番号は？`;
 $('si').value='';$('sr').textContent='';$('si').focus()}
function sans(skip){if(!sq)return;const m=$('sm').value,v=$('si').value,ok=!skip&&(m==='n2l'?norm(v)===norm(sq.line):norm(v)===sq.num);ssc[1]++;if(ok)ssc[0]++;rec('系統',m==='n2l'?sq.num:sq.line,ok);
 $('sr').innerHTML=ok?'<span class="ok">⭕ 正解！</span>':`<span class="ng">${skip?'答え':'❌ 正解は'}</span>：${esc(m==='n2l'?sq.line:sq.num)}`;$('ss').textContent=`${ssc[0]} / ${ssc[1]}`;sq=null}
$('sgo').onclick=snext;$('sb').onclick=()=>sans(false);$('sk').onclick=()=>sans(true);$('sm').onchange=()=>{ssc=[0,0];$('ss').textContent='';snext()};
$('si').addEventListener('keydown',e=>{if(e.key==='Enter')sans(false)});
$('sv').onclick=()=>{const r=parse($('ta').value);if(!r.length){alert('路線名とバス停2つ以上が必要です');return}routes=r;try{localStorage.setItem(K,toText(r))}catch(e){}fillSel();$('tV').click();reset()};
$('cp').onclick=()=>{const ta=$('ta');ta.select();ta.setSelectionRange(0,999999);let ok=false;try{ok=document.execCommand('copy')}catch(e){}if(!ok&&navigator.clipboard)navigator.clipboard.writeText(ta.value).catch(()=>{});$('cp').textContent='コピーしました';setTimeout(()=>$('cp').textContent='全部コピー',1500)};
$('rst').onclick=()=>{if(confirm('登録した路線データを捨てて、最初の状態に戻します。よろしいですか？')){routes=parse(SAMPLE);try{localStorage.setItem(K,toText(routes))}catch(e){}$('ta').value=toText(routes);fillSel();reset()}};
document.querySelectorAll('.fz').forEach(b=>b.onclick=()=>{FS=+b.dataset.f;try{localStorage.setItem('shizuoka_cards_fs',FS)}catch(e){}render()});try{localStorage.setItem('__t','1');localStorage.removeItem('__t')}catch(e){const w=document.createElement('div');w.className='hint';w.style.color='var(--ng)';w.textContent='このブラウザでは、編集内容と文字の大きさを保存できません（見る・問題を解くことはできます）。';document.body.insertBefore(w,document.body.children[1])}
// ---- 成績画面 ----
function renderStats(){const rp=$('rp'),pct=(a,b)=>b?Math.round(a*100/b)+'%':'―',t=S.days[today()]||[0,0];
 let streak=0;for(let i=0;i<400;i++){const d=new Date();d.setDate(d.getDate()-i);const v=S.days[today(d)];if(v&&v[0])streak++;else if(i>0)break}
 const rts=Object.entries(S.routes).sort((a,b)=>b[1][2]-a[1][2]).slice(0,10);
 const wk=Object.entries(S.stops).filter(([k,v])=>isWeak(v)).sort((a,b)=>b[1][1]-a[1][1]).slice(0,20);
 rp.innerHTML='<div class="card"><div class="stat"><div><b>'+S.n+'</b>回答</div><div><b>'+pct(S.ok,S.n)+'</b>正解率</div><div><b>'+streak+'日</b>連続</div></div>'+
  '<p class="hint">今日：'+t[0]+'問中 '+t[1]+'問正解</p></div>'+
  '<div class="card"><b>最近の路線</b>'+(rts.length?rts.map(([n,v])=>'<div class="wk"><span>'+esc(n)+'</span><span>'+pct(v[1],v[0])+'（'+v[0]+'問）</span></div>').join(''):'<p class="hint">まだ記録がありません。「学習」の「順番に入力」で答えると、ここに残ります。</p>')+'</div>'+
  '<div class="card"><b>苦手なバス停</b>'+(wk.length?wk.map(([k,v],i)=>{const [rn,sn]=k.split('|');return '<div class="wk"><span>'+esc(sn)+'<br><span class="hint">'+esc(rn)+'　×'+v[1]+'</span></span>'+(rn==='系統'?'':'<button data-i="'+i+'">練習</button>')+'</div>'}).join(''):'<p class="hint">苦手なバス停はまだありません。</p>')+'</div>'+
  '<div class="row"><button id="clr">成績を消す</button></div>';
 rp.querySelectorAll('button[data-i]').forEach(b=>b.onclick=()=>{const rn=wk[+b.dataset.i][0].split('|')[0],i=routes.findIndex(r=>r.name===rn);if(i<0)return;
  $('dp').value='';fillSel();$('rs').value=i;$('md').value='type';$('hp').value='weak';$('tV').click();reset()});
 $('clr').onclick=()=>{if(confirm('成績と苦手の記録をすべて消します。よろしいですか？')){S={n:0,ok:0,days:{},stops:{},routes:{}};store.set(SK,S);renderStats()}}}
// ---- 設定（前回の選択を覚える）----
function savePrefs(){try{P={dp:$('dp').value,rs:(R()||{}).name,md:$('md').value,hp:$('hp').value};store.set(PK,P)}catch(e){}}
function restorePrefs(){$('md').value='peel';try{const d=$('dp');if(P.dp&&[...d.options].some(o=>o.value===P.dp)){d.value=P.dp;fillSel()}
 const i=routes.findIndex(r=>r.name===P.rs);if(i>=0&&vis(routes[i]))$('rs').value=i;
 if(['see','peel','type'].includes(P.md))$('md').value=P.md;if(['1','.5','weak'].includes(P.hp))$('hp').value=P.hp}catch(e){}}
// ---- オフライン用（http/https で開いた時だけ。ファイルで開いた時は何もしない）----
if('serviceWorker' in navigator&&/^https?:$/.test(location.protocol))navigator.serviceWorker.register('sw.js').catch(()=>{});
addEventListener('resize',render);fillSel();restorePrefs();reset();{const f=document.getElementById('fallback');if(f)f.remove()}
</script></body></html>
