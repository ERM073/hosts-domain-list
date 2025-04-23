# 🛡️ hosts-domain-list

This is a list of `hosts` files designed to block malicious domains.

It is automatically generated and updated based on the latest malware intelligence provided by URLhaus. The following files are included:

---

## 📂 File Structure

| Filename                   | Description                                                              |
|----------------------------|--------------------------------------------------------------------------|
| `malware-domain-list.txt`  | A list of malicious domains from URLhaus (in `hostfile` format).        |
| `active-malware-list.txt`  | A list of hostnames extracted from currently active malware URLs.        |
| `new-malware-list.txt`     | A list of hostnames extracted from malware URLs reported in the last 30 days. |
| `hosts.txt`                | A basic consolidated blocklist of malware domains (URLhaus based).       |

---

## 🧠 Information Source

The data in this repository is generated based on information from:

- [https://urlhaus.abuse.ch/](https://urlhaus.abuse.ch/)

## 🔄 Automatic Updates

This list is automatically updated every 12 hours to ensure it reflects the latest malware threats.

---

# 🛡️ hosts-domain-list (日本語)

悪意のあるドメインをブロックするための `hosts` ファイルのリストです。  
URLhaus から提供される最新のマルウェア関連情報をもとに、以下のファイルを自動生成・更新しています。

---

## 📂 ファイル構成

| ファイル名 | 説明 |
|------------|------|
| `malware-domain-list.txt` | URLhaus による悪意あるドメインの一覧（`hostfile`ベース） |
| `active-malware-list.txt` | 現在アクティブとされるマルウェアURLから抽出したホスト名リスト |
| `new-malware-list.txt` | 過去30日以内に報告されたマルウェアURLから抽出したホスト名リスト |
| `hosts.txt` | マルウェアドメインのベーシックな統合ブロックリスト（URLhausベース） |

---

## 🧠 情報ソース

このリポジトリのデータは以下を元に生成されています：

- [https://urlhaus.abuse.ch/](https://urlhaus.abuse.ch/)

## 🔄 自動更新について

このリストは最新のマルウェア脅威に対応するために12時間おきに自動更新しています。
