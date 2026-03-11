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

# Server Metrics 2026-03-11 02:00:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 41688.8 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111804
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2542
telemt_upstream_connect_attempt_total 100824
telemt_upstream_connect_success_total 100788
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 100824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100784
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2776338580 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 80260110980 (74.75 GB)
telemt_user_msgs_from_client{user="hello"} 2856908
telemt_user_msgs_to_client{user="hello"} 5542852
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 41688.0 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46240
telemt_connections_bad_total 365
telemt_handshake_timeouts_total 2279
telemt_upstream_connect_attempt_total 41009
telemt_upstream_connect_success_total 41000
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 41009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40996
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2135082422 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 38926682609 (36.25 GB)
telemt_user_msgs_from_client{user="hello"} 1667300
telemt_user_msgs_to_client{user="hello"} 9697445
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 41687.7 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67344
telemt_connections_bad_total 641
telemt_handshake_timeouts_total 4137
telemt_upstream_connect_attempt_total 58771
telemt_upstream_connect_success_total 58769
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58763
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 11731973268 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 69682793854 (64.90 GB)
telemt_user_msgs_from_client{user="hello"} 5108837
telemt_user_msgs_to_client{user="hello"} 13011125
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 41686.6 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66123
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 540
telemt_upstream_connect_attempt_total 63264
telemt_upstream_connect_success_total 63109
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 63264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63103
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1751183820 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42561562587 (39.64 GB)
telemt_user_msgs_from_client{user="hello"} 1573885
telemt_user_msgs_to_client{user="hello"} 8325787
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41688.0 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95946
telemt_connections_bad_total 9717
telemt_handshake_timeouts_total 1515
telemt_upstream_connect_attempt_total 81158
telemt_upstream_connect_success_total 80910
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 81158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80906
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 2152198297 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 66549954941 (61.98 GB)
telemt_user_msgs_from_client{user="hello"} 2148312
telemt_user_msgs_to_client{user="hello"} 9609678
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 20657.3 (5h 44m)
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