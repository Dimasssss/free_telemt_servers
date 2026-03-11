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

# Server Metrics 2026-03-11 18:38:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5893.9 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24381
telemt_connections_bad_total 1325
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 21963
telemt_upstream_connect_success_total 21959
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 21963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21957
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 637185503 (607.67 MB)
telemt_user_octets_to_client{user="hello"} 14281666077 (13.30 GB)
telemt_user_msgs_from_client{user="hello"} 567210
telemt_user_msgs_to_client{user="hello"} 1058889
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 5882.1 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11797
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 232
telemt_upstream_connect_attempt_total 10556
telemt_upstream_connect_success_total 10555
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10553
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 166256630 (158.55 MB)
telemt_user_octets_to_client{user="hello"} 6542316917 (6.09 GB)
telemt_user_msgs_from_client{user="hello"} 245406
telemt_user_msgs_to_client{user="hello"} 2448148
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 5901.5 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13503
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 12588
telemt_upstream_connect_success_total 12586
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 12588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12584
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 113003315 (107.77 MB)
telemt_user_octets_to_client{user="hello"} 5299084487 (4.94 GB)
telemt_user_msgs_from_client{user="hello"} 261071
telemt_user_msgs_to_client{user="hello"} 1510975
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 5897.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13163
telemt_connections_bad_total 566
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 11932
telemt_upstream_connect_success_total 11900
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 11932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11898
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 470848816 (449.04 MB)
telemt_user_octets_to_client{user="hello"} 7176721550 (6.68 GB)
telemt_user_msgs_from_client{user="hello"} 327010
telemt_user_msgs_to_client{user="hello"} 1595268
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5905.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14802
telemt_connections_bad_total 1187
telemt_handshake_timeouts_total 78
telemt_upstream_connect_attempt_total 13130
telemt_upstream_connect_success_total 13129
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13127
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 216204176 (206.19 MB)
telemt_user_octets_to_client{user="hello"} 3500844005 (3.26 GB)
telemt_user_msgs_from_client{user="hello"} 251441
telemt_user_msgs_to_client{user="hello"} 1042046
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 80511.7 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```