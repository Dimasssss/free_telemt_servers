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

# Server Metrics 2026-03-11 01:45:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 40771.5 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110284
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2537
telemt_upstream_connect_attempt_total 99358
telemt_upstream_connect_success_total 99322
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 99358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99318
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2762074831 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 79191728412 (73.75 GB)
telemt_user_msgs_from_client{user="hello"} 2823723
telemt_user_msgs_to_client{user="hello"} 5445347
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 40771.2 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45407
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 2008
telemt_upstream_connect_attempt_total 40485
telemt_upstream_connect_success_total 40476
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 40485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40472
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 2025418662 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 38798702891 (36.13 GB)
telemt_user_msgs_from_client{user="hello"} 1623211
telemt_user_msgs_to_client{user="hello"} 9636873
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 40770.9 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66788
telemt_connections_bad_total 630
telemt_handshake_timeouts_total 4133
telemt_upstream_connect_attempt_total 58250
telemt_upstream_connect_success_total 58248
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58244
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 10520889745 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 67538150049 (62.90 GB)
telemt_user_msgs_from_client{user="hello"} 4668886
telemt_user_msgs_to_client{user="hello"} 12343450
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 40769.8 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65299
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 536
telemt_upstream_connect_attempt_total 62473
telemt_upstream_connect_success_total 62318
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 62473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62314
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 1746478333 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42508081669 (39.59 GB)
telemt_user_msgs_from_client{user="hello"} 1564936
telemt_user_msgs_to_client{user="hello"} 8306620
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 40771.1 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94308
telemt_connections_bad_total 9502
telemt_handshake_timeouts_total 1500
telemt_upstream_connect_attempt_total 79846
telemt_upstream_connect_success_total 79598
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 79846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79594
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 2139915700 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 64042265434 (59.64 GB)
telemt_user_msgs_from_client{user="hello"} 2120236
telemt_user_msgs_to_client{user="hello"} 9210068
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19740.6 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```