# 一丁书签云同步 隐私政策 / Privacy Policy

[中文](#中文) · [English](#english)

---

<a id="中文"></a>

# 一丁书签云同步 隐私政策

**生效日期**：2026 年 10 月 7 日　**开发者**：fanhe　**联系邮箱**：fanhe1618@gmail.com

「一丁书签云同步」（以下简称"本扩展"）用于把浏览器书签手动上传到你自己指定的 WebDAV 网盘（如坚果云），或从中下载后合并到本机。

## 1. 核心承诺

- 本扩展**没有开发者服务器**，开发者不会收到你的书签、账号、密码或任何使用数据。
- 数据只会在你主动操作时，发送到**你自己填写的 WebDAV 地址**，不会发送到其他任何地方。
- 不含统计、广告、追踪代码，不出售、不共享你的数据，不加载远程代码。

## 2. 处理哪些数据

| 数据 | 用途 | 存放位置 |
| --- | --- | --- |
| 书签（标题、网址、文件夹结构） | 上传到你的网盘；从网盘下载后合并到本机 | 本机浏览器；上传后在你的网盘 |
| WebDAV 地址、用户名、应用密码 | 登录你的网盘 | 仅本机浏览器的扩展存储 |
| 同步记录（上次同步时间、书签指纹） | 判断本机书签是否有变化，用于图标上的「!」提示 | 仅本机浏览器 |
| 撤销快照（操作前的本机书签副本） | 供「撤销上次操作」使用，只保留最近一份 | 仅本机浏览器 |

本扩展不收集浏览历史、网页内容、Cookie、位置、设备标识或个人身份信息。

## 3. 网络通信

仅在你保存设置、检查连接、上传、下载或删除云端备份时，向你填写的 WebDAV 地址发送标准 WebDAV 请求，并以 HTTP Basic 认证携带你的用户名和应用密码。只接受 `https://` 地址；内网地址经你确认后可使用 `http://`，公网 `http://` 会被拒绝。你的网盘服务商会按其自身政策处理它收到的数据，请自行了解。

## 4. 权限

- `bookmarks`：读取本机书签以便上传；在你确认后写入本机书签（合并、清空、还原）。
- `storage`：在本机保存设置、同步记录和撤销快照。
- `dav.jianguoyun.com`：连接坚果云。
- 可选网站权限：仅当你填写其他 WebDAV 地址时，浏览器会询问你是否允许访问**该地址**；你拒绝则不会访问。

本扩展不读取或修改任何网页，也没有申请标签页、历史记录、Cookie 等无关权限。

## 5. 保留与删除

- **设置与同步记录**：在设置页点「清除设置」，或卸载扩展即可删除。
- **撤销快照**：保留到被下一次操作覆盖，或卸载扩展时删除（「清除设置」不会删除它）。
- **云端备份**：本扩展只保留最近 3 个版本，上传成功后自动删除更早的；你也可以在备份列表或网盘中自行删除。卸载扩展不会删除已上传到网盘的文件。

## 6. 安全提示

- 应用密码保存在浏览器扩展存储中，本扩展不额外加密。请使用网盘的"应用密码"而非登录密码，并只在自己信任的设备上使用。
- 上传的书签文件是 JSON 明文，本扩展不加密，安全性取决于你所用的网盘服务。
- 在公用电脑上使用后，请点「清除设置」。重要书签建议另行备份。

## 7. 儿童隐私与政策更新

本扩展不面向 13 岁以下儿童。如数据处理方式发生变化，开发者会更新本政策和生效日期，重大变化会在扩展更新说明中提示。

## 8. 联系方式

如有疑问请联系：fanhe1618@gmail.com

---

<a id="english"></a>

# Yiding Bookmark Cloud Sync — Privacy Policy

**Effective date**: October 7, 2026　**Developer**: fanhe　**Contact**: fanhe1618@gmail.com

"Yiding Bookmark Cloud Sync" (the "Extension") lets you manually upload your browser bookmarks to a WebDAV storage service you choose (such as Jianguoyun), or download them from there and merge them into your browser.

## 1. Our commitments

- The Extension has **no developer-operated server**. The developer never receives your bookmarks, credentials, or any usage data.
- Data is sent **only to the WebDAV address you enter**, and only when you take an action. It is never sent anywhere else.
- No analytics, advertising, or tracking code. We do not sell or share your data, and the Extension does not load remote code.

## 2. Data handled

| Data | Purpose | Stored |
| --- | --- | --- |
| Bookmarks (titles, URLs, folder structure) | Uploaded to your storage; downloaded from it and merged locally | Your browser; your storage after upload |
| WebDAV URL, username, app password | Sign in to your storage | Your browser's extension storage only |
| Sync records (last sync time, bookmark fingerprint) | Detect local changes for the "!" badge | Your browser only |
| Undo snapshot (copy of local bookmarks before an operation) | Powers "Undo last action"; only the latest is kept | Your browser only |

The Extension does not collect browsing history, page content, cookies, location, device identifiers, or personally identifiable information.

## 3. Network communication

Only when you save settings, check the connection, upload, download, or delete cloud backups, the Extension sends standard WebDAV requests to the address you entered, using HTTP Basic authentication with your username and app password. Only `https://` is accepted; `http://` is allowed for private-network addresses after your confirmation, and public `http://` is rejected. Your storage provider processes the data it receives under its own policies; please review them.

## 4. Permissions

- `bookmarks`: read local bookmarks for upload; write local bookmarks (merge, clear, restore) after you confirm.
- `storage`: keep settings, sync records, and the undo snapshot locally.
- `dav.jianguoyun.com`: connect to Jianguoyun.
- Optional host permissions: only if you enter a different WebDAV address, the browser asks whether to allow access to **that address**; if you decline, it is not accessed.

The Extension does not read or modify any web page, and requests no unrelated permissions such as tabs, history, or cookies.

## 5. Retention and deletion

- **Settings and sync records**: click "Clear settings" or uninstall the Extension.
- **Undo snapshot**: kept until overwritten by the next operation, or removed on uninstall ("Clear settings" does not remove it).
- **Cloud backups**: the Extension keeps only the latest 3 versions and automatically deletes older ones after a successful upload; you can also delete them from the backup list or your storage. Uninstalling does not delete files already in your storage.

## 6. Security notes

- Your app password is stored in the browser's extension storage and is not additionally encrypted. Use an app-specific password rather than your login password, and use the Extension only on trusted devices.
- Uploaded bookmark files are plain-text JSON and are not encrypted by the Extension; their security depends on your storage provider.
- On a shared computer, click "Clear settings" after use. Keep a separate backup of important bookmarks.

## 7. Children and policy changes

The Extension is not directed to children under 13. If data handling changes, we will update this policy and its effective date, and note material changes in the release notes.

## 8. Contact

Questions? Contact: fanhe1618@gmail.com
