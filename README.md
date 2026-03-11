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

# Server Metrics 2026-03-11 04:08:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 49328.6 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125547
telemt_connections_bad_total 3382
telemt_handshake_timeouts_total 2645
telemt_upstream_connect_attempt_total 113882
telemt_upstream_connect_success_total 113842
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 113882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113836
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 2992869789 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 83885447767 (78.12 GB)
telemt_user_msgs_from_client{user="hello"} 3059017
telemt_user_msgs_to_client{user="hello"} 5828655
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 49327.9 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51806
telemt_connections_bad_total 401
telemt_handshake_timeouts_total 2940
telemt_upstream_connect_attempt_total 45730
telemt_upstream_connect_success_total 45720
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 45730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45714
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 2330012554 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 44144303447 (41.11 GB)
telemt_user_msgs_from_client{user="hello"} 1823621
telemt_user_msgs_to_client{user="hello"} 10508868
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 49327.6 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72517
telemt_connections_bad_total 672
telemt_handshake_timeouts_total 4235
telemt_upstream_connect_attempt_total 63578
telemt_upstream_connect_success_total 63575
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 63577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63569
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 11762829115 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 70769938183 (65.91 GB)
telemt_user_msgs_from_client{user="hello"} 5157137
telemt_user_msgs_to_client{user="hello"} 13267528
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 49326.4 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74060
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 562
telemt_upstream_connect_attempt_total 70885
telemt_upstream_connect_success_total 70725
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 70885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70719
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1786990929 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 43303630500 (40.33 GB)
telemt_user_msgs_from_client{user="hello"} 1642656
telemt_user_msgs_to_client{user="hello"} 8529077
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 49327.8 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117214
telemt_connections_bad_total 11161
telemt_handshake_timeouts_total 1655
telemt_upstream_connect_attempt_total 99915
telemt_upstream_connect_success_total 99667
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 99915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99661
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2288116657 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 92437593861 (86.09 GB)
telemt_user_msgs_from_client{user="hello"} 2437007
telemt_user_msgs_to_client{user="hello"} 11894488
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28297.2 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```