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

# Server Metrics 2026-03-11 05:34:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 54524.9 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140586
telemt_connections_bad_total 3410
telemt_handshake_timeouts_total 3183
telemt_upstream_connect_attempt_total 127654
telemt_upstream_connect_success_total 127610
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 127654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 127604
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 3125406909 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 88842903404 (82.74 GB)
telemt_user_msgs_from_client{user="hello"} 3294702
telemt_user_msgs_to_client{user="hello"} 6258801
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 54524.4 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57127
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 2976
telemt_upstream_connect_attempt_total 50788
telemt_upstream_connect_success_total 50776
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 50788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50770
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 4512509003 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 47391176277 (44.14 GB)
telemt_user_msgs_from_client{user="hello"} 2712392
telemt_user_msgs_to_client{user="hello"} 11187805
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 54524.1 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77704
telemt_connections_bad_total 719
telemt_handshake_timeouts_total 4324
telemt_upstream_connect_attempt_total 68267
telemt_upstream_connect_success_total 68264
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 68267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68258
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 11794222161 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 71420807791 (66.52 GB)
telemt_user_msgs_from_client{user="hello"} 5209811
telemt_user_msgs_to_client{user="hello"} 13452850
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 54523.1 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81830
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 603
telemt_upstream_connect_attempt_total 78338
telemt_upstream_connect_success_total 78167
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 78337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78161
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 1844518531 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 49747028803 (46.33 GB)
telemt_user_msgs_from_client{user="hello"} 1769899
telemt_user_msgs_to_client{user="hello"} 10929241
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 54524.4 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132438
telemt_connections_bad_total 12228
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 110580
telemt_upstream_connect_success_total 110331
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 110580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110325
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 2427929264 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 106279821068 (98.98 GB)
telemt_user_msgs_from_client{user="hello"} 2677471
telemt_user_msgs_to_client{user="hello"} 13772246
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33493.8 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```