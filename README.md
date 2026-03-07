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

# Server Metrics 2026-03-07 08:57:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 6601.6 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9395
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 9074
telemt_upstream_connect_success_total 9073
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9071
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 389881597 (371.82 MB)
telemt_user_octets_to_client{user="hello"} 9177519998 (8.55 GB)
telemt_user_msgs_from_client{user="hello"} 322472
telemt_user_msgs_to_client{user="hello"} 1565876
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 6601.0 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2606
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2490
telemt_upstream_connect_success_total 2489
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2487
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 87640381 (83.58 MB)
telemt_user_octets_to_client{user="hello"} 1385412796 (1.29 GB)
telemt_user_msgs_from_client{user="hello"} 73091
telemt_user_msgs_to_client{user="hello"} 371720
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 6600.5 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1974
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 1887
telemt_upstream_connect_success_total 1887
telemt_upstream_connect_attempts_per_request{bucket="1"} 1887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1885
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 35658997 (34.01 MB)
telemt_user_octets_to_client{user="hello"} 560839832 (534.86 MB)
telemt_user_msgs_from_client{user="hello"} 34539
telemt_user_msgs_to_client{user="hello"} 142751
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 6600.5 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2184
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2120
telemt_upstream_connect_success_total 2115
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2113
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 73128953 (69.74 MB)
telemt_user_octets_to_client{user="hello"} 974155714 (929.03 MB)
telemt_user_msgs_from_client{user="hello"} 50914
telemt_user_msgs_to_client{user="hello"} 249706
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 6601.0 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4501
telemt_connections_bad_total 1279
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 2872
telemt_upstream_connect_success_total 2871
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2869
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 52614262 (50.18 MB)
telemt_user_octets_to_client{user="hello"} 13126164943 (12.22 GB)
telemt_user_msgs_from_client{user="hello"} 88211
telemt_user_msgs_to_client{user="hello"} 2348717
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```