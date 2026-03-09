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

# Server Metrics 2026-03-09 01:30:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 7864.8 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6570
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 5938
telemt_upstream_connect_success_total 5936
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5934
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 68571754 (65.40 MB)
telemt_user_octets_to_client{user="hello"} 6939680958 (6.46 GB)
telemt_user_msgs_from_client{user="hello"} 152790
telemt_user_msgs_to_client{user="hello"} 253952
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 7862.9 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 449
telemt_upstream_connect_success_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 447
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 6529591 (6.23 MB)
telemt_user_octets_to_client{user="hello"} 422254545 (402.69 MB)
telemt_user_msgs_from_client{user="hello"} 18357
telemt_user_msgs_to_client{user="hello"} 81860
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 7863.5 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 494
telemt_upstream_connect_success_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 492
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 29799784 (28.42 MB)
telemt_user_octets_to_client{user="hello"} 80866264 (77.12 MB)
telemt_user_msgs_from_client{user="hello"} 16429
telemt_user_msgs_to_client{user="hello"} 25717
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 7858.3 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 896
telemt_upstream_connect_success_total 896
telemt_upstream_connect_attempts_per_request{bucket="1"} 896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 894
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 7491987 (7.14 MB)
telemt_user_octets_to_client{user="hello"} 545436943 (520.17 MB)
telemt_user_msgs_from_client{user="hello"} 19602
telemt_user_msgs_to_client{user="hello"} 149905
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 7863.8 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2259
telemt_connections_bad_total 1412
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 828
telemt_upstream_connect_success_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 826
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 6884018 (6.57 MB)
telemt_user_octets_to_client{user="hello"} 1285749595 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19208
telemt_user_msgs_to_client{user="hello"} 159027
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```