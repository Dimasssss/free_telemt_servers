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

# Server Metrics 2026-03-11 21:57:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 790.6 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1581
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1542
telemt_upstream_connect_success_total 1541
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1539
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 15672876 (14.95 MB)
telemt_user_octets_to_client{user="hello"} 947798000 (903.89 MB)
telemt_user_msgs_from_client{user="hello"} 37306
telemt_user_msgs_to_client{user="hello"} 150325
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 778.8 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648
telemt_upstream_connect_attempt_total 621
telemt_upstream_connect_success_total 621
telemt_upstream_connect_attempts_per_request{bucket="1"} 621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 619
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 5445555 (5.19 MB)
telemt_user_octets_to_client{user="hello"} 148718567 (141.83 MB)
telemt_user_msgs_from_client{user="hello"} 13137
telemt_user_msgs_to_client{user="hello"} 59560
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 752.5 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1622
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1059
telemt_upstream_connect_success_total 1059
telemt_upstream_connect_attempts_per_request{bucket="1"} 1059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1057
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 6720721 (6.41 MB)
telemt_user_octets_to_client{user="hello"} 527984287 (503.53 MB)
telemt_user_msgs_from_client{user="hello"} 20024
telemt_user_msgs_to_client{user="hello"} 138697
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 777.7 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 818
telemt_upstream_connect_success_total 816
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 814
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 5939667 (5.66 MB)
telemt_user_octets_to_client{user="hello"} 392334275 (374.16 MB)
telemt_user_msgs_from_client{user="hello"} 14589
telemt_user_msgs_to_client{user="hello"} 143517
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 779.1 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 867
telemt_upstream_connect_success_total 867
telemt_upstream_connect_attempts_per_request{bucket="1"} 867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 865
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 13411685 (12.79 MB)
telemt_user_octets_to_client{user="hello"} 561253181 (535.25 MB)
telemt_user_msgs_from_client{user="hello"} 15022
telemt_user_msgs_to_client{user="hello"} 105110
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 778.6 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 887
telemt_upstream_connect_success_total 887
telemt_upstream_connect_attempts_per_request{bucket="1"} 887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 885
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 29629682 (28.26 MB)
telemt_user_octets_to_client{user="hello"} 1138696226 (1.06 GB)
telemt_user_msgs_from_client{user="hello"} 29131
telemt_user_msgs_to_client{user="hello"} 108376
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 8
```