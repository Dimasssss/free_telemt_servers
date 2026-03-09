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

# Server Metrics 2026-03-09 18:52:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 70349.8 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133935
telemt_connections_bad_total 1800
telemt_handshake_timeouts_total 1113
telemt_upstream_connect_attempt_total 125395
telemt_upstream_connect_success_total 125352
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 125395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125344
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 3644340896 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 69495132166 (64.72 GB)
telemt_user_msgs_from_client{user="hello"} 3235752
telemt_user_msgs_to_client{user="hello"} 4436016
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 70348.6 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39233
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 456
telemt_upstream_connect_attempt_total 36847
telemt_upstream_connect_success_total 36826
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 36847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36818
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 1088604111 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 18031876407 (16.79 GB)
telemt_user_msgs_from_client{user="hello"} 992239
telemt_user_msgs_to_client{user="hello"} 5093918
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 70349.1 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48768
telemt_connections_bad_total 699
telemt_handshake_timeouts_total 2470
telemt_upstream_connect_attempt_total 38084
telemt_upstream_connect_success_total 38084
telemt_upstream_connect_attempts_per_request{bucket="1"} 38084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38076
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 4659205404 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 27715691164 (25.81 GB)
telemt_user_msgs_from_client{user="hello"} 2308237
telemt_user_msgs_to_client{user="hello"} 3966050
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 70343.9 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54736
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 918
telemt_upstream_connect_attempt_total 50140
telemt_upstream_connect_success_total 50013
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 50140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50005
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 2111265746 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 38808057327 (36.14 GB)
telemt_user_msgs_from_client{user="hello"} 1506769
telemt_user_msgs_to_client{user="hello"} 9334153
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 70349.4 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88556
telemt_connections_bad_total 16570
telemt_handshake_timeouts_total 2280
telemt_upstream_connect_attempt_total 65752
telemt_upstream_connect_success_total 65749
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 65751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65741
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 1142143782 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 59651328371 (55.55 GB)
telemt_user_msgs_from_client{user="hello"} 1513000
telemt_user_msgs_to_client{user="hello"} 7791361
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```