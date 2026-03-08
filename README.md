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

# Server Metrics 2026-03-08 18:20:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 40323.7 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95032
telemt_connections_bad_total 5047
telemt_handshake_timeouts_total 1242
telemt_upstream_connect_attempt_total 85583
telemt_upstream_connect_success_total 85554
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 85583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85548
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2049693553 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 53410530028 (49.74 GB)
telemt_user_msgs_from_client{user="hello"} 2051239
telemt_user_msgs_to_client{user="hello"} 2920462
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 40322.9 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21277
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 20583
telemt_upstream_connect_success_total 20578
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 20583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20574
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 723973744 (690.44 MB)
telemt_user_octets_to_client{user="hello"} 19464804076 (18.13 GB)
telemt_user_msgs_from_client{user="hello"} 832475
telemt_user_msgs_to_client{user="hello"} 5333528
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 40322.6 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13072
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 11757
telemt_upstream_connect_success_total 11681
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11677
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 236183116 (225.24 MB)
telemt_user_octets_to_client{user="hello"} 4189478538 (3.90 GB)
telemt_user_msgs_from_client{user="hello"} 202538
telemt_user_msgs_to_client{user="hello"} 744066
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 40322.4 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16735
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 16001
telemt_upstream_connect_success_total 15967
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 16001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15963
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 1021076438 (973.77 MB)
telemt_user_octets_to_client{user="hello"} 5765807357 (5.37 GB)
telemt_user_msgs_from_client{user="hello"} 531571
telemt_user_msgs_to_client{user="hello"} 1306619
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 40322.7 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23772
telemt_connections_bad_total 7649
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 15531
telemt_upstream_connect_success_total 15526
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15522
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 271629253 (259.05 MB)
telemt_user_octets_to_client{user="hello"} 11987431123 (11.16 GB)
telemt_user_msgs_from_client{user="hello"} 370337
telemt_user_msgs_to_client{user="hello"} 1574680
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```