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

# Server Metrics 2026-03-09 16:08:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 60525.8 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110370
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 971
telemt_upstream_connect_attempt_total 103169
telemt_upstream_connect_success_total 103130
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 103169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103124
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 2638273014 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 53780922706 (50.09 GB)
telemt_user_msgs_from_client{user="hello"} 2502187
telemt_user_msgs_to_client{user="hello"} 3592930
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 60524.9 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28657
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 346
telemt_upstream_connect_attempt_total 26998
telemt_upstream_connect_success_total 26981
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 26998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26975
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 848174392 (808.88 MB)
telemt_user_octets_to_client{user="hello"} 15320613427 (14.27 GB)
telemt_user_msgs_from_client{user="hello"} 766329
telemt_user_msgs_to_client{user="hello"} 4198898
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 60525.7 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36115
telemt_connections_bad_total 648
telemt_handshake_timeouts_total 1630
telemt_upstream_connect_attempt_total 27017
telemt_upstream_connect_success_total 27017
telemt_upstream_connect_attempts_per_request{bucket="1"} 27017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27011
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 4406604238 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 17388370790 (16.19 GB)
telemt_user_msgs_from_client{user="hello"} 1926626
telemt_user_msgs_to_client{user="hello"} 2295391
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 60520.0 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40670
telemt_connections_bad_total 197
telemt_handshake_timeouts_total 853
telemt_upstream_connect_attempt_total 37441
telemt_upstream_connect_success_total 37346
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 37441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37340
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 1928573525 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 29410562435 (27.39 GB)
telemt_user_msgs_from_client{user="hello"} 1236692
telemt_user_msgs_to_client{user="hello"} 7613841
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 60525.5 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68242
telemt_connections_bad_total 14583
telemt_handshake_timeouts_total 1585
telemt_upstream_connect_attempt_total 48881
telemt_upstream_connect_success_total 48879
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 48881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48873
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 823695801 (785.54 MB)
telemt_user_octets_to_client{user="hello"} 50265838587 (46.81 GB)
telemt_user_msgs_from_client{user="hello"} 1125846
telemt_user_msgs_to_client{user="hello"} 6195412
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```