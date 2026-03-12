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

# Server Metrics 2026-03-12 01:07:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12148.0 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23132
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 20431
telemt_upstream_connect_success_total 20425
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20423
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 226328921 (215.84 MB)
telemt_user_octets_to_client{user="hello"} 7153344169 (6.66 GB)
telemt_user_msgs_from_client{user="hello"} 381048
telemt_user_msgs_to_client{user="hello"} 963350
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12136.4 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9446
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9055
telemt_upstream_connect_success_total 9055
telemt_upstream_connect_attempts_per_request{bucket="1"} 9055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9053
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 62343318 (59.46 MB)
telemt_user_octets_to_client{user="hello"} 3228975171 (3.01 GB)
telemt_user_msgs_from_client{user="hello"} 156094
telemt_user_msgs_to_client{user="hello"} 1028599
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12109.9 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16100
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 862
telemt_upstream_connect_attempt_total 13297
telemt_upstream_connect_success_total 13297
telemt_upstream_connect_attempts_per_request{bucket="1"} 13297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13295
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 713466301 (680.41 MB)
telemt_user_octets_to_client{user="hello"} 7183522975 (6.69 GB)
telemt_user_msgs_from_client{user="hello"} 477171
telemt_user_msgs_to_client{user="hello"} 1632065
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12135.1 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16043
telemt_connections_bad_total 3460
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 11320
telemt_upstream_connect_success_total 11309
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 11320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11307
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 86772790 (82.75 MB)
telemt_user_octets_to_client{user="hello"} 5094212175 (4.74 GB)
telemt_user_msgs_from_client{user="hello"} 174114
telemt_user_msgs_to_client{user="hello"} 1907747
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12136.0 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12547
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 11329
telemt_upstream_connect_success_total 11329
telemt_upstream_connect_attempts_per_request{bucket="1"} 11329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11327
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 177273256 (169.06 MB)
telemt_user_octets_to_client{user="hello"} 17528097365 (16.32 GB)
telemt_user_msgs_from_client{user="hello"} 310972
telemt_user_msgs_to_client{user="hello"} 1606513
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```