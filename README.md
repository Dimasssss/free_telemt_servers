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

# Server Metrics 2026-03-09 18:47:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 70043.2 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133232
telemt_connections_bad_total 1800
telemt_handshake_timeouts_total 1113
telemt_upstream_connect_attempt_total 124718
telemt_upstream_connect_success_total 124675
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 124718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 124667
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 3527228798 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 69215930945 (64.46 GB)
telemt_user_msgs_from_client{user="hello"} 3181597
telemt_user_msgs_to_client{user="hello"} 4413536
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 70041.9 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38717
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 454
telemt_upstream_connect_attempt_total 36341
telemt_upstream_connect_success_total 36320
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 36341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36312
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1081352838 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 17901843478 (16.67 GB)
telemt_user_msgs_from_client{user="hello"} 969347
telemt_user_msgs_to_client{user="hello"} 5048963
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 70042.5 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48383
telemt_connections_bad_total 699
telemt_handshake_timeouts_total 2410
telemt_upstream_connect_attempt_total 37786
telemt_upstream_connect_success_total 37786
telemt_upstream_connect_attempts_per_request{bucket="1"} 37786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37778
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 4655049000 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 27586470094 (25.69 GB)
telemt_user_msgs_from_client{user="hello"} 2294144
telemt_user_msgs_to_client{user="hello"} 3931590
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 70037.4 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54399
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 916
telemt_upstream_connect_attempt_total 49805
telemt_upstream_connect_success_total 49678
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 49805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49670
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 2108885480 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 38622829087 (35.97 GB)
telemt_user_msgs_from_client{user="hello"} 1500668
telemt_user_msgs_to_client{user="hello"} 9306560
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 70042.8 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87906
telemt_connections_bad_total 16515
telemt_handshake_timeouts_total 2266
telemt_upstream_connect_attempt_total 65207
telemt_upstream_connect_success_total 65205
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 65207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65197
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 1131293628 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 59315778580 (55.24 GB)
telemt_user_msgs_from_client{user="hello"} 1499116
telemt_user_msgs_to_client{user="hello"} 7697958
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```