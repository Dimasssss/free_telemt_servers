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

# Server Metrics 2026-03-12 04:49:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25441.8 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58459
telemt_connections_bad_total 2084
telemt_handshake_timeouts_total 1148
telemt_upstream_connect_attempt_total 52616
telemt_upstream_connect_success_total 52601
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 52616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52597
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 567375612 (541.09 MB)
telemt_user_octets_to_client{user="hello"} 18471166411 (17.20 GB)
telemt_user_msgs_from_client{user="hello"} 842137
telemt_user_msgs_to_client{user="hello"} 2071781
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25429.8 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22325
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 21199
telemt_upstream_connect_success_total 21196
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21192
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 190274897 (181.46 MB)
telemt_user_octets_to_client{user="hello"} 11974959313 (11.15 GB)
telemt_user_msgs_from_client{user="hello"} 405552
telemt_user_msgs_to_client{user="hello"} 3389699
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25403.4 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37272
telemt_connections_bad_total 526
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 33116
telemt_upstream_connect_success_total 33116
telemt_upstream_connect_attempts_per_request{bucket="1"} 33116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33112
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 5293663614 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 21276197001 (19.82 GB)
telemt_user_msgs_from_client{user="hello"} 2432794
telemt_user_msgs_to_client{user="hello"} 3843831
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25428.7 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38468
telemt_connections_bad_total 9048
telemt_handshake_timeouts_total 755
telemt_upstream_connect_attempt_total 27434
telemt_upstream_connect_success_total 25734
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 27434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25730
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 245541333 (234.17 MB)
telemt_user_octets_to_client{user="hello"} 20429361066 (19.03 GB)
telemt_user_msgs_from_client{user="hello"} 486430
telemt_user_msgs_to_client{user="hello"} 8495366
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25429.5 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34144
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 179
telemt_upstream_connect_attempt_total 31894
telemt_upstream_connect_success_total 31893
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 31894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31889
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 649850225 (619.75 MB)
telemt_user_octets_to_client{user="hello"} 33545496909 (31.24 GB)
telemt_user_msgs_from_client{user="hello"} 896645
telemt_user_msgs_to_client{user="hello"} 4457797
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```