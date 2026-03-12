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

# Server Metrics 2026-03-12 02:12:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16037.7 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31211
telemt_connections_bad_total 1907
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 27679
telemt_upstream_connect_success_total 27672
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 27679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27670
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 276054329 (263.27 MB)
telemt_user_octets_to_client{user="hello"} 9250624459 (8.62 GB)
telemt_user_msgs_from_client{user="hello"} 473084
telemt_user_msgs_to_client{user="hello"} 1143154
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16025.9 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13051
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 12527
telemt_upstream_connect_success_total 12527
telemt_upstream_connect_attempts_per_request{bucket="1"} 12527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12525
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 85374260 (81.42 MB)
telemt_user_octets_to_client{user="hello"} 5359323613 (4.99 GB)
telemt_user_msgs_from_client{user="hello"} 210120
telemt_user_msgs_to_client{user="hello"} 1537931
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 15999.8 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21790
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 877
telemt_upstream_connect_attempt_total 18575
telemt_upstream_connect_success_total 18575
telemt_upstream_connect_attempts_per_request{bucket="1"} 18575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18573
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 3973982744 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 11459554048 (10.67 GB)
telemt_user_msgs_from_client{user="hello"} 1709474
telemt_user_msgs_to_client{user="hello"} 2276077
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16025.0 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24494
telemt_connections_bad_total 8403
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 14697
telemt_upstream_connect_success_total 14658
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 14697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14654
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 119770181 (114.22 MB)
telemt_user_octets_to_client{user="hello"} 6842290368 (6.37 GB)
telemt_user_msgs_from_client{user="hello"} 235996
telemt_user_msgs_to_client{user="hello"} 2595368
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16025.7 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17393
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 15904
telemt_upstream_connect_success_total 15904
telemt_upstream_connect_attempts_per_request{bucket="1"} 15904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15902
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 405973682 (387.17 MB)
telemt_user_octets_to_client{user="hello"} 21450534776 (19.98 GB)
telemt_user_msgs_from_client{user="hello"} 505357
telemt_user_msgs_to_client{user="hello"} 2312968
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```