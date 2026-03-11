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

# Server Metrics 2026-03-11 05:24:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 53913.4 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138232
telemt_connections_bad_total 3408
telemt_handshake_timeouts_total 3013
telemt_upstream_connect_attempt_total 125588
telemt_upstream_connect_success_total 125544
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 125588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125538
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 3110190042 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 88315684764 (82.25 GB)
telemt_user_msgs_from_client{user="hello"} 3263405
telemt_user_msgs_to_client{user="hello"} 6204255
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 53912.6 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56300
telemt_connections_bad_total 437
telemt_handshake_timeouts_total 2973
telemt_upstream_connect_attempt_total 49999
telemt_upstream_connect_success_total 49987
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 49999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49981
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 4504821255 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 47142693736 (43.91 GB)
telemt_user_msgs_from_client{user="hello"} 2692106
telemt_user_msgs_to_client{user="hello"} 11089848
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 53912.4 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77060
telemt_connections_bad_total 718
telemt_handshake_timeouts_total 4323
telemt_upstream_connect_attempt_total 67646
telemt_upstream_connect_success_total 67643
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 67646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67637
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 11791084033 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 71289154469 (66.39 GB)
telemt_user_msgs_from_client{user="hello"} 5201480
telemt_user_msgs_to_client{user="hello"} 13426864
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 53911.3 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80610
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 77172
telemt_upstream_connect_success_total 77003
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 77172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76997
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 1838456753 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 49484116253 (46.09 GB)
telemt_user_msgs_from_client{user="hello"} 1755982
telemt_user_msgs_to_client{user="hello"} 10871840
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 53912.6 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129406
telemt_connections_bad_total 12118
telemt_handshake_timeouts_total 1731
telemt_upstream_connect_attempt_total 108964
telemt_upstream_connect_success_total 108715
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 108964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108709
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2415661116 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 104309239633 (97.15 GB)
telemt_user_msgs_from_client{user="hello"} 2648707
telemt_user_msgs_to_client{user="hello"} 13423135
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32882.1 (9h 8m)
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