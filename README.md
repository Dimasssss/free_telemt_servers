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

# Server Metrics 2026-03-11 00:59:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 38022.1 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105692
telemt_connections_bad_total 3344
telemt_handshake_timeouts_total 2501
telemt_upstream_connect_attempt_total 95179
telemt_upstream_connect_success_total 95145
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 95179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95141
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2712203492 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 77389098571 (72.07 GB)
telemt_user_msgs_from_client{user="hello"} 2746082
telemt_user_msgs_to_client{user="hello"} 5275103
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 38021.4 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42155
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 38376
telemt_upstream_connect_success_total 38367
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 38376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38363
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 2016432205 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38562278629 (35.91 GB)
telemt_user_msgs_from_client{user="hello"} 1601944
telemt_user_msgs_to_client{user="hello"} 9554610
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 38021.2 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65064
telemt_connections_bad_total 571
telemt_handshake_timeouts_total 4112
telemt_upstream_connect_attempt_total 56707
telemt_upstream_connect_success_total 56705
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 56707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56701
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 8183460724 (7.62 GB)
telemt_user_octets_to_client{user="hello"} 61165127252 (56.96 GB)
telemt_user_msgs_from_client{user="hello"} 3797370
telemt_user_msgs_to_client{user="hello"} 9708262
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 38020.0 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62319
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 59637
telemt_upstream_connect_success_total 59483
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 59637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59479
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 854621179 (815.03 MB)
telemt_user_octets_to_client{user="hello"} 38485799941 (35.84 GB)
telemt_user_msgs_from_client{user="hello"} 1195805
telemt_user_msgs_to_client{user="hello"} 7508798
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38021.4 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90425
telemt_connections_bad_total 8944
telemt_handshake_timeouts_total 1486
telemt_upstream_connect_attempt_total 76653
telemt_upstream_connect_success_total 76405
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 76653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76401
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 2121758023 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 62009220275 (57.75 GB)
telemt_user_msgs_from_client{user="hello"} 2073175
telemt_user_msgs_to_client{user="hello"} 9012765
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16990.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```