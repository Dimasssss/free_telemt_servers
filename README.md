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

# Server Metrics 2026-03-11 06:15:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 56971.1 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151688
telemt_connections_bad_total 3497
telemt_handshake_timeouts_total 3878
telemt_upstream_connect_attempt_total 136678
telemt_upstream_connect_success_total 136634
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 136678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136628
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 3344443206 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 92247030462 (85.91 GB)
telemt_user_msgs_from_client{user="hello"} 3490271
telemt_user_msgs_to_client{user="hello"} 6512843
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 56970.5 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59883
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 3024
telemt_upstream_connect_attempt_total 53372
telemt_upstream_connect_success_total 53360
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 53372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53354
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 4584333730 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 47919011471 (44.63 GB)
telemt_user_msgs_from_client{user="hello"} 2781245
telemt_user_msgs_to_client{user="hello"} 11362537
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 56970.2 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81377
telemt_connections_bad_total 737
telemt_handshake_timeouts_total 4364
telemt_upstream_connect_attempt_total 71715
telemt_upstream_connect_success_total 71712
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 71715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71706
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 11809677691 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 72265729203 (67.30 GB)
telemt_user_msgs_from_client{user="hello"} 5244736
telemt_user_msgs_to_client{user="hello"} 13650115
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 56969.1 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86814
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 634
telemt_upstream_connect_attempt_total 83096
telemt_upstream_connect_success_total 82912
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 83096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82906
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 1893383876 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 55344282462 (51.54 GB)
telemt_user_msgs_from_client{user="hello"} 1872549
telemt_user_msgs_to_client{user="hello"} 13015576
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 56970.5 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148818
telemt_connections_bad_total 12666
telemt_handshake_timeouts_total 1787
telemt_upstream_connect_attempt_total 116946
telemt_upstream_connect_success_total 116696
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 116945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116690
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 2468591071 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 110301806606 (102.73 GB)
telemt_user_msgs_from_client{user="hello"} 2768330
telemt_user_msgs_to_client{user="hello"} 14632267
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35939.8 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166
telemt_connections_bad_total 146
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