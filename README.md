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

# Server Metrics 2026-03-11 08:07:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 63700.3 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178269
telemt_connections_bad_total 3542
telemt_handshake_timeouts_total 4065
telemt_upstream_connect_attempt_total 162077
telemt_upstream_connect_success_total 162026
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 162077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 162018
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 3692268162 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 103445524224 (96.34 GB)
telemt_user_msgs_from_client{user="hello"} 3962295
telemt_user_msgs_to_client{user="hello"} 7436132
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 63699.4 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69160
telemt_connections_bad_total 585
telemt_handshake_timeouts_total 3088
telemt_upstream_connect_attempt_total 62171
telemt_upstream_connect_success_total 62157
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 62171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62151
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 4834734228 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 52188047268 (48.60 GB)
telemt_user_msgs_from_client{user="hello"} 2994943
telemt_user_msgs_to_client{user="hello"} 12986732
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 63699.2 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96349
telemt_connections_bad_total 908
telemt_handshake_timeouts_total 5170
telemt_upstream_connect_attempt_total 84603
telemt_upstream_connect_success_total 84600
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 84603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84594
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 11916475617 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 75178030218 (70.01 GB)
telemt_user_msgs_from_client{user="hello"} 5430947
telemt_user_msgs_to_client{user="hello"} 14598697
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 63698.2 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104286
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 704
telemt_upstream_connect_attempt_total 99661
telemt_upstream_connect_success_total 99438
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 99661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99430
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 4442116350 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 67444519968 (62.81 GB)
telemt_user_msgs_from_client{user="hello"} 3002547
telemt_user_msgs_to_client{user="hello"} 16758804
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 63699.4 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172278
telemt_connections_bad_total 14090
telemt_handshake_timeouts_total 2135
telemt_upstream_connect_attempt_total 137038
telemt_upstream_connect_success_total 136788
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 137038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136782
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 2697204461 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 128908257180 (120.06 GB)
telemt_user_msgs_from_client{user="hello"} 3105394
telemt_user_msgs_to_client{user="hello"} 16526769
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 42668.8 (11h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```