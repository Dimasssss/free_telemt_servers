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

# Server Metrics 2026-03-11 03:37:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 47494.7 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121569
telemt_connections_bad_total 3365
telemt_handshake_timeouts_total 2593
telemt_upstream_connect_attempt_total 110083
telemt_upstream_connect_success_total 110044
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 110083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110038
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2957361017 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 82797638388 (77.11 GB)
telemt_user_msgs_from_client{user="hello"} 3004408
telemt_user_msgs_to_client{user="hello"} 5738800
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 47494.0 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50647
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 2925
telemt_upstream_connect_attempt_total 44634
telemt_upstream_connect_success_total 44624
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 44634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44618
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 2317145060 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 44043458624 (41.02 GB)
telemt_user_msgs_from_client{user="hello"} 1803457
telemt_user_msgs_to_client{user="hello"} 10459286
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 47493.9 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71180
telemt_connections_bad_total 667
telemt_handshake_timeouts_total 4231
telemt_upstream_connect_attempt_total 62310
telemt_upstream_connect_success_total 62308
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 62310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62302
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 11747706140 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70605527233 (65.76 GB)
telemt_user_msgs_from_client{user="hello"} 5140594
telemt_user_msgs_to_client{user="hello"} 13221369
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 47492.8 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71633
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 68544
telemt_upstream_connect_success_total 68385
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 68544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68379
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1775925223 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42837924644 (39.90 GB)
telemt_user_msgs_from_client{user="hello"} 1618253
telemt_user_msgs_to_client{user="hello"} 8430127
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 47494.2 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112327
telemt_connections_bad_total 10830
telemt_handshake_timeouts_total 1579
telemt_upstream_connect_attempt_total 95741
telemt_upstream_connect_success_total 95493
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 95741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95487
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2260104730 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 87568102929 (81.55 GB)
telemt_user_msgs_from_client{user="hello"} 2376622
telemt_user_msgs_to_client{user="hello"} 11516211
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26463.6 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```