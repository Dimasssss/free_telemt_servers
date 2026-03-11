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

# Server Metrics 2026-03-11 06:51:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 59110.5 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159603
telemt_connections_bad_total 3503
telemt_handshake_timeouts_total 3942
telemt_upstream_connect_attempt_total 144128
telemt_upstream_connect_success_total 144083
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 144128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 144077
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 3449850130 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 95102692561 (88.57 GB)
telemt_user_msgs_from_client{user="hello"} 3636594
telemt_user_msgs_to_client{user="hello"} 6778267
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 59109.8 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62968
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 3048
telemt_upstream_connect_attempt_total 56347
telemt_upstream_connect_success_total 56335
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 56347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56329
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 4651985841 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 49481357412 (46.08 GB)
telemt_user_msgs_from_client{user="hello"} 2854908
telemt_user_msgs_to_client{user="hello"} 11910436
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 59109.4 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84659
telemt_connections_bad_total 740
telemt_handshake_timeouts_total 4416
telemt_upstream_connect_attempt_total 74778
telemt_upstream_connect_success_total 74775
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 74778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74769
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 11841808957 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 73351079502 (68.31 GB)
telemt_user_msgs_from_client{user="hello"} 5292996
telemt_user_msgs_to_client{user="hello"} 13967028
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 59108.4 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91913
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 644
telemt_upstream_connect_attempt_total 88018
telemt_upstream_connect_success_total 87821
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 88018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87815
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1987738917 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 59211110496 (55.14 GB)
telemt_user_msgs_from_client{user="hello"} 1984505
telemt_user_msgs_to_client{user="hello"} 14543982
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 59109.7 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155783
telemt_connections_bad_total 13102
telemt_handshake_timeouts_total 1816
telemt_upstream_connect_attempt_total 123187
telemt_upstream_connect_success_total 122938
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 123187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122932
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 2521758166 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 118500095093 (110.36 GB)
telemt_user_msgs_from_client{user="hello"} 2875925
telemt_user_msgs_to_client{user="hello"} 15333501
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 38079.1 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167
telemt_connections_bad_total 147
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