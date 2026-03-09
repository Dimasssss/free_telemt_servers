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

# Server Metrics 2026-03-09 03:48:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 16119.8 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13366
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 12060
telemt_upstream_connect_success_total 12057
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 12060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12055
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 126450636 (120.59 MB)
telemt_user_octets_to_client{user="hello"} 8892637027 (8.28 GB)
telemt_user_msgs_from_client{user="hello"} 252242
telemt_user_msgs_to_client{user="hello"} 389204
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 16118.2 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1307
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1203
telemt_upstream_connect_success_total 1203
telemt_upstream_connect_attempts_per_request{bucket="1"} 1203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1201
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 24556206 (23.42 MB)
telemt_user_octets_to_client{user="hello"} 1208939928 (1.13 GB)
telemt_user_msgs_from_client{user="hello"} 48481
telemt_user_msgs_to_client{user="hello"} 227182
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 16118.6 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1076
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 979
telemt_upstream_connect_success_total 979
telemt_upstream_connect_attempts_per_request{bucket="1"} 979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 977
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 384263426 (366.46 MB)
telemt_user_octets_to_client{user="hello"} 925792530 (882.90 MB)
telemt_user_msgs_from_client{user="hello"} 156461
telemt_user_msgs_to_client{user="hello"} 176777
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 16113.5 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2063
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 1696
telemt_upstream_connect_success_total 1696
telemt_upstream_connect_attempts_per_request{bucket="1"} 1696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1694
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 14357168 (13.69 MB)
telemt_user_octets_to_client{user="hello"} 1166025157 (1.09 GB)
telemt_user_msgs_from_client{user="hello"} 37202
telemt_user_msgs_to_client{user="hello"} 288994
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 16119.0 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4337
telemt_connections_bad_total 2939
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1366
telemt_upstream_connect_success_total 1366
telemt_upstream_connect_attempts_per_request{bucket="1"} 1366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1364
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 9951593 (9.49 MB)
telemt_user_octets_to_client{user="hello"} 1593173149 (1.48 GB)
telemt_user_msgs_from_client{user="hello"} 26061
telemt_user_msgs_to_client{user="hello"} 193403
telemt_user_unique_ips_current{user="hello"} 5
```