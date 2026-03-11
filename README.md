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

# Server Metrics 2026-03-11 03:53:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 48411.8 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123366
telemt_connections_bad_total 3381
telemt_handshake_timeouts_total 2612
telemt_upstream_connect_attempt_total 111772
telemt_upstream_connect_success_total 111732
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 111772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111726
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2972815150 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 83234402492 (77.52 GB)
telemt_user_msgs_from_client{user="hello"} 3028461
telemt_user_msgs_to_client{user="hello"} 5782189
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 48411.1 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51223
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 2927
telemt_upstream_connect_attempt_total 45184
telemt_upstream_connect_success_total 45174
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 45184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45168
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 2324751044 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 44096199328 (41.07 GB)
telemt_user_msgs_from_client{user="hello"} 1813899
telemt_user_msgs_to_client{user="hello"} 10486727
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 48410.9 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71759
telemt_connections_bad_total 667
telemt_handshake_timeouts_total 4232
telemt_upstream_connect_attempt_total 62865
telemt_upstream_connect_success_total 62863
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 62865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62856
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 11750282053 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70652409789 (65.80 GB)
telemt_user_msgs_from_client{user="hello"} 5145649
telemt_user_msgs_to_client{user="hello"} 13235567
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 48410.0 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72745
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 69614
telemt_upstream_connect_success_total 69455
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 69614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69449
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 1782805129 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 43126768692 (40.16 GB)
telemt_user_msgs_from_client{user="hello"} 1632367
telemt_user_msgs_to_client{user="hello"} 8488639
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 48411.2 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115204
telemt_connections_bad_total 10998
telemt_handshake_timeouts_total 1653
telemt_upstream_connect_attempt_total 98112
telemt_upstream_connect_success_total 97864
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 98112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97858
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2278330178 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 91018455101 (84.77 GB)
telemt_user_msgs_from_client{user="hello"} 2412940
telemt_user_msgs_to_client{user="hello"} 11777241
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27380.5 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```