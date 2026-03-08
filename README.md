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

# Server Metrics 2026-03-08 22:17:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 54507.4 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115889
telemt_connections_bad_total 5546
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 105251
telemt_upstream_connect_success_total 105213
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 105251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105207
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2578548798 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 70057403710 (65.25 GB)
telemt_user_msgs_from_client{user="hello"} 2629539
telemt_user_msgs_to_client{user="hello"} 3627468
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 54506.6 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27248
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26352
telemt_upstream_connect_success_total 26345
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26339
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 839606890 (800.71 MB)
telemt_user_octets_to_client{user="hello"} 22767677359 (21.20 GB)
telemt_user_msgs_from_client{user="hello"} 980631
telemt_user_msgs_to_client{user="hello"} 6171807
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 54506.3 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15515
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14102
telemt_upstream_connect_success_total 14026
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14020
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1564603919 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 5692892971 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 701396
telemt_user_msgs_to_client{user="hello"} 977443
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 54506.3 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21301
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20432
telemt_upstream_connect_success_total 20392
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20386
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 1067942415 (1018.47 MB)
telemt_user_octets_to_client{user="hello"} 6592781075 (6.14 GB)
telemt_user_msgs_from_client{user="hello"} 576314
telemt_user_msgs_to_client{user="hello"} 1500727
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 54506.5 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31705
telemt_connections_bad_total 10338
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20620
telemt_upstream_connect_success_total 20613
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20607
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 378891422 (361.34 MB)
telemt_user_octets_to_client{user="hello"} 17775196502 (16.55 GB)
telemt_user_msgs_from_client{user="hello"} 546285
telemt_user_msgs_to_client{user="hello"} 2305620
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```