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

# Server Metrics 2026-03-09 00:04:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 2667.1 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2241
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 1816
telemt_upstream_connect_success_total 1816
telemt_upstream_connect_attempts_per_request{bucket="1"} 1816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1814
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 18945184 (18.07 MB)
telemt_user_octets_to_client{user="hello"} 1725721990 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 46853
telemt_user_msgs_to_client{user="hello"} 76159
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 2665.1 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 195
telemt_upstream_connect_success_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 193
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 1533805 (1.46 MB)
telemt_user_octets_to_client{user="hello"} 44893272 (42.81 MB)
telemt_user_msgs_from_client{user="hello"} 4046
telemt_user_msgs_to_client{user="hello"} 13087
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 2665.9 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224
telemt_connections_bad_total 26
telemt_upstream_connect_attempt_total 196
telemt_upstream_connect_success_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 194
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 11801942 (11.26 MB)
telemt_user_octets_to_client{user="hello"} 22169837 (21.14 MB)
telemt_user_msgs_from_client{user="hello"} 6484
telemt_user_msgs_to_client{user="hello"} 7570
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 2660.7 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 317
telemt_upstream_connect_success_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 315
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 1078983 (1.03 MB)
telemt_user_octets_to_client{user="hello"} 31731399 (30.26 MB)
telemt_user_msgs_from_client{user="hello"} 3216
telemt_user_msgs_to_client{user="hello"} 9797
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 2666.1 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726
telemt_connections_bad_total 478
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 242
telemt_upstream_connect_success_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 240
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 4091980 (3.90 MB)
telemt_user_octets_to_client{user="hello"} 1009928102 (963.14 MB)
telemt_user_msgs_from_client{user="hello"} 11452
telemt_user_msgs_to_client{user="hello"} 110401
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```