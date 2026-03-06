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

# Server Metrics 2026-03-06 17:49:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 26841.6 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62811
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 281
telemt_upstream_connect_attempt_total 55181
telemt_upstream_connect_success_total 55168
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 55181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55164
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2789147794 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 36543802709 (34.03 GB)
telemt_user_msgs_from_client{user="hello"} 1919427
telemt_user_msgs_to_client{user="hello"} 5771219
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 26841.9 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12290
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 11711
telemt_upstream_connect_success_total 11692
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 11711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11688
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 149785258 (142.85 MB)
telemt_user_octets_to_client{user="hello"} 6321287247 (5.89 GB)
telemt_user_msgs_from_client{user="hello"} 244454
telemt_user_msgs_to_client{user="hello"} 1948970
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 26841.0 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9543
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 9205
telemt_upstream_connect_success_total 9203
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9201
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 133483435 (127.30 MB)
telemt_user_octets_to_client{user="hello"} 5535415229 (5.16 GB)
telemt_user_msgs_from_client{user="hello"} 211417
telemt_user_msgs_to_client{user="hello"} 1304641
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 26840.2 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13557
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 12633
telemt_upstream_connect_success_total 12589
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 12633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12585
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 188453735 (179.72 MB)
telemt_user_octets_to_client{user="hello"} 5688447541 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 235529
telemt_user_msgs_to_client{user="hello"} 1342448
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 26841.6 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19026
telemt_connections_bad_total 6383
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 11741
telemt_upstream_connect_success_total 11741
telemt_upstream_connect_attempts_per_request{bucket="1"} 11741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11737
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 262909875 (250.73 MB)
telemt_user_octets_to_client{user="hello"} 24377983598 (22.70 GB)
telemt_user_msgs_from_client{user="hello"} 452772
telemt_user_msgs_to_client{user="hello"} 4431678
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```