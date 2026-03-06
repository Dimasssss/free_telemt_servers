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

# Server Metrics 2026-03-06 19:26:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 4729.9 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8677
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 7757
telemt_upstream_connect_success_total 7753
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 7757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7751
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 895347225 (853.87 MB)
telemt_user_octets_to_client{user="hello"} 11863395854 (11.05 GB)
telemt_user_msgs_from_client{user="hello"} 533333
telemt_user_msgs_to_client{user="hello"} 1861664
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 4728.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2422
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2251
telemt_upstream_connect_success_total 2251
telemt_upstream_connect_attempts_per_request{bucket="1"} 2251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2249
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 41878826 (39.94 MB)
telemt_user_octets_to_client{user="hello"} 1657233311 (1.54 GB)
telemt_user_msgs_from_client{user="hello"} 54269
telemt_user_msgs_to_client{user="hello"} 465080
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 4728.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1179
telemt_upstream_connect_success_total 1179
telemt_upstream_connect_attempts_per_request{bucket="1"} 1179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1177
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 15161108 (14.46 MB)
telemt_user_octets_to_client{user="hello"} 610034652 (581.77 MB)
telemt_user_msgs_from_client{user="hello"} 22831
telemt_user_msgs_to_client{user="hello"} 141925
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 4728.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1132
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1095
telemt_upstream_connect_success_total 1091
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 89
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1089
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 24748953 (23.60 MB)
telemt_user_octets_to_client{user="hello"} 449571956 (428.75 MB)
telemt_user_msgs_from_client{user="hello"} 24617
telemt_user_msgs_to_client{user="hello"} 115888
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 4728.8 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3803
telemt_connections_bad_total 877
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2897
telemt_upstream_connect_success_total 2897
telemt_upstream_connect_attempts_per_request{bucket="1"} 2897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2895
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 58522182 (55.81 MB)
telemt_user_octets_to_client{user="hello"} 2103710826 (1.96 GB)
telemt_user_msgs_from_client{user="hello"} 74211
telemt_user_msgs_to_client{user="hello"} 454958
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```