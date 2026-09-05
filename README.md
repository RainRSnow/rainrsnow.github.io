<!--
 * @Author: Chenyu Zhao zhaochenyu@icn.ist.hokudai.ac.jp
 * @Date: 2026-01-15 23:08:58
 * @LastEditors: Chenyu Zhao zhaochenyu@icn.ist.hokudai.ac.jp
 * @LastEditTime: 2026-01-15 23:08:59
 * @FilePath: /git_repo/yukipage/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# chenyu.github.io

## 中文（Chinese）

这是我的个人网站（RainRSnow 的个人主页），此仓库现为个人网页的源码 / 内容存放库，不再作为模板使用或分发。

说明
- 该仓库已被个人化、定制化，因此不再视为一个通用模板。
- 如果你是从本仓库派生（fork）或曾将本仓库当作模板，请注意本仓库目前以个人用途为主，某些内容已针对个人信息和偏好进行了修改。

元仓库（原始模板）
本项目基于一个原始仓库/模板开发。请参见元仓库以了解原始模板的详细信息与贡献历史：

- 原仓库（元仓库）: [personal-homepage-template](https://github.com/Yixin0313/personal-homepage-template)

许可（License）
本仓库保留并遵循元仓库的许可信息。元仓库的 LICENSE 文件内容已保留在本仓库中，如需查看请参阅仓库根目录的 `LICENSE` 文件。

请在复用或分发时遵循 LICENSE 中的条款，并保留原作者在 LICENSE 中的署名与版权声明。

联系
仓库所有者 / 网站负责人：RainRSnow

---

## English

This is my personal website (the personal homepage of RainRSnow). This repository now serves as the source/content repository for a personal site and is not intended to be used or distributed as a template.

Notes
- The repository has been personalized and customized, and is no longer treated as a generic template.
- If you forked or used this repository as a template, please be aware that it is now primarily for personal use and some content has been changed for personal information and preferences.

Upstream (Original Template)
This project was developed based on an original repository/template. Please refer to the upstream repository for details about the original template and contribution history:

- Upstream repository (original template): [personal-homepage-template](https://github.com/Yixin0313/personal-homepage-template)

License
This repository retains and follows the license information from the upstream repository. The upstream LICENSE file has been preserved in this repository; see the `LICENSE` file at the repository root for details.

When reusing or redistributing, please comply with the terms in the LICENSE and preserve original author attributions and copyright notices.

Contact
Repository owner / site maintainer: RainRSnow


## 本地预览与内容维护 / Preview and content maintenance

在仓库根目录运行 / Run from the repository root:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

访问 / Open `http://127.0.0.1:8000/`。内容通过 HTTP 加载，请勿使用 `file://` 直接打开。 / Content loads over HTTP; do not open the page with `file://`.

- `contents/zh/`：中文正文与界面配置。 / Chinese content and interface labels.
- `contents/en/`：英文正文与界面配置。 / English content and interface labels.
- `contents/publications.md`：两种语言共用的发表列表，保留原文。 / Shared publication list, retained in its original language.
- 每个语言目录中的 `config.yml` 保存纯文本标题、导航和页脚文案，正文使用同名 Markdown 文件对应。 / Each language has a `config.yml` for plain-text interface labels and matching Markdown files for section content.

导航栏的“中文 / EN”按钮切换整页语言。首次访问按浏览器首选语言选择中文或英文，之后记住选择；浏览器禁用本地存储时仍可切换。 / The navigation's “中文 / EN” buttons switch the page language. The first visit uses the browser's preferred language (Chinese or English); later visits remember the selection when local storage is available.
