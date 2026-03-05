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

# Server Metrics 2026-03-05 09:59:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 81146.4 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112438
telemt_connections_bad_total 468
telemt_handshake_timeouts_total 4027
telemt_upstream_connect_attempt_total 100225
telemt_upstream_connect_success_total 100201
telemt_upstream_connect_attempts_per_request{bucket="1"} 100177
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100193
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 2982592270 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 71487212498 (66.58 GB)
telemt_user_msgs_from_client{user="hello"} 2925511
telemt_user_msgs_to_client{user="hello"} 11661301
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 81149.3 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21665
telemt_connections_bad_total 444
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 16836
telemt_upstream_connect_success_total 16834
telemt_upstream_connect_attempts_per_request{bucket="1"} 16832
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16826
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1163772267 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 14380749827 (13.39 GB)
telemt_user_msgs_from_client{user="hello"} 803233
telemt_user_msgs_to_client{user="hello"} 4591448
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 81147.8 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17045
telemt_connections_bad_total 327
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 12893
telemt_upstream_connect_success_total 12893
telemt_upstream_connect_attempts_per_request{bucket="1"} 12893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12883
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 428292091 (408.45 MB)
telemt_user_octets_to_client{user="hello"} 9085751358 (8.46 GB)
telemt_user_msgs_from_client{user="hello"} 413763
telemt_user_msgs_to_client{user="hello"} 1909147
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 81145.2 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28171
telemt_connections_bad_total 976
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 24638
telemt_upstream_connect_success_total 24629
telemt_upstream_connect_attempts_per_request{bucket="1"} 24620
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24621
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 498669213 (475.57 MB)
telemt_user_octets_to_client{user="hello"} 17132210302 (15.96 GB)
telemt_user_msgs_from_client{user="hello"} 518849
telemt_user_msgs_to_client{user="hello"} 3784936
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 81146.9 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30998
telemt_connections_bad_total 14682
telemt_handshake_timeouts_total 61
telemt_upstream_connect_attempt_total 15785
telemt_upstream_connect_success_total 15781
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15779
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15773
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 614285437 (585.83 MB)
telemt_user_octets_to_client{user="hello"} 27491974648 (25.60 GB)
telemt_user_msgs_from_client{user="hello"} 711701
telemt_user_msgs_to_client{user="hello"} 5238950
telemt_user_unique_ips_current{user="hello"} 2
```