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

# Server Metrics 2026-03-11 08:48:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 66150.1 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188501
telemt_connections_bad_total 3550
telemt_handshake_timeouts_total 4149
telemt_upstream_connect_attempt_total 171939
telemt_upstream_connect_success_total 171885
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 171939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 171877
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 3834144579 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 106521872691 (99.21 GB)
telemt_user_msgs_from_client{user="hello"} 4141360
telemt_user_msgs_to_client{user="hello"} 7748097
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 66149.5 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73216
telemt_connections_bad_total 590
telemt_handshake_timeouts_total 3133
telemt_upstream_connect_attempt_total 66033
telemt_upstream_connect_success_total 66018
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 66033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66012
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 4905017423 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 53408717735 (49.74 GB)
telemt_user_msgs_from_client{user="hello"} 3068877
telemt_user_msgs_to_client{user="hello"} 13618374
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 66149.2 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101246
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 5190
telemt_upstream_connect_attempt_total 89261
telemt_upstream_connect_success_total 89258
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 89261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89250
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 11938986134 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 76184104517 (70.95 GB)
telemt_user_msgs_from_client{user="hello"} 5499927
telemt_user_msgs_to_client{user="hello"} 14899578
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 66148.1 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112504
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 1034
telemt_upstream_connect_attempt_total 106876
telemt_upstream_connect_success_total 106634
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 106876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106626
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 4538171909 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 73065174834 (68.05 GB)
telemt_user_msgs_from_client{user="hello"} 3141955
telemt_user_msgs_to_client{user="hello"} 18548330
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 66149.4 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180884
telemt_connections_bad_total 14541
telemt_handshake_timeouts_total 3082
telemt_upstream_connect_attempt_total 144014
telemt_upstream_connect_success_total 143613
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 144014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 143607
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2865163639 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 132027087958 (122.96 GB)
telemt_user_msgs_from_client{user="hello"} 3241885
telemt_user_msgs_to_client{user="hello"} 17057794
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 45118.8 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412
telemt_connections_bad_total 390
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```