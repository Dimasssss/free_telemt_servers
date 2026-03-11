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

# Server Metrics 2026-03-11 16:50:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2171.2 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11101
telemt_connections_bad_total 576
telemt_handshake_timeouts_total 474
telemt_upstream_connect_attempt_total 9418
telemt_upstream_connect_success_total 9414
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9412
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 88802027 (84.69 MB)
telemt_user_octets_to_client{user="hello"} 4233956475 (3.94 GB)
telemt_user_msgs_from_client{user="hello"} 146377
telemt_user_msgs_to_client{user="hello"} 346851
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 95062.3 (26h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131694
telemt_connections_bad_total 982
telemt_handshake_timeouts_total 3485
telemt_upstream_connect_attempt_total 121668
telemt_upstream_connect_success_total 121643
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 121667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 627
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 121633
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 6130451135 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 73551358097 (68.50 GB)
telemt_user_msgs_from_client{user="hello"} 4216590
telemt_user_msgs_to_client{user="hello"} 21633122
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 95062.0 (26h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177449
telemt_connections_bad_total 1549
telemt_handshake_timeouts_total 7898
telemt_upstream_connect_attempt_total 158418
telemt_upstream_connect_success_total 158404
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 158418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 158394
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 12807067800 (11.93 GB)
telemt_user_octets_to_client{user="hello"} 136365761228 (127.00 GB)
telemt_user_msgs_from_client{user="hello"} 7049017
telemt_user_msgs_to_client{user="hello"} 31024962
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 95060.9 (26h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201765
telemt_connections_bad_total 10808
telemt_handshake_timeouts_total 3594
telemt_upstream_connect_attempt_total 179369
telemt_upstream_connect_success_total 178933
telemt_upstream_connect_fail_total 436
telemt_upstream_connect_attempts_per_request{bucket="1"} 179369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 492
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 436
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 178923
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 10487552240 (9.77 GB)
telemt_user_octets_to_client{user="hello"} 124586199152 (116.03 GB)
telemt_user_msgs_from_client{user="hello"} 6284498
telemt_user_msgs_to_client{user="hello"} 37084589
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 74031.6 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```