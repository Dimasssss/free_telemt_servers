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

# Server Metrics 2026-03-11 00:08:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34967.7 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101874
telemt_connections_bad_total 3327
telemt_handshake_timeouts_total 2487
telemt_upstream_connect_attempt_total 91545
telemt_upstream_connect_success_total 91513
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 91545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91509
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2670209250 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 74922470035 (69.78 GB)
telemt_user_msgs_from_client{user="hello"} 2664352
telemt_user_msgs_to_client{user="hello"} 5115201
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34967.3 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39966
telemt_connections_bad_total 340
telemt_handshake_timeouts_total 954
telemt_upstream_connect_attempt_total 36322
telemt_upstream_connect_success_total 36313
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 36322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36309
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 2003609663 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38259428613 (35.63 GB)
telemt_user_msgs_from_client{user="hello"} 1569447
telemt_user_msgs_to_client{user="hello"} 9428481
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34967.1 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62894
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4085
telemt_upstream_connect_attempt_total 54770
telemt_upstream_connect_success_total 54768
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 54770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54764
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1105291015 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 56919852643 (53.01 GB)
telemt_user_msgs_from_client{user="hello"} 1282184
telemt_user_msgs_to_client{user="hello"} 8387469
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34965.9 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59610
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 522
telemt_upstream_connect_attempt_total 57038
telemt_upstream_connect_success_total 56885
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 57038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56881
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 842195771 (803.18 MB)
telemt_user_octets_to_client{user="hello"} 37919582275 (35.32 GB)
telemt_user_msgs_from_client{user="hello"} 1165046
telemt_user_msgs_to_client{user="hello"} 7320713
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34967.2 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86503
telemt_connections_bad_total 8334
telemt_handshake_timeouts_total 1470
telemt_upstream_connect_attempt_total 73438
telemt_upstream_connect_success_total 73190
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 73438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73186
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2095514230 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 58015296516 (54.03 GB)
telemt_user_msgs_from_client{user="hello"} 2010133
telemt_user_msgs_to_client{user="hello"} 8411873
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13936.5 (3h 52m)
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