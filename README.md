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

# Server Metrics 2026-03-12 07:15:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34268.3 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100069
telemt_connections_bad_total 2191
telemt_handshake_timeouts_total 2564
telemt_upstream_connect_attempt_total 90672
telemt_upstream_connect_success_total 90299
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 90671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90295
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 951774917 (907.68 MB)
telemt_user_octets_to_client{user="hello"} 26337152176 (24.53 GB)
telemt_user_msgs_from_client{user="hello"} 1361377
telemt_user_msgs_to_client{user="hello"} 3029783
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34256.3 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40669
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 558
telemt_upstream_connect_attempt_total 38522
telemt_upstream_connect_success_total 38392
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 38522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38388
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 327382153 (312.22 MB)
telemt_user_octets_to_client{user="hello"} 16733713471 (15.58 GB)
telemt_user_msgs_from_client{user="hello"} 652799
telemt_user_msgs_to_client{user="hello"} 5368295
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34229.8 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60060
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 1145
telemt_upstream_connect_attempt_total 54375
telemt_upstream_connect_success_total 54256
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 54374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54252
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 5498732461 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 31505233091 (29.34 GB)
telemt_user_msgs_from_client{user="hello"} 2794381
telemt_user_msgs_to_client{user="hello"} 5635241
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34255.1 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65870
telemt_connections_bad_total 13721
telemt_handshake_timeouts_total 933
telemt_upstream_connect_attempt_total 48452
telemt_upstream_connect_success_total 46621
telemt_upstream_connect_fail_total 1831
telemt_upstream_connect_attempts_per_request{bucket="1"} 48452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1831
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46617
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1455055240 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 37709811303 (35.12 GB)
telemt_user_msgs_from_client{user="hello"} 1240704
telemt_user_msgs_to_client{user="hello"} 14992408
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4447.6 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7350
telemt_connections_bad_total 821
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 6181
telemt_upstream_connect_success_total 6094
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 6181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6092
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 181019382 (172.63 MB)
telemt_user_octets_to_client{user="hello"} 5092954778 (4.74 GB)
telemt_user_msgs_from_client{user="hello"} 174010
telemt_user_msgs_to_client{user="hello"} 776360
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34256.0 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63919
telemt_connections_bad_total 1075
telemt_handshake_timeouts_total 347
telemt_upstream_connect_attempt_total 59798
telemt_upstream_connect_success_total 59591
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 59797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59587
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 1036069243 (988.07 MB)
telemt_user_octets_to_client{user="hello"} 51247180770 (47.73 GB)
telemt_user_msgs_from_client{user="hello"} 1475687
telemt_user_msgs_to_client{user="hello"} 6637740
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 46
```