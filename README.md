# SimpleCloudMusicPlayer
A CloudMusicPlayer code in C#

It support two search function：WangYi & BaiDu （For the first button and the second button on the right).

You can click the button on the right to use different function to search.

The BaiDu function is fine, you can use this function in two way: Fuzzy search or Precise search.

For Fuzzy search:Just input name of the song in textbox which on the top.

Then point the search button（next to the textbox）, the result will list in the listbox, click for play.

For Precise search:Input name of the song and the singer, with a space ditance.

If it find the song, it will play it. Or it will report an error.

Cause of API problems, the WangYi button, can only search by Songs ID.

It also contain a music station, but can't automatic to play next song. :(

-----------------------------------------------------------------------------------------

简易云音乐播放器

支持百度音乐和网易云音乐两个平台

百度平台支持模糊搜索和精确搜索

模糊搜索：输入 “歌名”

搜索结果出现在下方消息框中，点击即可播放

精确搜索：输入 “歌名 歌手”（中间需留一个空格）

搜索到就立即播放， 如未搜索到将报错

网易云由于API的问题只能支持按照ID查找并播放歌曲

同样添加了音乐电台， 但是无法自动播放下一首。。
