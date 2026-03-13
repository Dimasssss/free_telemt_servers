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

# Server Metrics 2026-03-13 04:54:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 76881.7 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292717
telemt_connections_bad_total 3033
telemt_handshake_timeouts_total 5786
telemt_upstream_connect_attempt_total 19439
telemt_upstream_connect_success_total 19348
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 19439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1559
telemt_me_reconnect_attempts_total 18972
telemt_me_reconnect_success_total 15476
telemt_me_reader_eof_total 16546
telemt_me_idle_close_by_peer_total 16545
telemt_me_route_drop_no_conn_total 91209
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245955
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 523
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 364
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15751
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15460
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 245893
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 4248402896 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 120999513744 (112.69 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 76774.5 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134351
telemt_connections_bad_total 752
telemt_handshake_timeouts_total 1004
telemt_upstream_connect_attempt_total 41136
telemt_upstream_connect_success_total 40619
telemt_upstream_connect_fail_total 517
telemt_upstream_connect_attempts_per_request{bucket="1"} 41136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 517
telemt_me_keepalive_timeout_total 562
telemt_me_reconnect_attempts_total 66827
telemt_me_reconnect_success_total 20264
telemt_me_reader_eof_total 22333
telemt_me_idle_close_by_peer_total 22333
telemt_me_route_drop_no_conn_total 49590
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111158
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 21879
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20249
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1615
telemt_user_connections_total{user="hello"} 127658
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1328262824 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 38360848087 (35.73 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 76738.0 (21h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162104
telemt_connections_bad_total 1858
telemt_handshake_timeouts_total 2632
telemt_upstream_connect_attempt_total 21200
telemt_upstream_connect_success_total 21198
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 447
telemt_me_reconnect_attempts_total 18470
telemt_me_reconnect_success_total 17306
telemt_me_reader_eof_total 18539
telemt_me_idle_close_by_peer_total 18539
telemt_me_route_drop_no_conn_total 62543
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151617
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17496
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17286
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 151544
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 2882738844 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 70555736648 (65.71 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 76713.7 (21h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233536
telemt_connections_bad_total 13531
telemt_handshake_timeouts_total 1472
telemt_upstream_connect_attempt_total 33621
telemt_upstream_connect_success_total 23737
telemt_upstream_connect_fail_total 9884
telemt_upstream_connect_attempts_per_request{bucket="1"} 33621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9884
telemt_me_keepalive_timeout_total 3311
telemt_me_reconnect_attempts_total 65610
telemt_me_reconnect_success_total 17024
telemt_me_reader_eof_total 19065
telemt_me_idle_close_by_peer_total 19058
telemt_me_route_drop_no_conn_total 85256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195547
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18766
telemt_me_refill_failed_total 1514
telemt_me_writer_restored_same_endpoint_total 17014
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1742
telemt_user_connections_total{user="hello"} 198295
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 3248583330 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 79377580869 (73.93 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26885.5 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27660
telemt_connections_bad_total 5020
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 8503
telemt_upstream_connect_success_total 8420
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 8502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 202
telemt_me_reconnect_attempts_total 7106
telemt_me_reconnect_success_total 7079
telemt_me_reader_eof_total 7564
telemt_me_idle_close_by_peer_total 7564
telemt_me_route_drop_no_conn_total 7653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21768
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7145
telemt_me_writer_restored_same_endpoint_total 7061
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 21768
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 152533836 (145.47 MB)
telemt_user_octets_to_client{user="hello"} 9215893512 (8.58 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 76670.2 (21h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393481
telemt_connections_bad_total 7713
telemt_handshake_timeouts_total 2956
telemt_upstream_connect_attempt_total 16350
telemt_upstream_connect_success_total 16258
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1433
telemt_me_reconnect_attempts_total 16055
telemt_me_reconnect_success_total 12426
telemt_me_reader_eof_total 13343
telemt_me_idle_close_by_peer_total 13340
telemt_me_route_drop_no_conn_total 175777
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383590
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 12699
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12419
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 371833
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 6163205256 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 219690832560 (204.60 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 32
```