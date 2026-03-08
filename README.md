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

# Server Metrics 2026-03-08 08:45:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 5779.9 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12380
telemt_connections_bad_total 2073
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 9755
telemt_upstream_connect_success_total 9750
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9748
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 260619159 (248.55 MB)
telemt_user_octets_to_client{user="hello"} 6157850272 (5.73 GB)
telemt_user_msgs_from_client{user="hello"} 230293
telemt_user_msgs_to_client{user="hello"} 308765
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 5778.9 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2628
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2494
telemt_upstream_connect_success_total 2494
telemt_upstream_connect_attempts_per_request{bucket="1"} 2494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2492
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 35180579 (33.55 MB)
telemt_user_octets_to_client{user="hello"} 1934710265 (1.80 GB)
telemt_user_msgs_from_client{user="hello"} 64891
telemt_user_msgs_to_client{user="hello"} 479774
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 5778.6 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2302
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2240
telemt_upstream_connect_success_total 2240
telemt_upstream_connect_attempts_per_request{bucket="1"} 2240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2238
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 25658111 (24.47 MB)
telemt_user_octets_to_client{user="hello"} 471046488 (449.22 MB)
telemt_user_msgs_from_client{user="hello"} 20843
telemt_user_msgs_to_client{user="hello"} 87329
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 5778.6 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2131
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 2038
telemt_upstream_connect_success_total 2034
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 2038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2032
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 46213009 (44.07 MB)
telemt_user_octets_to_client{user="hello"} 513725371 (489.93 MB)
telemt_user_msgs_from_client{user="hello"} 31352
telemt_user_msgs_to_client{user="hello"} 146978
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 5778.7 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3705
telemt_connections_bad_total 1079
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2595
telemt_upstream_connect_success_total 2595
telemt_upstream_connect_attempts_per_request{bucket="1"} 2595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2593
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 32761598 (31.24 MB)
telemt_user_octets_to_client{user="hello"} 2443555817 (2.28 GB)
telemt_user_msgs_from_client{user="hello"} 55839
telemt_user_msgs_to_client{user="hello"} 262701
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```