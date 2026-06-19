# MediaHard: профиль инженера (universwebsite)

Привет! Я **AndroiT**, SRE/DevOps инженер. Строю отказоустойчивые кластеры на **Proxmox VE 9 (Trixie)** с **Ceph**, **ZFS**, **pvesr**.

Этот репозиторий — моя «визитка» на GitHub. Основной проект и документация — в [`mediahard-app`](https://github.com/universwebsite/mediahard-app).

## 🛠 Что я делаю

- **Кластер Proxmox на 3 узлах** (pve1, pve2, pve3): кворум, corosync, CFS, диагностика проблем вроде `Connection refused`, `Operation not permitted`, восстановление после потери кворума.
- **Хранилища и репликация**: Ceph (мониторы, OSD, кворум), ZFS, pvesr (репликация между узлами), устранение ошибок репликации и зависаний.
- **Сеть**: bond, VLAN, MTU 9000, диагностика через `ping -M do`, `mtr`, `ss -tlnp`.
- **Docs as Code**: документация в Markdown, сборка через **MkDocs + Material**, публикация на `mediahard.ru/wiki`.
- **CI/CD и автоматизация**: Git‑workflow, коммиты с верификацией, подготовка артефактов для резюме и собеседования.

## 📚 Где искать документацию

- [`mediahard-app/wiki/ops`](https://github.com/universwebsite/mediahard-app/wiki/ops/docs/index.md) — инфраструктурные статьи, чек‑листы, сценарии восстановления.
- [`mkdocs.yml`](https://github.com/universwebsite/mediahard-app/wiki/ops/mkdocs.yml) — навигация и структура документации.

## 🧪 Примеры типовых задач, которые документирую

- Пересоздание кластера PVE: удаление `corosync.conf`, очистка кэша CFS, перегенерация ключей.
- Диагностика Ceph: `ceph -s`, проверка мониторов, восстановление кворума.
- Настройка SSH‑туннелей и прокси через `systemd-ssh-proxy` для доступа к изолированным сегментам сети.
- Устранение ошибок GUI Proxmox после изменений крипто‑настроек и постквантовых алгоритмов.

## 📩 Как связаться

* **Secure E-mail:** [universwebsite@proton.me](mailto:universwebsite@proton.me) 
* **Основной домен проекта:** [mediahard.ru](https://mediahard.ru)
Или открой issue в любом из репозиториев — отвечу.

---

_AndroiT | MediaHard Ops_
