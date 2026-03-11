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

# Server Metrics 2026-03-11 14:06:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 85197.9 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279461
telemt_connections_bad_total 3676
telemt_handshake_timeouts_total 4769
telemt_upstream_connect_attempt_total 258486
telemt_upstream_connect_success_total 258409
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 258486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 236515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 258399
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 4973614353 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 132503636135 (123.40 GB)
telemt_user_msgs_from_client{user="hello"} 5734864
telemt_user_msgs_to_client{user="hello"} 10474078
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 85197.0 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109753
telemt_connections_bad_total 921
telemt_handshake_timeouts_total 3351
telemt_upstream_connect_attempt_total 100668
telemt_upstream_connect_success_total 100649
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 100668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 431
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100641
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 5425273702 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 66746868612 (62.16 GB)
telemt_user_msgs_from_client{user="hello"} 3685710
telemt_user_msgs_to_client{user="hello"} 18974938
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 85196.8 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153254
telemt_connections_bad_total 1250
telemt_handshake_timeouts_total 6884
telemt_upstream_connect_attempt_total 136588
telemt_upstream_connect_success_total 136574
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 136588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136566
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 12647083761 (11.78 GB)
telemt_user_octets_to_client{user="hello"} 124435804490 (115.89 GB)
telemt_user_msgs_from_client{user="hello"} 6628428
telemt_user_msgs_to_client{user="hello"} 27541495
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 85195.6 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169733
telemt_connections_bad_total 5798
telemt_handshake_timeouts_total 1934
telemt_upstream_connect_attempt_total 155106
telemt_upstream_connect_success_total 154730
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 155105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 154720
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 9275231229 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 109858346102 (102.31 GB)
telemt_user_msgs_from_client{user="hello"} 5522193
telemt_user_msgs_to_client{user="hello"} 32509034
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 85196.9 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245148
telemt_connections_bad_total 18867
telemt_handshake_timeouts_total 6160
telemt_upstream_connect_attempt_total 198523
telemt_upstream_connect_success_total 198020
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 198523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 171343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 198012
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 4890275254 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 156735288882 (145.97 GB)
telemt_user_msgs_from_client{user="hello"} 4658078
telemt_user_msgs_to_client{user="hello"} 21715179
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 64166.3 (17h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 10
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