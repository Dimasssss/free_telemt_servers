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

# Server Metrics 2026-03-08 00:42:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 28640.6 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40035
telemt_connections_bad_total 1560
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 36905
telemt_upstream_connect_success_total 36900
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36896
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2216597524 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 26663563770 (24.83 GB)
telemt_user_msgs_from_client{user="hello"} 1300674
telemt_user_msgs_to_client{user="hello"} 4143202
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 28639.9 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7103
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6725
telemt_upstream_connect_success_total 6718
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 6725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6714
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 169595481 (161.74 MB)
telemt_user_octets_to_client{user="hello"} 10339973632 (9.63 GB)
telemt_user_msgs_from_client{user="hello"} 315300
telemt_user_msgs_to_client{user="hello"} 2382250
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 28639.6 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4231
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 3937
telemt_upstream_connect_success_total 3937
telemt_upstream_connect_attempts_per_request{bucket="1"} 3937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3933
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 108813801 (103.77 MB)
telemt_user_octets_to_client{user="hello"} 11728923237 (10.92 GB)
telemt_user_msgs_from_client{user="hello"} 185155
telemt_user_msgs_to_client{user="hello"} 2489287
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 28467.9 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11540
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 11061
telemt_upstream_connect_success_total 11036
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 11061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11032
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 252247296 (240.56 MB)
telemt_user_octets_to_client{user="hello"} 10186275104 (9.49 GB)
telemt_user_msgs_from_client{user="hello"} 298775
telemt_user_msgs_to_client{user="hello"} 3012051
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 28639.9 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12894
telemt_connections_bad_total 5296
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 7374
telemt_upstream_connect_success_total 7366
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7362
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1617078275 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7606442823 (7.08 GB)
telemt_user_msgs_from_client{user="hello"} 796477
telemt_user_msgs_to_client{user="hello"} 1688816
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```