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

# Server Metrics 2026-03-11 18:28:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5280.4 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21611
telemt_connections_bad_total 1147
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 19435
telemt_upstream_connect_success_total 19430
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 19434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19428
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 587949707 (560.71 MB)
telemt_user_octets_to_client{user="hello"} 12426645115 (11.57 GB)
telemt_user_msgs_from_client{user="hello"} 504379
telemt_user_msgs_to_client{user="hello"} 922280
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 5268.7 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10662
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 209
telemt_upstream_connect_attempt_total 9552
telemt_upstream_connect_success_total 9551
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9549
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 158579380 (151.23 MB)
telemt_user_octets_to_client{user="hello"} 6236437264 (5.81 GB)
telemt_user_msgs_from_client{user="hello"} 226148
telemt_user_msgs_to_client{user="hello"} 2321019
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 5288.0 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12137
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 105
telemt_upstream_connect_attempt_total 11276
telemt_upstream_connect_success_total 11274
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 11276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11272
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 89871064 (85.71 MB)
telemt_user_octets_to_client{user="hello"} 4908765261 (4.57 GB)
telemt_user_msgs_from_client{user="hello"} 232250
telemt_user_msgs_to_client{user="hello"} 1405050
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 5284.0 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11948
telemt_connections_bad_total 565
telemt_handshake_timeouts_total 191
telemt_upstream_connect_attempt_total 10764
telemt_upstream_connect_success_total 10736
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 10764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10734
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 460316145 (438.99 MB)
telemt_user_octets_to_client{user="hello"} 5740400832 (5.35 GB)
telemt_user_msgs_from_client{user="hello"} 300851
telemt_user_msgs_to_client{user="hello"} 1307187
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5292.1 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13136
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 78
telemt_upstream_connect_attempt_total 11608
telemt_upstream_connect_success_total 11608
telemt_upstream_connect_attempts_per_request{bucket="1"} 11608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11606
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 201957001 (192.60 MB)
telemt_user_octets_to_client{user="hello"} 2416486418 (2.25 GB)
telemt_user_msgs_from_client{user="hello"} 217776
telemt_user_msgs_to_client{user="hello"} 742256
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 79898.4 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 14
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