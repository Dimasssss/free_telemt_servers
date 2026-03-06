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

# Server Metrics 2026-03-06 18:30:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 1340.5 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2281
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 2116
telemt_upstream_connect_success_total 2114
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2112
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 221109602 (210.87 MB)
telemt_user_octets_to_client{user="hello"} 4324069935 (4.03 GB)
telemt_user_msgs_from_client{user="hello"} 144111
telemt_user_msgs_to_client{user="hello"} 717470
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 1339.1 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 683
telemt_upstream_connect_success_total 683
telemt_upstream_connect_attempts_per_request{bucket="1"} 683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 681
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 5539908 (5.28 MB)
telemt_user_octets_to_client{user="hello"} 340317697 (324.55 MB)
telemt_user_msgs_from_client{user="hello"} 13170
telemt_user_msgs_to_client{user="hello"} 99818
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 1339.1 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 466
telemt_upstream_connect_success_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 464
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 6747814 (6.44 MB)
telemt_user_octets_to_client{user="hello"} 104172857 (99.35 MB)
telemt_user_msgs_from_client{user="hello"} 8264
telemt_user_msgs_to_client{user="hello"} 29272
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 1339.1 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 402
telemt_upstream_connect_success_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 400
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 20619494 (19.66 MB)
telemt_user_octets_to_client{user="hello"} 218863816 (208.72 MB)
telemt_user_msgs_from_client{user="hello"} 14521
telemt_user_msgs_to_client{user="hello"} 54666
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 1339.5 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1261
telemt_connections_bad_total 249
telemt_upstream_connect_attempt_total 1000
telemt_upstream_connect_success_total 1000
telemt_upstream_connect_attempts_per_request{bucket="1"} 1000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 998
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 8547423 (8.15 MB)
telemt_user_octets_to_client{user="hello"} 520827230 (496.70 MB)
telemt_user_msgs_from_client{user="hello"} 19394
telemt_user_msgs_to_client{user="hello"} 118536
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 8
```