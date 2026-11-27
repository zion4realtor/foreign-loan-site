# Research / facts — foreignloan site
- 站点定位与顺序：~/workspace/your_files/zion-site-matrix.md 第 1 波 #2。
- Zion 资质（MEMORY 已核实）：MLO 执照 CA + GA，2026 年 8 月首次获批；
  Virtual Properties Realty；电话 626.702.1888、微信 zion4realtor 与
  newhomes 站 CTA 一致（generate_v2.py）。
- 内容口径：外国买家项目常见首付 25%–40% 为行业一般区间表述，页内多处
  注明「因项目和个人情况而异、以贷款机构审核为准」，不写具体利率、
  不写批准承诺（符合矩阵数据规矩 #4：贷款带免责声明、不承诺利率）。
- 上线状态：2026-11-24 晚正式上线（Pages 项目 foreign-loan-site 在子站账号，
  CNAME foreignloan→foreign-loan-site.pages.dev 已生效，实测 200）。
- 2026-11-26：新增英文版 /en/（全英文测评 + 英文 FAQPage 结构化数据），
  中英两页互加 hreflang（zh-CN / en / x-default），sitemap 扩为 2 URL 并带
  xhtml:link 交替链接。目标英文搜索词 "foreign national mortgage Georgia"。
- 2026-11-27：11-26 的英文版提交（9af91ef2）24 小时后仍未部署到 Pages
  （pages.dev 与正式域名均为旧版：sitemap 仍 1 URL、/en/ 回退中文首页）。
  本次提交用于重新触发 Pages 自动部署；若仍不生效，需在子站账号控制台
  查看 foreign-loan-site 部署记录/手动 Retry deployment。
