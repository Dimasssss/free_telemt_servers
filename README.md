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

# Server Metrics 2026-03-11 04:03:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 49022.8 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124764
telemt_connections_bad_total 3381
telemt_handshake_timeouts_total 2639
telemt_upstream_connect_attempt_total 113129
telemt_upstream_connect_success_total 113089
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 113129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113083
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 2988314407 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 83626221767 (77.88 GB)
telemt_user_msgs_from_client{user="hello"} 3048980
telemt_user_msgs_to_client{user="hello"} 5810771
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 49022.2 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51638
telemt_connections_bad_total 401
telemt_handshake_timeouts_total 2933
telemt_upstream_connect_attempt_total 45578
telemt_upstream_connect_success_total 45568
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 45578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45562
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 2328810200 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 44121061498 (41.09 GB)
telemt_user_msgs_from_client{user="hello"} 1820215
telemt_user_msgs_to_client{user="hello"} 10500365
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 49021.9 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72219
telemt_connections_bad_total 671
telemt_handshake_timeouts_total 4233
telemt_upstream_connect_attempt_total 63296
telemt_upstream_connect_success_total 63294
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 63296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63288
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 11752237275 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 70726629709 (65.87 GB)
telemt_user_msgs_from_client{user="hello"} 5150317
telemt_user_msgs_to_client{user="hello"} 13256143
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 49020.8 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73710
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 70552
telemt_upstream_connect_success_total 70393
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 70552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70387
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 1786060652 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 43294319079 (40.32 GB)
telemt_user_msgs_from_client{user="hello"} 1640538
telemt_user_msgs_to_client{user="hello"} 8524665
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 49022.2 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116584
telemt_connections_bad_total 11106
telemt_handshake_timeouts_total 1655
telemt_upstream_connect_attempt_total 99352
telemt_upstream_connect_success_total 99104
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 99352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99098
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 2285356637 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 92168402209 (85.84 GB)
telemt_user_msgs_from_client{user="hello"} 2430253
telemt_user_msgs_to_client{user="hello"} 11865818
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27991.6 (7h 46m)
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