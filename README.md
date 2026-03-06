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

# Server Metrics 2026-03-06 04:18:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 21783.2 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72340
telemt_connections_bad_total 51934
telemt_handshake_timeouts_total 2431
telemt_upstream_connect_attempt_total 16570
telemt_upstream_connect_success_total 16568
telemt_upstream_connect_attempts_per_request{bucket="1"} 16566
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16566
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 211653778 (201.85 MB)
telemt_user_octets_to_client{user="hello"} 15282985765 (14.23 GB)
telemt_user_msgs_from_client{user="hello"} 386109
telemt_user_msgs_to_client{user="hello"} 2249316
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 21781.0 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2097
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1928
telemt_upstream_connect_success_total 1927
telemt_upstream_connect_attempts_per_request{bucket="1"} 1926
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 81
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1925
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 51276564 (48.90 MB)
telemt_user_octets_to_client{user="hello"} 928884343 (885.85 MB)
telemt_user_msgs_from_client{user="hello"} 67667
telemt_user_msgs_to_client{user="hello"} 293084
telemt_user_unique_ips_current{user="hello"} 8
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 21781.4 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1419
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1215
telemt_upstream_connect_success_total 1215
telemt_upstream_connect_attempts_per_request{bucket="1"} 1215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1211
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 36706298 (35.01 MB)
telemt_user_octets_to_client{user="hello"} 1732671971 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 46598
telemt_user_msgs_to_client{user="hello"} 347850
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 21784.3 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2980
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2479
telemt_upstream_connect_success_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 2479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2475
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 95352000 (90.93 MB)
telemt_user_octets_to_client{user="hello"} 5664189044 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 134465
telemt_user_msgs_to_client{user="hello"} 1188952
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 21783.9 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7167
telemt_connections_bad_total 3969
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 2965
telemt_upstream_connect_success_total 2965
telemt_upstream_connect_attempts_per_request{bucket="1"} 2965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2963
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 51801694 (49.40 MB)
telemt_user_octets_to_client{user="hello"} 11359376262 (10.58 GB)
telemt_user_msgs_from_client{user="hello"} 135998
telemt_user_msgs_to_client{user="hello"} 2068017
telemt_user_unique_ips_current{user="hello"} 3
```