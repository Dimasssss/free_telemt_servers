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

# Server Metrics 2026-03-11 00:24:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 35884.1 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103117
telemt_connections_bad_total 3341
telemt_handshake_timeouts_total 2491
telemt_upstream_connect_attempt_total 92729
telemt_upstream_connect_success_total 92696
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 92729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92692
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2688322559 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 75678420532 (70.48 GB)
telemt_user_msgs_from_client{user="hello"} 2696023
telemt_user_msgs_to_client{user="hello"} 5165596
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 35883.4 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40677
telemt_connections_bad_total 340
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 36987
telemt_upstream_connect_success_total 36978
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 36987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36974
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2008577576 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38456650876 (35.82 GB)
telemt_user_msgs_from_client{user="hello"} 1581958
telemt_user_msgs_to_client{user="hello"} 9503116
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 35883.0 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63533
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 4091
telemt_upstream_connect_attempt_total 55385
telemt_upstream_connect_success_total 55383
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55379
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 8167233049 (7.61 GB)
telemt_user_octets_to_client{user="hello"} 57376408741 (53.44 GB)
telemt_user_msgs_from_client{user="hello"} 3752810
telemt_user_msgs_to_client{user="hello"} 8492656
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 35882.1 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60511
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 57901
telemt_upstream_connect_success_total 57747
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 57901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57743
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 847945816 (808.66 MB)
telemt_user_octets_to_client{user="hello"} 38316083879 (35.68 GB)
telemt_user_msgs_from_client{user="hello"} 1179583
telemt_user_msgs_to_client{user="hello"} 7453641
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35883.2 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87861
telemt_connections_bad_total 8552
telemt_handshake_timeouts_total 1472
telemt_upstream_connect_attempt_total 74551
telemt_upstream_connect_success_total 74303
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 74551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74299
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2103791026 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 58474226836 (54.46 GB)
telemt_user_msgs_from_client{user="hello"} 2029828
telemt_user_msgs_to_client{user="hello"} 8473788
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 14852.7 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```