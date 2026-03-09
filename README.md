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

# Server Metrics 2026-03-09 15:07:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 56853.3 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101426
telemt_connections_bad_total 1651
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 94478
telemt_upstream_connect_success_total 94440
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 94478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94434
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 2482532509 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 49415296915 (46.02 GB)
telemt_user_msgs_from_client{user="hello"} 2313959
telemt_user_msgs_to_client{user="hello"} 3266955
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 56851.6 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25233
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 23699
telemt_upstream_connect_success_total 23682
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 23699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23676
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 814719372 (776.98 MB)
telemt_user_octets_to_client{user="hello"} 13428677370 (12.51 GB)
telemt_user_msgs_from_client{user="hello"} 704051
telemt_user_msgs_to_client{user="hello"} 3661691
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 56852.7 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31646
telemt_connections_bad_total 643
telemt_handshake_timeouts_total 1543
telemt_upstream_connect_attempt_total 22863
telemt_upstream_connect_success_total 22863
telemt_upstream_connect_attempts_per_request{bucket="1"} 22863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22857
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 4353811255 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 14182810871 (13.21 GB)
telemt_user_msgs_from_client{user="hello"} 1853561
telemt_user_msgs_to_client{user="hello"} 1935969
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 56846.9 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34360
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 812
telemt_upstream_connect_attempt_total 31479
telemt_upstream_connect_success_total 31397
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 31479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31391
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 1842189107 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 24571631294 (22.88 GB)
telemt_user_msgs_from_client{user="hello"} 1104734
telemt_user_msgs_to_client{user="hello"} 6197698
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 56852.4 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61864
telemt_connections_bad_total 13739
telemt_handshake_timeouts_total 1541
telemt_upstream_connect_attempt_total 43671
telemt_upstream_connect_success_total 43669
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 43671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43663
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 732533019 (698.60 MB)
telemt_user_octets_to_client{user="hello"} 43336185103 (40.36 GB)
telemt_user_msgs_from_client{user="hello"} 967268
telemt_user_msgs_to_client{user="hello"} 5343932
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```