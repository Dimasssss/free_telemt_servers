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

# Server Metrics 2026-03-08 08:34:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 5163.9 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10771
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 8830
telemt_upstream_connect_success_total 8825
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8823
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 252198056 (240.51 MB)
telemt_user_octets_to_client{user="hello"} 5683752186 (5.29 GB)
telemt_user_msgs_from_client{user="hello"} 209735
telemt_user_msgs_to_client{user="hello"} 279610
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 5163.2 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2356
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2234
telemt_upstream_connect_success_total 2234
telemt_upstream_connect_attempts_per_request{bucket="1"} 2234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2232
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 29379584 (28.02 MB)
telemt_user_octets_to_client{user="hello"} 1395999176 (1.30 GB)
telemt_user_msgs_from_client{user="hello"} 51219
telemt_user_msgs_to_client{user="hello"} 335047
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 5162.9 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2029
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1983
telemt_upstream_connect_success_total 1983
telemt_upstream_connect_attempts_per_request{bucket="1"} 1983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1981
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 24939356 (23.78 MB)
telemt_user_octets_to_client{user="hello"} 448940527 (428.14 MB)
telemt_user_msgs_from_client{user="hello"} 18718
telemt_user_msgs_to_client{user="hello"} 80305
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 5162.9 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1944
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1877
telemt_upstream_connect_success_total 1874
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1872
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 45254170 (43.16 MB)
telemt_user_octets_to_client{user="hello"} 491683105 (468.91 MB)
telemt_user_msgs_from_client{user="hello"} 29815
telemt_user_msgs_to_client{user="hello"} 140933
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 5163.1 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3323
telemt_connections_bad_total 925
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2369
telemt_upstream_connect_success_total 2369
telemt_upstream_connect_attempts_per_request{bucket="1"} 2369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2367
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 23552231 (22.46 MB)
telemt_user_octets_to_client{user="hello"} 659942054 (629.37 MB)
telemt_user_msgs_from_client{user="hello"} 37118
telemt_user_msgs_to_client{user="hello"} 120399
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```