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

# Server Metrics 2026-03-04 11:02:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 9551.0 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16203
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 14846
telemt_upstream_connect_success_total 14845
telemt_upstream_connect_attempts_per_request{bucket="1"} 14844
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14843
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 298500106 (284.67 MB)
telemt_user_octets_to_client{user="hello"} 7484981666 (6.97 GB)
telemt_user_msgs_from_client{user="hello"} 363739
telemt_user_msgs_to_client{user="hello"} 1247552
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 9562.7 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2133
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1968
telemt_upstream_connect_success_total 1966
telemt_upstream_connect_attempts_per_request{bucket="1"} 1964
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1964
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 75759518 (72.25 MB)
telemt_user_octets_to_client{user="hello"} 933356016 (890.12 MB)
telemt_user_msgs_from_client{user="hello"} 67158
telemt_user_msgs_to_client{user="hello"} 288837
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 9547.1 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1868
telemt_connections_bad_total 78
telemt_upstream_connect_attempt_total 1761
telemt_upstream_connect_success_total 1761
telemt_upstream_connect_attempts_per_request{bucket="1"} 1761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1759
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 44291108 (42.24 MB)
telemt_user_octets_to_client{user="hello"} 3316241633 (3.09 GB)
telemt_user_msgs_from_client{user="hello"} 94801
telemt_user_msgs_to_client{user="hello"} 628389
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 9537.7 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3488
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 3163
telemt_upstream_connect_success_total 3162
telemt_upstream_connect_attempts_per_request{bucket="1"} 3161
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3160
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 22902557 (21.84 MB)
telemt_user_octets_to_client{user="hello"} 1214895134 (1.13 GB)
telemt_user_msgs_from_client{user="hello"} 38872
telemt_user_msgs_to_client{user="hello"} 334915
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 9549.1 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3359
telemt_connections_bad_total 1706
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1585
telemt_upstream_connect_success_total 1585
telemt_upstream_connect_attempts_per_request{bucket="1"} 1585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1583
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 22864319 (21.81 MB)
telemt_user_octets_to_client{user="hello"} 822801864 (784.69 MB)
telemt_user_msgs_from_client{user="hello"} 45479
telemt_user_msgs_to_client{user="hello"} 207550
telemt_user_unique_ips_current{user="hello"} 1
```