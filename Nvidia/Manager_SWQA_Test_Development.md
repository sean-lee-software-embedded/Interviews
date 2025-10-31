# Manager SWQA Test Development

**Job Description:** http://nvidia.eightfold.ai/careers/job/893383572286

## 面試流程（先問清楚節奏與期待）
1. 這個職缺的完整面試流程是什麼？會有 phone screen → virtual/onsite → hiring manager/團隊面談 → HR/薪資談嗎？預估時程與決策時間軸？（NVIDIA 官方說明通常是電話後接虛擬或實體面談，但各團隊會微調。）
   **Answer:** 美國 manager（first run）、台灣同事面試（Teams）、final run（美國 manager）
2. 是否有技術測驗 / take-home / 現場案例簡報？需要準備哪類題型（測試設計、Python、自動化平台、管理情境題）？第三方整理常見：Recruiter 初聊、技術面、可能有 coding/domain 專場。請問本 team 是否採用？
   **Answer:** BMC/BIOS firmware，software automation、testing、automation，data center
3. 每一輪面談面試官角色（研發、QA、平台、跨區同事）與重點主題為何？
4. 會不會安排實驗室/測試環境介紹或 tour（若是 onsite）？

## 工作模式 / 地點（WFH / 混合 / 到班）
5. 這個團隊目前採 WFH / Hybrid / Onsite 哪種？每週需要進辦公室幾天？核心到班日是哪些？
6. 工作模式是否視職務/團隊而定？（外部報導多次提到 NVIDIA 近年維持彈性、支持遠端或混合，仍以團隊需求為準—想確認本 team 的實際規範與彈性空間。）
   **Answer:** Onsite
7. 若需硬體/機房/實驗室操作（DGX/HGX、叢集、燒機、健康度檢測），是否規定必須到場？比例大概多少？
8. 跨時區協作（美西/以色列/歐洲）會議時段如何安排？是否有彈性工時或補休機制？
   **Answer:** 老闆在美國（不確定是不是美國人，但不會講中文）

## 團隊與職責範圍（Manager, SWQA Test Dev）
9. 團隊規模/職級組成、回報線、與相鄰團隊（Dev、平台、資料中心/IT、韌體/矽、供應商）的合作節點？
   **Answer:** 10-15 report to manager in America
10. 這個 Manager 的成功指標（前 90/180 天）是什麼？例如缺陷逃逸率、覆蓋率、MTTR、release on-time、效能/穩定性門檻等？
11. 團隊目前最大的痛點/空缺：自動化覆蓋不足、實驗室排程、測試數據治理、報表與可視化、流程落地…哪三件事最想先解？
   **Answer:** 擴邊（缺人）

## 技術棧 / 測試平台（你能很快對上）
12. 目前自動化語言/框架（Python/pytest/Robot？）、CI/CD（Jenkins/GitLab/GitHub Actions？）、容器/K8s、結果報表/資料湖工具？
13. 和 DCGM/NVML 的整合深度（健康檢查、診斷、policy、topology、job stats），回歸/壓力/長測如何掛 release gate？（DCGM 是資料中心 GPU 管理監控套件，可問實際用到哪些功能模組。）
14. 測試環境資源（DGX/HGX 機型、GPU 代數、NVSwitch/NVLink、儲存/網路）、排程/預約與重現機制如何運作？

## On-call / 發布 / 供應商
15. 是否有 on-call 或非上班時段的故障處理？頻率與補償？
16. 釋出流程：誰擁有 release gate？與開發/PM/運維的 go-no-go 溝通節點在哪？
17. 若涉及 ODM/供應商（機櫃、主機板、韌體），SQA 如何對齊規範、進行稽核、追蹤修復 SLA？

## 等級 / 薪酬 / 後勤
18. 這個職缺對應的職等（level）與薪資構成（base/bonus/RSU 範圍）？是否有簽約金/搬遷支援？
   **Answer:** 有 RSU，recruiter 不談這個，要三輪面完才知道
19. 若跨據點合作，需要差旅嗎？頻率與地點？
   **Answer:** 不一定
20. 若我通過本輪，下一步是哪一位（或哪些角色）面談？預計在哪一天/週安排？
