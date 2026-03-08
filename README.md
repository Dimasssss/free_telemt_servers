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

# Server Metrics 2026-03-08 15:15:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 29230.4 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71375
telemt_connections_bad_total 5024
telemt_handshake_timeouts_total 1043
telemt_upstream_connect_attempt_total 62731
telemt_upstream_connect_success_total 62708
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 62731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62704
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1667716178 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 32651231940 (30.41 GB)
telemt_user_msgs_from_client{user="hello"} 1484045
telemt_user_msgs_to_client{user="hello"} 1969584
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 29229.9 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15358
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 14837
telemt_upstream_connect_success_total 14836
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14832
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 565285421 (539.10 MB)
telemt_user_octets_to_client{user="hello"} 12853501922 (11.97 GB)
telemt_user_msgs_from_client{user="hello"} 571358
telemt_user_msgs_to_client{user="hello"} 3372782
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 29229.6 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9789
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9163
telemt_upstream_connect_success_total 9087
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9083
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 206677829 (197.10 MB)
telemt_user_octets_to_client{user="hello"} 3038042775 (2.83 GB)
telemt_user_msgs_from_client{user="hello"} 152887
telemt_user_msgs_to_client{user="hello"} 525838
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 29229.4 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12636
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 12056
telemt_upstream_connect_success_total 12028
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12024
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 945471644 (901.67 MB)
telemt_user_octets_to_client{user="hello"} 4553085473 (4.24 GB)
telemt_user_msgs_from_client{user="hello"} 464188
telemt_user_msgs_to_client{user="hello"} 1024796
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 29229.6 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16612
telemt_connections_bad_total 5382
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 10869
telemt_upstream_connect_success_total 10865
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10861
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 232138262 (221.38 MB)
telemt_user_octets_to_client{user="hello"} 8379300252 (7.80 GB)
telemt_user_msgs_from_client{user="hello"} 279910
telemt_user_msgs_to_client{user="hello"} 1173872
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```