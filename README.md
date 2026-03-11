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

# Server Metrics 2026-03-11 07:11:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 60334.4 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164044
telemt_connections_bad_total 3510
telemt_handshake_timeouts_total 3982
telemt_upstream_connect_attempt_total 148375
telemt_upstream_connect_success_total 148328
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 148375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148320
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 3529007735 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 98219701565 (91.47 GB)
telemt_user_msgs_from_client{user="hello"} 3738013
telemt_user_msgs_to_client{user="hello"} 7020984
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 60333.8 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64673
telemt_connections_bad_total 456
telemt_handshake_timeouts_total 3067
telemt_upstream_connect_attempt_total 57970
telemt_upstream_connect_success_total 57956
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 57970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57950
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 4659945832 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 49990732864 (46.56 GB)
telemt_user_msgs_from_client{user="hello"} 2874147
telemt_user_msgs_to_client{user="hello"} 12129456
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 60333.4 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87445
telemt_connections_bad_total 743
telemt_handshake_timeouts_total 4444
telemt_upstream_connect_attempt_total 76995
telemt_upstream_connect_success_total 76992
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 76995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76986
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 11854354253 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 74257601617 (69.16 GB)
telemt_user_msgs_from_client{user="hello"} 5327889
telemt_user_msgs_to_client{user="hello"} 14222787
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 60332.2 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94835
telemt_connections_bad_total 216
telemt_handshake_timeouts_total 655
telemt_upstream_connect_attempt_total 90876
telemt_upstream_connect_success_total 90674
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 90876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 254
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90668
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2096736094 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 60764012488 (56.59 GB)
telemt_user_msgs_from_client{user="hello"} 2065278
telemt_user_msgs_to_client{user="hello"} 14961669
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 60333.7 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160217
telemt_connections_bad_total 13328
telemt_handshake_timeouts_total 1834
telemt_upstream_connect_attempt_total 127201
telemt_upstream_connect_success_total 126952
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 127201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126946
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2556283060 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 122882723953 (114.44 GB)
telemt_user_msgs_from_client{user="hello"} 2940891
telemt_user_msgs_to_client{user="hello"} 15698020
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 39303.1 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```