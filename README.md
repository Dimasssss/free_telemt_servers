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

# Server Metrics 2026-03-08 19:12:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 43404.5 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99924
telemt_connections_bad_total 5056
telemt_handshake_timeouts_total 1256
telemt_upstream_connect_attempt_total 90356
telemt_upstream_connect_success_total 90325
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 90356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90319
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 2205783701 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 56187557896 (52.33 GB)
telemt_user_msgs_from_client{user="hello"} 2195823
telemt_user_msgs_to_client{user="hello"} 3083353
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 43403.7 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22817
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 22090
telemt_upstream_connect_success_total 22085
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22081
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 741891625 (707.52 MB)
telemt_user_octets_to_client{user="hello"} 20535781782 (19.13 GB)
telemt_user_msgs_from_client{user="hello"} 869734
telemt_user_msgs_to_client{user="hello"} 5594635
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 43403.4 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13867
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12540
telemt_upstream_connect_success_total 12464
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12460
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 242328370 (231.10 MB)
telemt_user_octets_to_client{user="hello"} 4260454856 (3.97 GB)
telemt_user_msgs_from_client{user="hello"} 209688
telemt_user_msgs_to_client{user="hello"} 767638
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 43403.3 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17837
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17076
telemt_upstream_connect_success_total 17040
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 17076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17036
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 1039663711 (991.50 MB)
telemt_user_octets_to_client{user="hello"} 6016450530 (5.60 GB)
telemt_user_msgs_from_client{user="hello"} 543638
telemt_user_msgs_to_client{user="hello"} 1364123
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 43403.6 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25539
telemt_connections_bad_total 8212
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 16697
telemt_upstream_connect_success_total 16690
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16684
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 314952157 (300.36 MB)
telemt_user_octets_to_client{user="hello"} 12852246947 (11.97 GB)
telemt_user_msgs_from_client{user="hello"} 412382
telemt_user_msgs_to_client{user="hello"} 1698546
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```