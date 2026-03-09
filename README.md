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

# Server Metrics 2026-03-09 05:10:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 21013.2 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19368
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 555
telemt_upstream_connect_attempt_total 17489
telemt_upstream_connect_success_total 17484
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17482
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 164782714 (157.15 MB)
telemt_user_octets_to_client{user="hello"} 9915234225 (9.23 GB)
telemt_user_msgs_from_client{user="hello"} 319484
telemt_user_msgs_to_client{user="hello"} 477116
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 21011.3 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2355
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 2184
telemt_upstream_connect_success_total 2184
telemt_upstream_connect_attempts_per_request{bucket="1"} 2184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2182
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 36095711 (34.42 MB)
telemt_user_octets_to_client{user="hello"} 1673854237 (1.56 GB)
telemt_user_msgs_from_client{user="hello"} 74907
telemt_user_msgs_to_client{user="hello"} 330003
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 21011.9 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1455
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1355
telemt_upstream_connect_success_total 1355
telemt_upstream_connect_attempts_per_request{bucket="1"} 1355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1351
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 905884324 (863.92 MB)
telemt_user_octets_to_client{user="hello"} 1035860634 (987.87 MB)
telemt_user_msgs_from_client{user="hello"} 344241
telemt_user_msgs_to_client{user="hello"} 205574
telemt_user_unique_ips_current{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 21006.6 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2783
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 2265
telemt_upstream_connect_success_total 2265
telemt_upstream_connect_attempts_per_request{bucket="1"} 2265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2261
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 18710172 (17.84 MB)
telemt_user_octets_to_client{user="hello"} 1577080672 (1.47 GB)
telemt_user_msgs_from_client{user="hello"} 48192
telemt_user_msgs_to_client{user="hello"} 370789
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 21012.1 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6008
telemt_connections_bad_total 3815
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2144
telemt_upstream_connect_success_total 2144
telemt_upstream_connect_attempts_per_request{bucket="1"} 2144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2142
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 18242258 (17.40 MB)
telemt_user_octets_to_client{user="hello"} 2222263152 (2.07 GB)
telemt_user_msgs_from_client{user="hello"} 44892
telemt_user_msgs_to_client{user="hello"} 263772
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```