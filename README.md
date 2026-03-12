# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 00:08:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8581.9 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14684
telemt_connections_bad_total 237
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 13939
telemt_upstream_connect_success_total 13934
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13932
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 174446458 (166.37 MB)
telemt_user_octets_to_client{user="hello"} 5865863894 (5.46 GB)
telemt_user_msgs_from_client{user="hello"} 301266
telemt_user_msgs_to_client{user="hello"} 769684
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8570.1 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6316
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 6057
telemt_upstream_connect_success_total 6057
telemt_upstream_connect_attempts_per_request{bucket="1"} 6057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 780
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6055
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 30612070 (29.19 MB)
telemt_user_octets_to_client{user="hello"} 957844634 (913.47 MB)
telemt_user_msgs_from_client{user="hello"} 73789
telemt_user_msgs_to_client{user="hello"} 414329
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8543.9 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11071
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 768
telemt_upstream_connect_attempt_total 8640
telemt_upstream_connect_success_total 8640
telemt_upstream_connect_attempts_per_request{bucket="1"} 8640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8638
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 57469180 (54.81 MB)
telemt_user_octets_to_client{user="hello"} 5932778580 (5.53 GB)
telemt_user_msgs_from_client{user="hello"} 180675
telemt_user_msgs_to_client{user="hello"} 1357362
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8569.1 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10162
telemt_connections_bad_total 1867
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 7775
telemt_upstream_connect_success_total 7765
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 7775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7763
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 57637559 (54.97 MB)
telemt_user_octets_to_client{user="hello"} 3367236771 (3.14 GB)
telemt_user_msgs_from_client{user="hello"} 117972
telemt_user_msgs_to_client{user="hello"} 1186353
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 8569.9 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8252
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 7258
telemt_upstream_connect_success_total 7258
telemt_upstream_connect_attempts_per_request{bucket="1"} 7258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7256
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 107938966 (102.94 MB)
telemt_user_octets_to_client{user="hello"} 14934871934 (13.91 GB)
telemt_user_msgs_from_client{user="hello"} 217451
telemt_user_msgs_to_client{user="hello"} 1309517
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 16
```