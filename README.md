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

# Server Metrics 2026-03-11 23:57:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7933.5 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13221
telemt_connections_bad_total 177
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 12597
telemt_upstream_connect_success_total 12592
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12590
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 165753860 (158.08 MB)
telemt_user_octets_to_client{user="hello"} 5659032177 (5.27 GB)
telemt_user_msgs_from_client{user="hello"} 285780
telemt_user_msgs_to_client{user="hello"} 732662
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 7921.7 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5637
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 5404
telemt_upstream_connect_success_total 5404
telemt_upstream_connect_attempts_per_request{bucket="1"} 5404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 691
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5402
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 26154678 (24.94 MB)
telemt_user_octets_to_client{user="hello"} 791487410 (754.82 MB)
telemt_user_msgs_from_client{user="hello"} 63301
telemt_user_msgs_to_client{user="hello"} 330850
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 7895.5 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10168
telemt_connections_bad_total 269
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 7780
telemt_upstream_connect_success_total 7780
telemt_upstream_connect_attempts_per_request{bucket="1"} 7780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1022
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7778
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 53373289 (50.90 MB)
telemt_user_octets_to_client{user="hello"} 5733101609 (5.34 GB)
telemt_user_msgs_from_client{user="hello"} 167111
telemt_user_msgs_to_client{user="hello"} 1312210
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7920.8 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8620
telemt_connections_bad_total 1055
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 7070
telemt_upstream_connect_success_total 7060
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 7070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7058
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 51992922 (49.58 MB)
telemt_user_octets_to_client{user="hello"} 2788479477 (2.60 GB)
telemt_user_msgs_from_client{user="hello"} 106639
telemt_user_msgs_to_client{user="hello"} 1051984
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7921.5 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7583
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 6633
telemt_upstream_connect_success_total 6633
telemt_upstream_connect_attempts_per_request{bucket="1"} 6633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6631
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 100179989 (95.54 MB)
telemt_user_octets_to_client{user="hello"} 13212630213 (12.31 GB)
telemt_user_msgs_from_client{user="hello"} 196105
telemt_user_msgs_to_client{user="hello"} 1127693
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```