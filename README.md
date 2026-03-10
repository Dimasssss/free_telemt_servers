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

# Server Metrics 2026-03-10 22:57:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30690.7 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96712
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2209
telemt_upstream_connect_attempt_total 86924
telemt_upstream_connect_success_total 86892
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 86924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86888
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2577044764 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 70735012239 (65.88 GB)
telemt_user_msgs_from_client{user="hello"} 2531205
telemt_user_msgs_to_client{user="hello"} 4781073
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30689.9 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37247
telemt_connections_bad_total 332
telemt_handshake_timeouts_total 824
telemt_upstream_connect_attempt_total 33861
telemt_upstream_connect_success_total 33852
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33848
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1695398427 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 35697466307 (33.25 GB)
telemt_user_msgs_from_client{user="hello"} 1395898
telemt_user_msgs_to_client{user="hello"} 8956799
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30689.8 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59832
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 4062
telemt_upstream_connect_attempt_total 51861
telemt_upstream_connect_success_total 51859
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51855
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 788816554 (752.27 MB)
telemt_user_octets_to_client{user="hello"} 49327230641 (45.94 GB)
telemt_user_msgs_from_client{user="hello"} 1103058
telemt_user_msgs_to_client{user="hello"} 7353210
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30688.4 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55102
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 52899
telemt_upstream_connect_success_total 52748
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 52899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52744
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 827282823 (788.96 MB)
telemt_user_octets_to_client{user="hello"} 37407398693 (34.84 GB)
telemt_user_msgs_from_client{user="hello"} 1127896
telemt_user_msgs_to_client{user="hello"} 7159915
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30689.8 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80983
telemt_connections_bad_total 7522
telemt_handshake_timeouts_total 1462
telemt_upstream_connect_attempt_total 68861
telemt_upstream_connect_success_total 68613
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 68861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68609
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 2065757158 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 55145772002 (51.36 GB)
telemt_user_msgs_from_client{user="hello"} 1936090
telemt_user_msgs_to_client{user="hello"} 8097817
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9659.1 (2h 40m)
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