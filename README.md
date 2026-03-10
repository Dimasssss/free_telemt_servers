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

# Server Metrics 2026-03-10 23:28:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 32522.9 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98590
telemt_connections_bad_total 3319
telemt_handshake_timeouts_total 2212
telemt_upstream_connect_attempt_total 88722
telemt_upstream_connect_success_total 88690
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 88722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88686
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 2611996561 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 72842155281 (67.84 GB)
telemt_user_msgs_from_client{user="hello"} 2584112
telemt_user_msgs_to_client{user="hello"} 4956150
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 32522.3 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38360
telemt_connections_bad_total 334
telemt_handshake_timeouts_total 881
telemt_upstream_connect_attempt_total 34866
telemt_upstream_connect_success_total 34857
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 34866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34853
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1765049021 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 36775900656 (34.25 GB)
telemt_user_msgs_from_client{user="hello"} 1453652
telemt_user_msgs_to_client{user="hello"} 9156553
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 32522.0 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61077
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 4082
telemt_upstream_connect_attempt_total 53029
telemt_upstream_connect_success_total 53027
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53023
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 853652069 (814.11 MB)
telemt_user_octets_to_client{user="hello"} 53011803785 (49.37 GB)
telemt_user_msgs_from_client{user="hello"} 1160410
telemt_user_msgs_to_client{user="hello"} 7832708
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 32523.7 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56951
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 337
telemt_upstream_connect_attempt_total 54683
telemt_upstream_connect_success_total 54531
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 54683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54527
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 833138611 (794.54 MB)
telemt_user_octets_to_client{user="hello"} 37573029130 (34.99 GB)
telemt_user_msgs_from_client{user="hello"} 1142600
telemt_user_msgs_to_client{user="hello"} 7212982
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32522.3 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83356
telemt_connections_bad_total 7883
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 70817
telemt_upstream_connect_success_total 70569
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 70817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70565
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 2082157996 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57290704378 (53.36 GB)
telemt_user_msgs_from_client{user="hello"} 1978800
telemt_user_msgs_to_client{user="hello"} 8311223
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11491.7 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```