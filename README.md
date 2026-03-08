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

# Server Metrics 2026-03-08 19:22:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 44020.7 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101144
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 1260
telemt_upstream_connect_attempt_total 91553
telemt_upstream_connect_success_total 91522
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 91553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91516
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 2233793689 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 57148126302 (53.22 GB)
telemt_user_msgs_from_client{user="hello"} 2229730
telemt_user_msgs_to_client{user="hello"} 3126125
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 44019.8 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23351
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 22594
telemt_upstream_connect_success_total 22589
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22585
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 747795824 (713.15 MB)
telemt_user_octets_to_client{user="hello"} 20949076298 (19.51 GB)
telemt_user_msgs_from_client{user="hello"} 882977
telemt_user_msgs_to_client{user="hello"} 5700365
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 44019.6 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13998
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12666
telemt_upstream_connect_success_total 12590
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12586
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 259239270 (247.23 MB)
telemt_user_octets_to_client{user="hello"} 4415320490 (4.11 GB)
telemt_user_msgs_from_client{user="hello"} 218239
telemt_user_msgs_to_client{user="hello"} 788730
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 44019.3 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18056
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17293
telemt_upstream_connect_success_total 17256
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17252
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 1040532626 (992.33 MB)
telemt_user_octets_to_client{user="hello"} 6095013603 (5.68 GB)
telemt_user_msgs_from_client{user="hello"} 545959
telemt_user_msgs_to_client{user="hello"} 1383068
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 44019.6 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26065
telemt_connections_bad_total 8321
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 17094
telemt_upstream_connect_success_total 17087
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17081
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 319853143 (305.04 MB)
telemt_user_octets_to_client{user="hello"} 13465934494 (12.54 GB)
telemt_user_msgs_from_client{user="hello"} 423395
telemt_user_msgs_to_client{user="hello"} 1760262
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```