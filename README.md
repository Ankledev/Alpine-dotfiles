# My collection of wallpapers and configs for quickshell

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8e8b2f85-2f6d-4f09-98e1-3495b167e80c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dce32fca-ea6c-404d-bf78-53851e10a527" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a5a7fb75-2953-46c4-a940-6c696b4b2c57" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/89fc5613-f919-491d-b474-36d1a1331695" />

###Note these configs and wallpapers are not all mine, original creator for the quickshell was "Shaiqie" and wallpapers were found from a multitude of sources.

To install the dotfiles 

```
install git
alpine : apk add git
arch : pacman -S git / yay -S git / paru -S git
gentoo : emerge -q git

git clone https://github.com/ankledev/Alpine-dotfiles
then move over the configs you need. 
note you also need quickshell for the bar and utils.
```

## My browser setup.
i use helium browser (helium.computer) and my prefered web extensions are mtab, nav, ublock origin

My mtab config:

<img width="1833" height="922" alt="image" src="https://github.com/user-attachments/assets/89ab7a38-5c5a-400c-9f87-d645cace72ae" />

```
MTAB_SAVE_FORMAT_v1.12.5_{"options":{"showOptionsButton":false},"user":{"name":"user"},"title":{"defaultTitle":"New tab","dynamic":{"enabled":true},"effect":"none","typewriter":{"speed":500,"remainCount":1},"faviconType":"default"},"message":{"enabled":true,"font":{"type":"default","custom":""},"textColor":"#ffffff","textSize":2.75,"type":"custom","customText":"\\hh:\\mm | \\d$-\\m$-\\yyyy","weather":{"unitsType":"f"}},"wallpaper":{"type":"file-upload","enabled":true,"frequency":"constant","urls":[],"filters":{"brightness":"1","blur":"0px"},"solidColors":["#171717"]},"ui":{"style":"glass","glassColor":"#19191950","blurStrength":"32px","foregroundColor":"#262626","highlightColor":"#ffffff20","cornerStyle":"round","customCSS":"/* input custom css... */"},"animations":{"enabled":true,"bookmarkTiming":"left","initialType":"animate-down-bouncy","searchType":"animate-page-shrink","bookmarkType":"animate-page-up"},"search":{"enabled":true,"engine":"duckduckgo","useCustomEngine":false,"customEngineURL":"","buttons":{"clear":true,"search":true},"recognizeLinks":true,"suggestions":true,"assist":{"date":true,"math":true,"definitions":true,"conversions":true,"passwordGenerator":true},"placeholderText":"search...","bookmarkPlaceholderText":"find bookmark...","focusedBorderColor":"#0ea5e9","font":{"type":"default","custom":""},"textColor":"#ffffff","placeholderTextColor":"#a1a1aa","searchIconColor":"#2FA5FF","bookmarkIconColor":"#2FA5FF","selectIconColor":"#2FA5FF","linkTextColor":"#0ea5e9"},"hotkeys":{"enabled":true,"activationKey":"<space>","closePageKey":"x","searchBookmarksKey":"b"},"bookmarks":{"type":"user-defined","showBookmarkNames":true,"numberKeys":true,"enablePagination":false,"maxBookmarkRowsPerPage":2,"lineOrientation":"top","defaultIconColor":"#ffffff","defaultFolderIconType":"ri-folder-open-fill","userDefinedCols":4,"userDefined":[{"color":"#8b5cf6","contents":[{"color":"#6366f1","iconColor":"#ffffff","iconType":"ri-github-fill","name":"github","type":"bookmark","url":"https://github.com/ankledev"},{"color":"#ffffff","iconColor":"#ffffff","iconType":"ri-openai-fill","name":"chatgpt","type":"bookmark","url":"https://chatgpt.com"},{"color":"#14b8a6","iconColor":"#ffffff","iconType":"ri-global-fill","name":"localhost","type":"bookmark","url":"http://localhost:3000"},{"color":"#f97316","iconColor":"#ffffff","iconType":"ri-newspaper-fill","name":"hackernews","type":"bookmark","url":"https://news.ycombinator.com/"},{"color":"#f97316","iconColor":"#ffffff","iconType":"ri-cloud-line","name":"cloudflare","type":"bookmark","url":"https://dash.cloudflare.com"},{"color":"#ffffff","iconColor":"#ffffff","iconType":"ri-vercel-line","name":"vercel","type":"bookmark","url":"https://vercel.com"},{"color":"#ffffff","iconType":"ri-code-line","name":"v0","type":"bookmark","url":"https://v0.app"},{"color":"#a3e635","iconColor":"#ffffff","iconType":"si-drizzle","name":"drizzle","type":"bookmark","url":"https://local.drizzle.studio/"},{"color":"#fbbc05","iconColor":"#ffffff","iconType":"ri-puzzle-2-fill","name":"chrome extensions","type":"bookmark","url":"https://chrome.google.com/webstore/devconsole"},{"color":"#ff7139","iconColor":"#ffffff","iconType":"ri-puzzle-2-fill","name":"firefox extensions","type":"bookmark","url":"https://addons.mozilla.org/en-US/developers/addons"},{"color":"#0a5bd3","iconColor":"#ffffff","iconType":"ri-puzzle-2-fill","name":"edge extensions","type":"bookmark","url":"https://developer.microsoft.com/en-us/microsoft-edge/extensions"}],"iconColor":"#8b5cf6","iconType":"ri-folder-open-fill","name":"dev","type":"folder"},{"color":"#06b6d4","contents":[{"color":"#f43f5e","iconColor":"#ffffff","iconType":"ri-youtube-fill","name":"youtube","type":"bookmark","url":"https://youtube.com"},{"color":"#ec4899","iconColor":"#ffffff","iconType":"ri-mail-fill","name":"gmail","type":"bookmark","url":"https://mail.google.com/mail/u/0/#inbox"},{"color":"#14b8a6","iconColor":"#ffffff","iconType":"ri-bar-chart-2-fill","name":"studio","type":"bookmark","url":"https://studio.youtube.com"},{"color":"#60a5fa","iconColor":"#ffffff","iconType":"ri-discord-fill","name":"discord","type":"bookmark","url":"https://discord.com/channels/@me"},{"color":"#e01e5a","iconColor":"#ffffff","iconType":"ri-slack-fill","name":"slack","type":"bookmark","url":"https://app.slack.com/client"},{"color":"#f97316","iconColor":"#ffffff","iconType":"ri-reddit-fill","name":"reddit","type":"bookmark","url":"https://www.reddit.com"},{"color":"#c13584","iconType":"ri-instagram-line","name":"instagram","type":"bookmark","url":"https://www.instagram.com"},{"color":"#ffffff","iconColor":"#ffffff","iconType":"ri-twitter-x-line","name":"twitter/x","type":"bookmark","url":"https://x.com"},{"color":"#1185fe","iconType":"ri-bluesky-fill","name":"bluesky","type":"bookmark","url":"https://bsky.app"}],"iconColor":"#06b6d4","iconType":"ri-folder-open-fill","name":"social","type":"folder"},{"color":"#22c55e","contents":[{"color":"#84cc16","iconColor":"#ffffff","iconType":"ri-calendar-line","name":"calendar","type":"bookmark","url":"https://calendar.google.com/calendar/u/0/r"},{"color":"#f43f5e","iconColor":"#ffffff","iconType":"ri-figma-line","name":"figma","type":"bookmark","url":"https://www.figma.com"},{"color":"#0ea5e9","iconColor":"#ffffff","iconType":"ri-drive-line","name":"drive","type":"bookmark","url":"https://drive.google.com/drive/home"},{"color":"#3b82f6","iconColor":"#ffffff","iconType":"ri-file-list-3-fill","name":"docs","type":"bookmark","url":"https://docs.google.com/document/u/0"},{"color":"#efb100","iconColor":"#ffffff","iconType":"ri-slideshow-view","name":"slides","type":"bookmark","url":"https://docs.google.com/presentation/u/0"},{"color":"#22c55e","iconColor":"#ffffff","iconType":"ri-table-3","name":"sheets","type":"bookmark","url":"https://docs.google.com/spreadsheets/u/0"},{"color":"#6366f1","iconColor":"#ffffff","iconType":"ri-survey-line","name":"forms","type":"bookmark","url":"https://docs.google.com/forms/u/0"},{"color":"#efb100","iconColor":"#ffffff","iconType":"ri-presentation-fill","name":"classroom","type":"bookmark","url":"https://classroom.google.com"}],"iconColor":"#22c55e","iconType":"ri-folder-open-fill","name":"productivity","type":"folder"},{"color":"#eab308","contents":[{"color":"#eab308","contents":[{"color":"#eab308","iconColor":"#ffffff","iconType":"nf-fa-keyboard","name":"monkeytype","type":"bookmark","url":"https://monkeytype.com"},{"color":"#14b8a6","iconColor":"#ffffff","iconType":"ri-flag-fill","name":"typeracer","type":"bookmark","url":"https://play.typeracer.com"},{"color":"#ef4444","iconColor":"#ffffff","iconType":"ri-speed-up-line","name":"nitrotype","type":"bookmark","url":"https://www.nitrotype.com/garage"},{"color":"#3b82f6","iconColor":"#ffffff","iconType":"ri-double-quotes-r","name":"typegg","type":"bookmark","url":"https://typegg.io"}],"iconColor":"#eab308","iconType":"ri-folder-open-fill","name":"typing","type":"folder"},{"color":"#ff9900","iconType":"ri-amazon-fill","name":"amazon","type":"bookmark","url":"https://www.amazon.com"}],"iconColor":"#eab308","name":"other","type":"folder"}],"defaultBlockyCols":4,"defaultBlockyColorType":"custom","defaultBlockyColor":"#ffffff","bookmarksLocationFirefox":"toolbar","defaultFaviconSource":"duckduckgo"},"extras":{"snow":{"enabled":"off"}}}
```

**[download mtab extension](https://get-mtab.vercel.app/)**

### anti youtube shorts filter for ublock origin
```
https://raw.githubusercontent.com/gijsdev/ublock-hide-yt-shorts/master/list.txt
```

### webhid support
```
echo 'KERNEL=="hidraw*", MODE="0666"' | sudo tee /etc/udev/rules.d/99-webhid.rules
sudo udevadm control --reload-rules && sudo udevadm trigger
```
