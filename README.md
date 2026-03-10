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

# Server Metrics 2026-03-10 19:21:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17704.1 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68638
telemt_connections_bad_total 2229
telemt_handshake_timeouts_total 1929
telemt_upstream_connect_attempt_total 61175
telemt_upstream_connect_success_total 61163
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 61175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61161
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 1946617759 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 44550066453 (41.49 GB)
telemt_user_msgs_from_client{user="hello"} 1783035
telemt_user_msgs_to_client{user="hello"} 3357554
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17703.4 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26246
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 442
telemt_upstream_connect_attempt_total 24007
telemt_upstream_connect_success_total 24000
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23998
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 803097111 (765.89 MB)
telemt_user_octets_to_client{user="hello"} 15877445085 (14.79 GB)
telemt_user_msgs_from_client{user="hello"} 771329
telemt_user_msgs_to_client{user="hello"} 4919837
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17703.0 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40185
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 3581
telemt_upstream_connect_attempt_total 34046
telemt_upstream_connect_success_total 34046
telemt_upstream_connect_attempts_per_request{bucket="1"} 34046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34044
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 554402571 (528.72 MB)
telemt_user_octets_to_client{user="hello"} 33477520883 (31.18 GB)
telemt_user_msgs_from_client{user="hello"} 750692
telemt_user_msgs_to_client{user="hello"} 4936185
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17701.9 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37587
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 272
telemt_upstream_connect_attempt_total 36003
telemt_upstream_connect_success_total 35899
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 36003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35897
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 602832540 (574.91 MB)
telemt_user_octets_to_client{user="hello"} 29279693714 (27.27 GB)
telemt_user_msgs_from_client{user="hello"} 765424
telemt_user_msgs_to_client{user="hello"} 5408098
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17703.3 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55589
telemt_connections_bad_total 4925
telemt_handshake_timeouts_total 1210
telemt_upstream_connect_attempt_total 47155
telemt_upstream_connect_success_total 46912
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 47154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46910
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1477521133 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 33995682778 (31.66 GB)
telemt_user_msgs_from_client{user="hello"} 1300931
telemt_user_msgs_to_client{user="hello"} 4993210
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```