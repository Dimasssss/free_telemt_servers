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

# Server Metrics 2026-03-13 03:58:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 73504.2 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283646
telemt_connections_bad_total 2990
telemt_handshake_timeouts_total 5756
telemt_upstream_connect_attempt_total 18584
telemt_upstream_connect_success_total 18501
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 18584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1534
telemt_me_reconnect_attempts_total 18296
telemt_me_reconnect_success_total 14808
telemt_me_reader_eof_total 15828
telemt_me_idle_close_by_peer_total 15827
telemt_me_route_drop_no_conn_total 88218
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237232
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15079
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14792
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 237172
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 4143887756 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 116277067640 (108.29 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 73397.1 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130466
telemt_connections_bad_total 746
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 39865
telemt_upstream_connect_success_total 39382
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 39865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_keepalive_timeout_total 533
telemt_me_reconnect_attempts_total 65764
telemt_me_reconnect_success_total 19204
telemt_me_reader_eof_total 21228
telemt_me_idle_close_by_peer_total 21228
telemt_me_route_drop_no_conn_total 47235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107456
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 20803
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19189
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1599
telemt_user_connections_total{user="hello"} 123956
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1291517548 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 37174436775 (34.62 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 73360.8 (20h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157149
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 2561
telemt_upstream_connect_attempt_total 20346
telemt_upstream_connect_success_total 20344
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 403
telemt_me_reconnect_attempts_total 17788
telemt_me_reconnect_success_total 16625
telemt_me_reader_eof_total 17796
telemt_me_idle_close_by_peer_total 17796
telemt_me_route_drop_no_conn_total 60798
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146948
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
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16808
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16605
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 146873
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 2774676208 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 69386125684 (64.62 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 73336.4 (20h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225604
telemt_connections_bad_total 13467
telemt_handshake_timeouts_total 1446
telemt_upstream_connect_attempt_total 32751
telemt_upstream_connect_success_total 22902
telemt_upstream_connect_fail_total 9849
telemt_upstream_connect_attempts_per_request{bucket="1"} 32751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9849
telemt_me_keepalive_timeout_total 3304
telemt_me_reconnect_attempts_total 59892
telemt_me_reconnect_success_total 16365
telemt_me_reader_eof_total 18243
telemt_me_idle_close_by_peer_total 18236
telemt_me_route_drop_no_conn_total 82179
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188353
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 17944
telemt_me_refill_failed_total 1356
telemt_me_writer_restored_same_endpoint_total 16355
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1579
telemt_user_connections_total{user="hello"} 191101
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3174777778 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 77544040681 (72.22 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23508.0 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23236
telemt_connections_bad_total 4412
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 7339
telemt_upstream_connect_success_total 7271
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 7339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 6084
telemt_me_reconnect_success_total 6063
telemt_me_reader_eof_total 6497
telemt_me_idle_close_by_peer_total 6497
telemt_me_route_drop_no_conn_total 6633
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18075
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6116
telemt_me_writer_restored_same_endpoint_total 6045
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 18075
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 132422280 (126.29 MB)
telemt_user_octets_to_client{user="hello"} 8215550048 (7.65 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 73292.7 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380689
telemt_connections_bad_total 7181
telemt_handshake_timeouts_total 2897
telemt_upstream_connect_attempt_total 15606
telemt_upstream_connect_success_total 15520
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1423
telemt_me_reconnect_attempts_total 15491
telemt_me_reconnect_success_total 11865
telemt_me_reader_eof_total 12741
telemt_me_idle_close_by_peer_total 12738
telemt_me_route_drop_no_conn_total 170371
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371660
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
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12130
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11858
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 359906
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 6027826464 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 215650863640 (200.84 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 39
```