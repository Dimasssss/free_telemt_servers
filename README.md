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

# Server Metrics 2026-03-07 07:15:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 442.6 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 715
telemt_upstream_connect_success_total 715
telemt_upstream_connect_attempts_per_request{bucket="1"} 715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 713
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 9069706 (8.65 MB)
telemt_user_octets_to_client{user="hello"} 635593853 (606.15 MB)
telemt_user_msgs_from_client{user="hello"} 14976
telemt_user_msgs_to_client{user="hello"} 147951
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 441.7 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137
telemt_upstream_connect_attempt_total 139
telemt_upstream_connect_success_total 138
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 488174 (476.73 KB)
telemt_user_octets_to_client{user="hello"} 24936125 (23.78 MB)
telemt_user_msgs_from_client{user="hello"} 1438
telemt_user_msgs_to_client{user="hello"} 8925
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 441.4 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193
telemt_upstream_connect_attempt_total 194
telemt_upstream_connect_success_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 192
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 8752417 (8.35 MB)
telemt_user_octets_to_client{user="hello"} 81507504 (77.73 MB)
telemt_user_msgs_from_client{user="hello"} 3933
telemt_user_msgs_to_client{user="hello"} 18289
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 441.1 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 226
telemt_upstream_connect_success_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 224
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 3711721 (3.54 MB)
telemt_user_octets_to_client{user="hello"} 81868671 (78.08 MB)
telemt_user_msgs_from_client{user="hello"} 5703
telemt_user_msgs_to_client{user="hello"} 22728
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 441.6 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295
telemt_connections_bad_total 79
telemt_upstream_connect_attempt_total 216
telemt_upstream_connect_success_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 214
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 2052035 (1.96 MB)
telemt_user_octets_to_client{user="hello"} 654729908 (624.40 MB)
telemt_user_msgs_from_client{user="hello"} 4957
telemt_user_msgs_to_client{user="hello"} 122717
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```