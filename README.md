# th-mega dict

东方 Project 的 Rime 词库，适用于雾凇拼音等拼音方案。包含 **17,691 个词形、17,693 条读音记录**，涵盖人物、符卡、作品名及相关用语。

## 使用

1. 将 `th_mega.dict.yaml` 放入 Rime 用户资料夹，与 `rime_ice.dict.yaml` 同级。
2. 在 `rime_ice.dict.yaml` 原有的 `import_tables:` 列表中添加 `- th_mega`，保留其他基础词库项。
3. 重新部署即可。

其他方案请添加到实际使用的主词典。词典内部名称为 `th_mega`，不是 `th-mega dict`。

## 来源与修改

- **パチュリーPatchouli** 的东方微软拼音词库：转换为 Rime 格式，切分并规范拼音；作者 [B 站主页](https://space.bilibili.com/3493092321659700)，原说明保留于 [`readme.txt`](readme.txt)。
- **[THBWiki](https://thwiki.cc/) 贡献者**：选取 2026-11-16 sitemap 快照中的汉字标题，经繁转简、有限清洗及注音生成，并非全站词汇导出。构建使用 [mw2fcitx](https://github.com/outloudvi/mw2fcitx)。

合并按“完整词形＋拼音”去重，重复取较高权重，保留不同读音及间隔号写法。原页面及编辑历史可在 THBWiki 按来源标题查阅。

**部分读音由程序生成，未逐条人工校对。** 

## 转载与许可

- 原词库作者声明：**“此压缩包可以转载，但不得用于商业用途”**。
- THBWiki 的[版权信息](https://thwiki.cc/THBWiki:关于#版权信息)规定：文本除特别注明外采用 **[CC BY-NC-SA 3.0（署名—非商业性使用—相同方式共享）](https://creativecommons.org/licenses/by-nc-sa/3.0/deed.zh)**，附加条款亦可能适用；引用及其他作品的版权归原作者，按相应授权使用。THBWiki 来源及其改编部分须遵守这些条件。

转载时请随附本说明、`readme.txt` 及来源映射，保留署名、许可链接和修改说明。
