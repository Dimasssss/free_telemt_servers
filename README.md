# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

# Server Metrics 2026-03-10 19:05:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16784.3 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65545
telemt_connections_bad_total 2069
telemt_handshake_timeouts_total 1828
telemt_upstream_connect_attempt_total 58443
telemt_upstream_connect_success_total 58431
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 58443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58429
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 1919723105 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 43338182700 (40.36 GB)
telemt_user_msgs_from_client{user="hello"} 1733515
telemt_user_msgs_to_client{user="hello"} 3264984
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16783.6 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24907
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 425
telemt_upstream_connect_attempt_total 22747
telemt_upstream_connect_success_total 22740
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 22747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22738
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 765465461 (730.00 MB)
telemt_user_octets_to_client{user="hello"} 13350766310 (12.43 GB)
telemt_user_msgs_from_client{user="hello"} 712247
telemt_user_msgs_to_client{user="hello"} 4168917
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16783.0 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38275
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 3314
telemt_upstream_connect_attempt_total 32490
telemt_upstream_connect_success_total 32490
telemt_upstream_connect_attempts_per_request{bucket="1"} 32490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32488
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 522510139 (498.30 MB)
telemt_user_octets_to_client{user="hello"} 33214957067 (30.93 GB)
telemt_user_msgs_from_client{user="hello"} 719053
telemt_user_msgs_to_client{user="hello"} 4865702
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16782.0 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35873
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 270
telemt_upstream_connect_attempt_total 34349
telemt_upstream_connect_success_total 34249
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 34348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34247
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 587336609 (560.13 MB)
telemt_user_octets_to_client{user="hello"} 28334687020 (26.39 GB)
telemt_user_msgs_from_client{user="hello"} 727603
telemt_user_msgs_to_client{user="hello"} 5110007
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16783.4 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52608
telemt_connections_bad_total 4760
telemt_handshake_timeouts_total 1190
telemt_upstream_connect_attempt_total 44516
telemt_upstream_connect_success_total 44274
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 44516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44272
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 1457026957 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 30875158238 (28.75 GB)
telemt_user_msgs_from_client{user="hello"} 1251358
telemt_user_msgs_to_client{user="hello"} 4634860
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```