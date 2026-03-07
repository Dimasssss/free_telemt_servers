# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-07 00:50:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 24129.7 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31791
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 487
telemt_upstream_connect_attempt_total 29632
telemt_upstream_connect_success_total 29625
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29621
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2073320868 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 32943470260 (30.68 GB)
telemt_user_msgs_from_client{user="hello"} 1365992
telemt_user_msgs_to_client{user="hello"} 5184480
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 24128.6 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6690
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6262
telemt_upstream_connect_success_total 6259
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6255
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 215229253 (205.26 MB)
telemt_user_octets_to_client{user="hello"} 3894351032 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 201664
telemt_user_msgs_to_client{user="hello"} 1088751
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 24128.4 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3122
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2852
telemt_upstream_connect_success_total 2852
telemt_upstream_connect_attempts_per_request{bucket="1"} 2852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2848
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 65053676 (62.04 MB)
telemt_user_octets_to_client{user="hello"} 1861791613 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 63952
telemt_user_msgs_to_client{user="hello"} 392457
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 24128.5 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4309
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4154
telemt_upstream_connect_success_total 4147
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4143
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 100654065 (95.99 MB)
telemt_user_octets_to_client{user="hello"} 1361037328 (1.27 GB)
telemt_user_msgs_from_client{user="hello"} 85679
telemt_user_msgs_to_client{user="hello"} 349809
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 24128.8 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12015
telemt_connections_bad_total 5274
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6595
telemt_upstream_connect_success_total 6594
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6590
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 227603861 (217.06 MB)
telemt_user_octets_to_client{user="hello"} 7416839386 (6.91 GB)
telemt_user_msgs_from_client{user="hello"} 214124
telemt_user_msgs_to_client{user="hello"} 1525696
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```