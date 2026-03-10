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

# Server Metrics 2026-03-10 18:55:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16168.3 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63270
telemt_connections_bad_total 1947
telemt_handshake_timeouts_total 1503
telemt_upstream_connect_attempt_total 56714
telemt_upstream_connect_success_total 56702
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 56714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56700
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 1823902477 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 42619874775 (39.69 GB)
telemt_user_msgs_from_client{user="hello"} 1671497
telemt_user_msgs_to_client{user="hello"} 3206428
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16167.8 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24108
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 391
telemt_upstream_connect_attempt_total 22068
telemt_upstream_connect_success_total 22061
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 22068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22059
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 723692845 (690.17 MB)
telemt_user_octets_to_client{user="hello"} 12158946960 (11.32 GB)
telemt_user_msgs_from_client{user="hello"} 675243
telemt_user_msgs_to_client{user="hello"} 3778050
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16167.5 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36804
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 3163
telemt_upstream_connect_attempt_total 31235
telemt_upstream_connect_success_total 31235
telemt_upstream_connect_attempts_per_request{bucket="1"} 31235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31233
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 473972818 (452.02 MB)
telemt_user_octets_to_client{user="hello"} 33087188400 (30.81 GB)
telemt_user_msgs_from_client{user="hello"} 688317
telemt_user_msgs_to_client{user="hello"} 4822102
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16166.4 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34651
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 270
telemt_upstream_connect_attempt_total 33165
telemt_upstream_connect_success_total 33067
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 33165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33065
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 579434560 (552.59 MB)
telemt_user_octets_to_client{user="hello"} 27959701193 (26.04 GB)
telemt_user_msgs_from_client{user="hello"} 706399
telemt_user_msgs_to_client{user="hello"} 5014191
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16167.8 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50542
telemt_connections_bad_total 4650
telemt_handshake_timeouts_total 1081
telemt_upstream_connect_attempt_total 42798
telemt_upstream_connect_success_total 42557
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 42798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42555
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1439349780 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 29139110915 (27.14 GB)
telemt_user_msgs_from_client{user="hello"} 1218092
telemt_user_msgs_to_client{user="hello"} 4408756
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 17
```