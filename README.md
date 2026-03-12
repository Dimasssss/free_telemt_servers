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

# Server Metrics 2026-03-12 06:09:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30272.9 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79055
telemt_connections_bad_total 2109
telemt_handshake_timeouts_total 2261
telemt_upstream_connect_attempt_total 71095
telemt_upstream_connect_success_total 71050
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 71095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71046
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 724899797 (691.32 MB)
telemt_user_octets_to_client{user="hello"} 21563885659 (20.08 GB)
telemt_user_msgs_from_client{user="hello"} 1079144
telemt_user_msgs_to_client{user="hello"} 2493942
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30261.1 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31691
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 159
telemt_upstream_connect_attempt_total 30198
telemt_upstream_connect_success_total 30184
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 30198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30180
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 281436593 (268.40 MB)
telemt_user_octets_to_client{user="hello"} 15237873644 (14.19 GB)
telemt_user_msgs_from_client{user="hello"} 560119
telemt_user_msgs_to_client{user="hello"} 4754474
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30234.6 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48756
telemt_connections_bad_total 674
telemt_handshake_timeouts_total 1061
telemt_upstream_connect_attempt_total 43980
telemt_upstream_connect_success_total 43967
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 43980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43963
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 5377009778 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 27427189016 (25.54 GB)
telemt_user_msgs_from_client{user="hello"} 2629059
telemt_user_msgs_to_client{user="hello"} 4920616
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30259.9 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53594
telemt_connections_bad_total 12927
telemt_handshake_timeouts_total 847
telemt_upstream_connect_attempt_total 37798
telemt_upstream_connect_success_total 36084
telemt_upstream_connect_fail_total 1714
telemt_upstream_connect_attempts_per_request{bucket="1"} 37798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1714
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36080
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1222034339 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 23668788913 (22.04 GB)
telemt_user_msgs_from_client{user="hello"} 953158
telemt_user_msgs_to_client{user="hello"} 9797944
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 452.5 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 997
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 839
telemt_upstream_connect_success_total 833
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 831
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 29538206 (28.17 MB)
telemt_user_octets_to_client{user="hello"} 561829603 (535.80 MB)
telemt_user_msgs_from_client{user="hello"} 22027
telemt_user_msgs_to_client{user="hello"} 67908
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30260.9 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48457
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 45122
telemt_upstream_connect_success_total 45103
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 45121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45099
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 822679876 (784.57 MB)
telemt_user_octets_to_client{user="hello"} 42060645423 (39.17 GB)
telemt_user_msgs_from_client{user="hello"} 1194411
telemt_user_msgs_to_client{user="hello"} 5589282
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 42
```