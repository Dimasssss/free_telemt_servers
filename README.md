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

# Server Metrics 2026-03-10 07:55:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 117324.7 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230774
telemt_connections_bad_total 2459
telemt_handshake_timeouts_total 2042
telemt_upstream_connect_attempt_total 217184
telemt_upstream_connect_success_total 217118
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 217184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 200203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 217106
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 5560929948 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 130649627675 (121.68 GB)
telemt_user_msgs_from_client{user="hello"} 5349038
telemt_user_msgs_to_client{user="hello"} 8201567
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 117323.6 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69214
telemt_connections_bad_total 3219
telemt_handshake_timeouts_total 998
telemt_upstream_connect_attempt_total 61384
telemt_upstream_connect_success_total 61343
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 61384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61331
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 2251281845 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 27148116829 (25.28 GB)
telemt_user_msgs_from_client{user="hello"} 1747516
telemt_user_msgs_to_client{user="hello"} 7896629
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 117324.6 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101690
telemt_connections_bad_total 1122
telemt_handshake_timeouts_total 4833
telemt_upstream_connect_attempt_total 70389
telemt_upstream_connect_success_total 70387
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 70389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70375
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 6242172872 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 59676418193 (55.58 GB)
telemt_user_msgs_from_client{user="hello"} 3876443
telemt_user_msgs_to_client{user="hello"} 9428791
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 117319.0 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99296
telemt_connections_bad_total 900
telemt_handshake_timeouts_total 1208
telemt_upstream_connect_attempt_total 92171
telemt_upstream_connect_success_total 91974
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 92171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91962
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2551762722 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 66839589437 (62.25 GB)
telemt_user_msgs_from_client{user="hello"} 2362268
telemt_user_msgs_to_client{user="hello"} 15329812
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 117324.3 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156109
telemt_connections_bad_total 25547
telemt_handshake_timeouts_total 4064
telemt_upstream_connect_attempt_total 119896
telemt_upstream_connect_success_total 119102
telemt_upstream_connect_fail_total 794
telemt_upstream_connect_attempts_per_request{bucket="1"} 119896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 794
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119090
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 1858019126 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 102764057178 (95.71 GB)
telemt_user_msgs_from_client{user="hello"} 2597359
telemt_user_msgs_to_client{user="hello"} 13825592
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```