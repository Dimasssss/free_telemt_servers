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

# Server Metrics 2026-03-05 00:04:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 45430.9 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67517
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 60931
telemt_upstream_connect_success_total 60916
telemt_upstream_connect_attempts_per_request{bucket="1"} 60901
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60910
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 2337667828 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 47031820918 (43.80 GB)
telemt_user_msgs_from_client{user="hello"} 1995717
telemt_user_msgs_to_client{user="hello"} 7500387
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 45433.8 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13629
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 11410
telemt_upstream_connect_success_total 11408
telemt_upstream_connect_attempts_per_request{bucket="1"} 11406
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11404
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1056308566 (1007.37 MB)
telemt_user_octets_to_client{user="hello"} 11091045446 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 649665
telemt_user_msgs_to_client{user="hello"} 3736536
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 45432.5 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11227
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 7336
telemt_upstream_connect_success_total 7336
telemt_upstream_connect_attempts_per_request{bucket="1"} 7336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7330
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308131215 (293.86 MB)
telemt_user_octets_to_client{user="hello"} 5254153354 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 268759
telemt_user_msgs_to_client{user="hello"} 1133881
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 45430.0 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15146
telemt_connections_bad_total 686
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 13215
telemt_upstream_connect_success_total 13210
telemt_upstream_connect_attempts_per_request{bucket="1"} 13205
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13204
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 392331458 (374.16 MB)
telemt_user_octets_to_client{user="hello"} 5585103487 (5.20 GB)
telemt_user_msgs_from_client{user="hello"} 302952
telemt_user_msgs_to_client{user="hello"} 1392686
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 45431.7 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17746
telemt_connections_bad_total 8167
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9222
telemt_upstream_connect_success_total 9218
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9216
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9212
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 512870607 (489.11 MB)
telemt_user_octets_to_client{user="hello"} 21170831733 (19.72 GB)
telemt_user_msgs_from_client{user="hello"} 542705
telemt_user_msgs_to_client{user="hello"} 4005096
```