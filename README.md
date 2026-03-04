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

# Server Metrics 2026-03-04 14:07:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 9606.9 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15720
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 14795
telemt_upstream_connect_success_total 14793
telemt_upstream_connect_attempts_per_request{bucket="1"} 14791
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14791
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 431383780 (411.40 MB)
telemt_user_octets_to_client{user="hello"} 13876342192 (12.92 GB)
telemt_user_msgs_from_client{user="hello"} 475941
telemt_user_msgs_to_client{user="hello"} 2183079
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 9610.0 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3461
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3228
telemt_upstream_connect_success_total 3227
telemt_upstream_connect_attempts_per_request{bucket="1"} 3226
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3225
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 181886351 (173.46 MB)
telemt_user_octets_to_client{user="hello"} 3437420850 (3.20 GB)
telemt_user_msgs_from_client{user="hello"} 137598
telemt_user_msgs_to_client{user="hello"} 1086793
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 9608.0 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1607
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1554
telemt_upstream_connect_success_total 1554
telemt_upstream_connect_attempts_per_request{bucket="1"} 1554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1552
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 65613736 (62.57 MB)
telemt_user_octets_to_client{user="hello"} 702792778 (670.24 MB)
telemt_user_msgs_from_client{user="hello"} 61283
telemt_user_msgs_to_client{user="hello"} 173479
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 9606.0 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3725
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3418
telemt_upstream_connect_success_total 3416
telemt_upstream_connect_attempts_per_request{bucket="1"} 3414
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3414
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 26359605 (25.14 MB)
telemt_user_octets_to_client{user="hello"} 2146045064 (2.00 GB)
telemt_user_msgs_from_client{user="hello"} 55786
telemt_user_msgs_to_client{user="hello"} 503193
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 9607.7 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4191
telemt_connections_bad_total 1725
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2331
telemt_upstream_connect_success_total 2330
telemt_upstream_connect_attempts_per_request{bucket="1"} 2329
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2328
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 45627832 (43.51 MB)
telemt_user_octets_to_client{user="hello"} 6818122140 (6.35 GB)
telemt_user_msgs_from_client{user="hello"} 109327
telemt_user_msgs_to_client{user="hello"} 1241038
```