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

# Server Metrics 2026-03-12 09:34:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7241.2 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38883
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 2072
telemt_upstream_connect_attempt_total 1632
telemt_upstream_connect_success_total 1626
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1244
telemt_me_reconnect_success_total 1237
telemt_me_reader_eof_total 1256
telemt_me_idle_close_by_peer_total 1256
telemt_me_route_drop_no_conn_total 10295
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34464
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1236
telemt_me_writer_restored_same_endpoint_total 1221
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 34443
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 471116916 (449.29 MB)
telemt_user_octets_to_client{user="hello"} 10050553560 (9.36 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 7134.2 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15239
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 138
telemt_upstream_connect_attempt_total 2622
telemt_upstream_connect_success_total 2572
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 4990
telemt_me_reconnect_success_total 2200
telemt_me_reader_eof_total 2279
telemt_me_idle_close_by_peer_total 2279
telemt_me_route_drop_no_conn_total 5488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2280
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 2185
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 14522
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 85138996 (81.19 MB)
telemt_user_octets_to_client{user="hello"} 2706821908 (2.52 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 7098.4 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21758
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 1822
telemt_upstream_connect_success_total 1822
telemt_upstream_connect_attempts_per_request{bucket="1"} 1822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1453
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1496
telemt_me_idle_close_by_peer_total 1496
telemt_me_route_drop_no_conn_total 7057
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20272
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1430
telemt_me_writer_restored_same_endpoint_total 1426
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 20268
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 220897476 (210.66 MB)
telemt_user_octets_to_client{user="hello"} 23511115876 (21.90 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 7073.7 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24725
telemt_connections_bad_total 1027
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 1976
telemt_upstream_connect_success_total 1924
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 1976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 1572
telemt_me_reconnect_success_total 1543
telemt_me_reader_eof_total 1598
telemt_me_idle_close_by_peer_total 1598
telemt_me_route_drop_no_conn_total 7328
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22043
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 88
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1564
telemt_me_writer_restored_same_endpoint_total 1535
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 22042
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 624847400 (595.90 MB)
telemt_user_octets_to_client{user="hello"} 8061292612 (7.51 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7043.0 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13569
telemt_connections_bad_total 1390
telemt_handshake_timeouts_total 169
telemt_upstream_connect_attempt_total 2040
telemt_upstream_connect_success_total 1952
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 2040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 7983
telemt_me_reconnect_success_total 1575
telemt_me_reader_eof_total 1753
telemt_me_idle_close_by_peer_total 1753
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 3847
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11721
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 1776
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 1562
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 11720
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 53989116 (51.49 MB)
telemt_user_octets_to_client{user="hello"} 2881187340 (2.68 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7029.9 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33921
telemt_connections_bad_total 529
telemt_handshake_timeouts_total 505
telemt_upstream_connect_attempt_total 1266
telemt_upstream_connect_success_total 1258
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 895
telemt_me_reconnect_success_total 887
telemt_me_reader_eof_total 918
telemt_me_idle_close_by_peer_total 918
telemt_me_route_drop_no_conn_total 15316
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31661
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 899
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 31629
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 1544595132 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 20141639020 (18.76 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 41
```