# ASCII to Unicode Equivalents

This is a stupid script I wrote to convert ASCII to ⒶⓈⒸⒾⒾ. The
motivation was to have a simple command line tool that convert a basic
string to to a few different variations of based on unicode
variants. E.g.:


```
$ ./convert The quick brown fox jumps over the lazy dog
The quick brown fox jumps over the lazy dog
Ⓣⓗⓔ ⓠⓤⓘⓒⓚ ⓑⓡⓞⓦⓝ ⓕⓞⓧ ⓙⓤⓜⓟⓢ ⓞⓥⓔⓡ ⓣⓗⓔ ⓛⓐⓩⓨ ⓓⓞⓖ
🅣🅗🅔 🅠🅤🅘🅒🅚 🅑🅡🅞🅦🅝 🅕🅞🅧 🅙🅤🅜🅟🅢 🅞🅥🅔🅡 🅣🅗🅔 🅛🅐🅩🅨 🅓🅞🅖
𝐓𝐡𝐞 𝐪𝐮𝐢𝐜𝐤 𝐛𝐫𝐨𝐰𝐧 𝐟𝐨𝐱 𝐣𝐮𝐦𝐩𝐬 𝐨𝐯𝐞𝐫 𝐭𝐡𝐞 𝐥𝐚𝐳𝐲 𝐝𝐨𝐠
𝕿𝖍𝖊 𝖖𝖚𝖎𝖈𝖐 𝖇𝖗𝖔𝖜𝖓 𝖋𝖔𝖝 𝖏𝖚𝖒𝖕𝖘 𝖔𝖛𝖊𝖗 𝖙𝖍𝖊 𝖑𝖆𝖟𝖞 𝖉𝖔𝖌
𝑻𝒉𝒆 𝒒𝒖𝒊𝒄𝒌 𝒃𝒓𝒐𝒘𝒏 𝒇𝒐𝒙 𝒋𝒖𝒎𝒑𝒔 𝒐𝒗𝒆𝒓 𝒕𝒉𝒆 𝒍𝒂𝒛𝒚 𝒅𝒐𝒈
𝓣𝓱𝓮 𝓺𝓾𝓲𝓬𝓴 𝓫𝓻𝓸𝔀𝓷 𝓯𝓸𝔁 𝓳𝓾𝓶𝓹𝓼 𝓸𝓿𝓮𝓻 𝓽𝓱𝓮 𝓵𝓪𝔃𝔂 𝓭𝓸𝓰
𝕋𝕙𝕖 𝕢𝕦𝕚𝕔𝕜 𝕓𝕣𝕠𝕨𝕟 𝕗𝕠𝕩 𝕛𝕦𝕞𝕡𝕤 𝕠𝕧𝕖𝕣 𝕥𝕙𝕖 𝕝𝕒𝕫𝕪 𝕕𝕠𝕘
𝚃𝚑𝚎 𝚚𝚞𝚒𝚌𝚔 𝚋𝚛𝚘𝚠𝚗 𝚏𝚘𝚡 𝚓𝚞𝚖𝚙𝚜 𝚘𝚟𝚎𝚛 𝚝𝚑𝚎 𝚕𝚊𝚣𝚢 𝚍𝚘𝚐
𝖳𝗁𝖾 𝗊𝗎𝗂𝖼𝗄 𝖻𝗋𝗈𝗐𝗇 𝖿𝗈𝗑 𝗃𝗎𝗆𝗉𝗌 𝗈𝗏𝖾𝗋 𝗍𝗁𝖾 𝗅𝖺𝗓𝗒 𝖽𝗈𝗀
𝗧𝗵𝗲 𝗾𝘂𝗶𝗰𝗸 𝗯𝗿𝗼𝘄𝗻 𝗳𝗼𝘅 𝗷𝘂𝗺𝗽𝘀 𝗼𝘃𝗲𝗿 𝘁𝗵𝗲 𝗹𝗮𝘇𝘆 𝗱𝗼𝗴
𝙏𝙝𝙚 𝙦𝙪𝙞𝙘𝙠 𝙗𝙧𝙤𝙬𝙣 𝙛𝙤𝙭 𝙟𝙪𝙢𝙥𝙨 𝙤𝙫𝙚𝙧 𝙩𝙝𝙚 𝙡𝙖𝙯𝙮 𝙙𝙤𝙜
𝘛𝘩𝘦 𝘲𝘶𝘪𝘤𝘬 𝘣𝘳𝘰𝘸𝘯 𝘧𝘰𝘹 𝘫𝘶𝘮𝘱𝘴 𝘰𝘷𝘦𝘳 𝘵𝘩𝘦 𝘭𝘢𝘻𝘺 𝘥𝘰𝘨
⒯⒣⒠ ⒬⒰⒤⒞⒦ ⒝⒭⒪⒲⒩ ⒡⒪⒳ ⒥⒰⒨⒫⒮ ⒪⒱⒠⒭ ⒯⒣⒠ ⒧⒜⒵⒴ ⒟⒪⒢
🅃🄷🄴 🅀🅄🄸🄲🄺 🄱🅁🄾🅆🄽 🄵🄾🅇 🄹🅄🄼🄿🅂 🄾🅅🄴🅁 🅃🄷🄴 🄻🄰🅉🅈 🄳🄾🄶
🆃🅷🅴 🆀🆄🅸🅲🅺 🅱🆁🅾🆆🅽 🅵🅾🆇 🅹🆄🅼🅿🆂 🅾🆅🅴🆁 🆃🅷🅴 🅻🅰🆉🆈 🅳🅾🅶
Thé qúíćḱ bŕőẃń főx júḿṕś ővéŕ thé ĺáźӳ dőǵ
ｲん乇 quﾉcズ 乃尺ow刀 ｷoﾒ ﾌuﾶｱ丂 o√乇尺 ｲん乇 ﾚﾑ乙ﾘ dog
Շɦﻉ ۹પٱƈᛕ ๒ɼѻฝก िѻซ ﻝપ๓ρร ѻ۷ﻉɼ Շɦﻉ ɭคչץ ɗѻﻭ
тнє ۹υι¢к вяσωη ƒσχ נυмρѕ σνєя тнє ℓαչу ∂σﻭ
Շђє ợยเςк ๒г๏ฬภ Ŧ๏א ןย๓קร ๏שєг Շђє ɭคչץ ๔๏ﻮ
ГЂэ qціск ъѓоши fох јцмрѕ оvэѓ тЂэ lаzЎ ↁоБ
ፕዘቿ ዒሁጎርጕ ጌዪዐሠክ ቻዐሸ ጋሁጠየነ ዐሀቿዪ ፕዘቿ ረልጊሃ ዕዐኗ
𝔗𝔥𝔢 𝔮𝔲𝔦𝔠𝔨 𝔟𝔯𝔬𝔴𝔫 𝔣𝔬𝔵 𝔧𝔲𝔪𝔭𝔰 𝔬𝔳𝔢𝔯 𝔱𝔥𝔢 𝔩𝔞𝔷𝔶 𝔡𝔬𝔤
Ṫḧë qüïċḳ ḅṛöẅṅ ḟöẍ jüṁṗṡ öṿëṛ ẗḧë ḷäżÿ ḋöġ
ᴛʜᴇ qᴜɪᴄᴋ ʙʀᴏᴡɴ ꜰᴏx ᴊᴜᴍᴩꜱ ᴏᴠᴇʀ ᴛʜᴇ ʟᴀᴢy ᴅᴏɢ
Ŧħɇ ꝗᵾɨȼꝁ ƀɍøwn føx ɉᵾmᵽs øvɇɍ ŧħɇ łȺƶɏ đøǥ
ᵀʰᵉ qᵘⁱᶜᵏ ᵇʳᵒʷⁿ ᶠᵒˣ ʲᵘᵐᵖˢ ᵒᵛᵉʳ ᵗʰᵉ ˡᵃᶻʸ ᵈᵒᵍ
ʇɥǝ bnıɔʞ qɹoʍu ɟox ɾnɯds oʌǝɹ ʇɥǝ ןɐzʎ poƃ
THɘ pUiↄk dᴙowᴎ ꟻox jUmqꙅ ovɘᴙ THɘ lAzY bog
```

The script is just a single go file. In order to use, ~go build
convert.go~ and then run it with input that you'd like to try
transacting into different characters.

