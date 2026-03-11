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

# Server Metrics 2026-03-11 23:09:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5084.9 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8336
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 7975
telemt_upstream_connect_success_total 7971
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 7975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7969
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 109855279 (104.77 MB)
telemt_user_octets_to_client{user="hello"} 3571883118 (3.33 GB)
telemt_user_msgs_from_client{user="hello"} 181912
telemt_user_msgs_to_client{user="hello"} 514862
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 5073.2 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3924
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 3775
telemt_upstream_connect_success_total 3775
telemt_upstream_connect_attempts_per_request{bucket="1"} 3775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 489
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3773
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 16807173 (16.03 MB)
telemt_user_octets_to_client{user="hello"} 453209602 (432.21 MB)
telemt_user_msgs_from_client{user="hello"} 41899
telemt_user_msgs_to_client{user="hello"} 199643
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 5046.7 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6363
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 5252
telemt_upstream_connect_success_total 5252
telemt_upstream_connect_attempts_per_request{bucket="1"} 5252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 668
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5250
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 30470464 (29.06 MB)
telemt_user_octets_to_client{user="hello"} 2464826359 (2.30 GB)
telemt_user_msgs_from_client{user="hello"} 98441
telemt_user_msgs_to_client{user="hello"} 669156
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 5072.0 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4922
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 4713
telemt_upstream_connect_success_total 4708
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 4713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4706
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 39165138 (37.35 MB)
telemt_user_octets_to_client{user="hello"} 1856229973 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 74850
telemt_user_msgs_to_client{user="hello"} 678179
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5073.3 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5038
telemt_connections_bad_total 1001
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 3944
telemt_upstream_connect_success_total 3941
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3939
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 44542151 (42.48 MB)
telemt_user_octets_to_client{user="hello"} 1543265084 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 58059
telemt_user_msgs_to_client{user="hello"} 283877
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 5072.7 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5091
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 4338
telemt_upstream_connect_success_total 4338
telemt_upstream_connect_attempts_per_request{bucket="1"} 4338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 713
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4336
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 81679144 (77.90 MB)
telemt_user_octets_to_client{user="hello"} 11191501342 (10.42 GB)
telemt_user_msgs_from_client{user="hello"} 148637
telemt_user_msgs_to_client{user="hello"} 818657
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```