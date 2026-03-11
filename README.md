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

# Server Metrics 2026-03-11 05:39:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 54830.5 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141869
telemt_connections_bad_total 3415
telemt_handshake_timeouts_total 3494
telemt_upstream_connect_attempt_total 128615
telemt_upstream_connect_success_total 128571
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 128615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128565
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 3137818059 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 89056338481 (82.94 GB)
telemt_user_msgs_from_client{user="hello"} 3308368
telemt_user_msgs_to_client{user="hello"} 6276456
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 54829.9 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57354
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 2977
telemt_upstream_connect_attempt_total 51000
telemt_upstream_connect_success_total 50988
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 51000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50982
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 4524596001 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 47456854337 (44.20 GB)
telemt_user_msgs_from_client{user="hello"} 2721647
telemt_user_msgs_to_client{user="hello"} 11208674
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 54829.6 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78160
telemt_connections_bad_total 719
telemt_handshake_timeouts_total 4326
telemt_upstream_connect_attempt_total 68704
telemt_upstream_connect_success_total 68701
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 68704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68695
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 11795934736 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 71453832827 (66.55 GB)
telemt_user_msgs_from_client{user="hello"} 5213298
telemt_user_msgs_to_client{user="hello"} 13464394
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 54828.6 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82492
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 78955
telemt_upstream_connect_success_total 78783
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 78955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78777
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 1850293876 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 50373287142 (46.91 GB)
telemt_user_msgs_from_client{user="hello"} 1781531
telemt_user_msgs_to_client{user="hello"} 11128992
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 54829.8 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133725
telemt_connections_bad_total 12283
telemt_handshake_timeouts_total 1741
telemt_upstream_connect_attempt_total 111596
telemt_upstream_connect_success_total 111347
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 111596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111341
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 2433462664 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 106970929323 (99.62 GB)
telemt_user_msgs_from_client{user="hello"} 2689679
telemt_user_msgs_to_client{user="hello"} 13952991
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33799.3 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```