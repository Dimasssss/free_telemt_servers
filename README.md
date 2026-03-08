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

# Server Metrics 2026-03-08 20:49:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 49258.9 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110504
telemt_connections_bad_total 5481
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 100017
telemt_upstream_connect_success_total 99981
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 100017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99975
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2339266609 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 62580556738 (58.28 GB)
telemt_user_msgs_from_client{user="hello"} 2421240
telemt_user_msgs_to_client{user="hello"} 3392644
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 49257.9 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25739
telemt_connections_bad_total 275
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 24892
telemt_upstream_connect_success_total 24885
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24879
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 830879681 (792.39 MB)
telemt_user_octets_to_client{user="hello"} 22441665943 (20.90 GB)
telemt_user_msgs_from_client{user="hello"} 960126
telemt_user_msgs_to_client{user="hello"} 6070407
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 49257.7 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14953
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13551
telemt_upstream_connect_success_total 13475
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13469
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 1414837064 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 5648124640 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 645836
telemt_user_msgs_to_client{user="hello"} 963998
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 49257.6 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19573
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 18735
telemt_upstream_connect_success_total 18697
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 18735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18691
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 1060224097 (1011.11 MB)
telemt_user_octets_to_client{user="hello"} 6394791977 (5.96 GB)
telemt_user_msgs_from_client{user="hello"} 564031
telemt_user_msgs_to_client{user="hello"} 1444926
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 49257.8 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28957
telemt_connections_bad_total 9392
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 18864
telemt_upstream_connect_success_total 18857
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18851
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 347304326 (331.22 MB)
telemt_user_octets_to_client{user="hello"} 15665081391 (14.59 GB)
telemt_user_msgs_from_client{user="hello"} 483933
telemt_user_msgs_to_client{user="hello"} 2058945
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```