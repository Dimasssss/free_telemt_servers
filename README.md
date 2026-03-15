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

# Server Metrics 2026-03-15 00:58:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 9832.8 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20391
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 261
telemt_upstream_connect_attempt_total 2491
telemt_upstream_connect_success_total 2479
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1985
telemt_me_reconnect_success_total 1974
telemt_me_reader_eof_total 2072
telemt_me_idle_close_by_peer_total 2072
telemt_me_route_drop_no_conn_total 5692
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19103
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1975
telemt_me_writer_restored_same_endpoint_total 1943
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 19101
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 214789080 (204.84 MB)
telemt_user_octets_to_client{user="hello"} 6429975632 (5.99 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 9838.9 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9482
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 2738
telemt_upstream_connect_success_total 2738
telemt_upstream_connect_attempts_per_request{bucket="1"} 2738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1538
telemt_me_reconnect_attempts_total 2238
telemt_me_reconnect_success_total 2232
telemt_me_reader_eof_total 2364
telemt_me_idle_close_by_peer_total 2364
telemt_me_route_drop_no_conn_total 2858
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8935
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2243
telemt_me_writer_restored_same_endpoint_total 2216
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 8938
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 91618252 (87.37 MB)
telemt_user_octets_to_client{user="hello"} 1580010076 (1.47 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 9831.3 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9695
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 2586
telemt_upstream_connect_success_total 2585
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2089
telemt_me_reconnect_success_total 2077
telemt_me_reader_eof_total 2226
telemt_me_idle_close_by_peer_total 2226
telemt_me_route_drop_no_conn_total 3137
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9124
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2088
telemt_me_writer_restored_same_endpoint_total 2073
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 9096
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 1408062840 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 10927142784 (10.18 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 9831.3 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9863
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 2384
telemt_upstream_connect_success_total 2383
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1891
telemt_me_reconnect_success_total 1882
telemt_me_reader_eof_total 1987
telemt_me_idle_close_by_peer_total 1987
telemt_me_route_drop_no_conn_total 3974
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9490
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1894
telemt_me_writer_restored_same_endpoint_total 1871
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 9490
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 235125796 (224.23 MB)
telemt_user_octets_to_client{user="hello"} 6601672856 (6.15 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 9831.3 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12459
telemt_connections_bad_total 2062
telemt_handshake_timeouts_total 372
telemt_upstream_connect_attempt_total 3153
telemt_upstream_connect_success_total 3114
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 3153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 2686
telemt_me_reconnect_success_total 2609
telemt_me_reader_eof_total 2725
telemt_me_idle_close_by_peer_total 2725
telemt_me_route_drop_no_conn_total 3028
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9788
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2613
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2597
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 9776
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 158531468 (151.19 MB)
telemt_user_octets_to_client{user="hello"} 5477485604 (5.10 GB)
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 9830.4 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31900
telemt_connections_bad_total 851
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 2150
telemt_upstream_connect_success_total 2139
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1642
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1702
telemt_me_idle_close_by_peer_total 1702
telemt_me_route_drop_no_conn_total 18453
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31501
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1623
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 30070
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 465380236 (443.82 MB)
telemt_user_octets_to_client{user="hello"} 21630557432 (20.15 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 32
```