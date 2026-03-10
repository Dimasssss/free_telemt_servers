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

# Server Metrics 2026-03-10 10:23:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 126227.9 (35h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266556
telemt_connections_bad_total 3451
telemt_handshake_timeouts_total 2768
telemt_upstream_connect_attempt_total 249461
telemt_upstream_connect_success_total 249333
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 249445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 230252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 249321
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 6149481776 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 150150641191 (139.84 GB)
telemt_user_msgs_from_client{user="hello"} 6010828
telemt_user_msgs_to_client{user="hello"} 9504666
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 126226.8 (35h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80334
telemt_connections_bad_total 3259
telemt_handshake_timeouts_total 1049
telemt_upstream_connect_attempt_total 71901
telemt_upstream_connect_success_total 71858
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 71901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 401
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71846
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 2359565602 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 33008118608 (30.74 GB)
telemt_user_msgs_from_client{user="hello"} 1953207
telemt_user_msgs_to_client{user="hello"} 9459252
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 126227.4 (35h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115699
telemt_connections_bad_total 1159
telemt_handshake_timeouts_total 5787
telemt_upstream_connect_attempt_total 82805
telemt_upstream_connect_success_total 82803
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 82805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82791
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 6408652734 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 63585521331 (59.22 GB)
telemt_user_msgs_from_client{user="hello"} 4135824
telemt_user_msgs_to_client{user="hello"} 10299671
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 126222.1 (35h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117683
telemt_connections_bad_total 1026
telemt_handshake_timeouts_total 1350
telemt_upstream_connect_attempt_total 109554
telemt_upstream_connect_success_total 109311
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 109554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 262
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109299
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 3000055838 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 80276565107 (74.76 GB)
telemt_user_msgs_from_client{user="hello"} 2794587
telemt_user_msgs_to_client{user="hello"} 18379234
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 126227.4 (35h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178892
telemt_connections_bad_total 27649
telemt_handshake_timeouts_total 4460
telemt_upstream_connect_attempt_total 139210
telemt_upstream_connect_success_total 138388
telemt_upstream_connect_fail_total 822
telemt_upstream_connect_attempts_per_request{bucket="1"} 139210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 822
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 138374
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 2060085858 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 107297458711 (99.93 GB)
telemt_user_msgs_from_client{user="hello"} 2874894
telemt_user_msgs_to_client{user="hello"} 14638014
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 26
```