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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 06:14:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30579.8 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80488
telemt_connections_bad_total 2117
telemt_handshake_timeouts_total 2274
telemt_upstream_connect_attempt_total 72464
telemt_upstream_connect_success_total 72415
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 72464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72411
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 735430702 (701.36 MB)
telemt_user_octets_to_client{user="hello"} 21796254850 (20.30 GB)
telemt_user_msgs_from_client{user="hello"} 1100642
telemt_user_msgs_to_client{user="hello"} 2531355
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30568.3 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32326
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 30824
telemt_upstream_connect_success_total 30810
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 30824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30806
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 284717039 (271.53 MB)
telemt_user_octets_to_client{user="hello"} 15348815663 (14.29 GB)
telemt_user_msgs_from_client{user="hello"} 566641
telemt_user_msgs_to_client{user="hello"} 4802511
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30541.8 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49545
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 1062
telemt_upstream_connect_attempt_total 44721
telemt_upstream_connect_success_total 44706
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 44721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44702
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 5380417336 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 27594725288 (25.70 GB)
telemt_user_msgs_from_client{user="hello"} 2639616
telemt_user_msgs_to_client{user="hello"} 4955218
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30567.2 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54218
telemt_connections_bad_total 12927
telemt_handshake_timeouts_total 860
telemt_upstream_connect_attempt_total 38360
telemt_upstream_connect_success_total 36645
telemt_upstream_connect_fail_total 1714
telemt_upstream_connect_attempts_per_request{bucket="1"} 38359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1714
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36641
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 1226625964 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 24153265061 (22.49 GB)
telemt_user_msgs_from_client{user="hello"} 965286
telemt_user_msgs_to_client{user="hello"} 10008715
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 759.4 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1347
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 1110
telemt_upstream_connect_success_total 1101
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1099
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 100255280 (95.61 MB)
telemt_user_octets_to_client{user="hello"} 573190646 (546.64 MB)
telemt_user_msgs_from_client{user="hello"} 48064
telemt_user_msgs_to_client{user="hello"} 72370
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30568.0 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49506
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 46136
telemt_upstream_connect_success_total 46114
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 46136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46110
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 829787476 (791.35 MB)
telemt_user_octets_to_client{user="hello"} 42517605241 (39.60 GB)
telemt_user_msgs_from_client{user="hello"} 1213923
telemt_user_msgs_to_client{user="hello"} 5648797
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```