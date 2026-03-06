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

# Server Metrics 2026-03-06 03:32:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 19011.5 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68783
telemt_connections_bad_total 51932
telemt_handshake_timeouts_total 2247
telemt_upstream_connect_attempt_total 13274
telemt_upstream_connect_success_total 13272
telemt_upstream_connect_attempts_per_request{bucket="1"} 13270
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13270
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 183677557 (175.17 MB)
telemt_user_octets_to_client{user="hello"} 13216827379 (12.31 GB)
telemt_user_msgs_from_client{user="hello"} 330533
telemt_user_msgs_to_client{user="hello"} 1943000
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 19009.5 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1736
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1578
telemt_upstream_connect_success_total 1577
telemt_upstream_connect_attempts_per_request{bucket="1"} 1576
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1575
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 47245426 (45.06 MB)
telemt_user_octets_to_client{user="hello"} 732340004 (698.41 MB)
telemt_user_msgs_from_client{user="hello"} 57666
telemt_user_msgs_to_client{user="hello"} 232591
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 19009.7 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1037
telemt_upstream_connect_success_total 1037
telemt_upstream_connect_attempts_per_request{bucket="1"} 1037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1033
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 35885813 (34.22 MB)
telemt_user_octets_to_client{user="hello"} 1698241545 (1.58 GB)
telemt_user_msgs_from_client{user="hello"} 44349
telemt_user_msgs_to_client{user="hello"} 337946
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 19012.5 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2339
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 267
telemt_upstream_connect_attempt_total 1884
telemt_upstream_connect_success_total 1884
telemt_upstream_connect_attempts_per_request{bucket="1"} 1884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1880
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 93883214 (89.53 MB)
telemt_user_octets_to_client{user="hello"} 5615271830 (5.23 GB)
telemt_user_msgs_from_client{user="hello"} 130793
telemt_user_msgs_to_client{user="hello"} 1173492
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 19012.3 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6061
telemt_connections_bad_total 3475
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 2390
telemt_upstream_connect_success_total 2390
telemt_upstream_connect_attempts_per_request{bucket="1"} 2390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2388
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 48779175 (46.52 MB)
telemt_user_octets_to_client{user="hello"} 11185962436 (10.42 GB)
telemt_user_msgs_from_client{user="hello"} 129062
telemt_user_msgs_to_client{user="hello"} 2030669
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```