# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-06 19:21:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 4421.7 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7838
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 250
telemt_upstream_connect_attempt_total 7045
telemt_upstream_connect_success_total 7041
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 7045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7039
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 890764840 (849.50 MB)
telemt_user_octets_to_client{user="hello"} 11586321566 (10.79 GB)
telemt_user_msgs_from_client{user="hello"} 522426
telemt_user_msgs_to_client{user="hello"} 1815329
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 4420.4 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2347
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2177
telemt_upstream_connect_success_total 2177
telemt_upstream_connect_attempts_per_request{bucket="1"} 2177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2175
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 23768555 (22.67 MB)
telemt_user_octets_to_client{user="hello"} 1629729301 (1.52 GB)
telemt_user_msgs_from_client{user="hello"} 46772
telemt_user_msgs_to_client{user="hello"} 455499
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 4420.4 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1189
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1114
telemt_upstream_connect_success_total 1114
telemt_upstream_connect_attempts_per_request{bucket="1"} 1114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1112
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 13137959 (12.53 MB)
telemt_user_octets_to_client{user="hello"} 602604297 (574.69 MB)
telemt_user_msgs_from_client{user="hello"} 21897
telemt_user_msgs_to_client{user="hello"} 139581
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 4420.3 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1067
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1031
telemt_upstream_connect_success_total 1027
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 83
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1025
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 24476739 (23.34 MB)
telemt_user_octets_to_client{user="hello"} 444871853 (424.26 MB)
telemt_user_msgs_from_client{user="hello"} 24079
telemt_user_msgs_to_client{user="hello"} 114302
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 4420.7 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3593
telemt_connections_bad_total 822
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2742
telemt_upstream_connect_success_total 2741
telemt_upstream_connect_attempts_per_request{bucket="1"} 2741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2739
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 29501420 (28.13 MB)
telemt_user_octets_to_client{user="hello"} 2090928754 (1.95 GB)
telemt_user_msgs_from_client{user="hello"} 62996
telemt_user_msgs_to_client{user="hello"} 449776
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```