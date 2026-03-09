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

# Server Metrics 2026-03-09 00:50:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 5418.7 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4685
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 4164
telemt_upstream_connect_success_total 4163
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4161
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 48998091 (46.73 MB)
telemt_user_octets_to_client{user="hello"} 6220375638 (5.79 GB)
telemt_user_msgs_from_client{user="hello"} 118041
telemt_user_msgs_to_client{user="hello"} 205788
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 5417.0 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 320
telemt_upstream_connect_success_total 320
telemt_upstream_connect_attempts_per_request{bucket="1"} 320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 318
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 1996070 (1.90 MB)
telemt_user_octets_to_client{user="hello"} 47060190 (44.88 MB)
telemt_user_msgs_from_client{user="hello"} 5804
telemt_user_msgs_to_client{user="hello"} 15329
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 5417.6 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 340
telemt_upstream_connect_success_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 338
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 16183136 (15.43 MB)
telemt_user_octets_to_client{user="hello"} 47991742 (45.77 MB)
telemt_user_msgs_from_client{user="hello"} 9560
telemt_user_msgs_to_client{user="hello"} 13234
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 5412.3 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 648
telemt_upstream_connect_success_total 648
telemt_upstream_connect_attempts_per_request{bucket="1"} 648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 646
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 4045525 (3.86 MB)
telemt_user_octets_to_client{user="hello"} 186797661 (178.14 MB)
telemt_user_msgs_from_client{user="hello"} 10050
telemt_user_msgs_to_client{user="hello"} 38489
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 5418.0 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1667
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 679
telemt_upstream_connect_success_total 679
telemt_upstream_connect_attempts_per_request{bucket="1"} 679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 677
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 6545962 (6.24 MB)
telemt_user_octets_to_client{user="hello"} 1269399943 (1.18 GB)
telemt_user_msgs_from_client{user="hello"} 18295
telemt_user_msgs_to_client{user="hello"} 156023
telemt_user_unique_ips_current{user="hello"} 7
```