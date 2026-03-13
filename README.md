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

# Server Metrics 2026-03-13 09:51:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 94702.7 (26h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372924
telemt_connections_bad_total 3190
telemt_handshake_timeouts_total 7906
telemt_upstream_connect_attempt_total 23910
telemt_upstream_connect_success_total 23798
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 23910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1741
telemt_me_reconnect_attempts_total 22542
telemt_me_reconnect_success_total 19027
telemt_me_reader_eof_total 20328
telemt_me_idle_close_by_peer_total 20327
telemt_me_route_drop_no_conn_total 116817
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320236
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1029
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 19338
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19011
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 319927
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 5585830484 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 140990896104 (131.31 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 94595.8 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170996
telemt_connections_bad_total 1558
telemt_handshake_timeouts_total 1309
telemt_upstream_connect_attempt_total 46958
telemt_upstream_connect_success_total 46317
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 46958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_keepalive_timeout_total 732
telemt_me_reconnect_attempts_total 81452
telemt_me_reconnect_success_total 25083
telemt_me_reader_eof_total 27590
telemt_me_idle_close_by_peer_total 27590
telemt_me_route_drop_no_conn_total 72307
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144636
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 27056
telemt_me_refill_failed_total 1759
telemt_me_writer_restored_same_endpoint_total 25068
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1973
telemt_user_connections_total{user="hello"} 160918
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 1689814508 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 52887846123 (49.26 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 94559.2 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208183
telemt_connections_bad_total 2023
telemt_handshake_timeouts_total 4209
telemt_upstream_connect_attempt_total 25572
telemt_upstream_connect_success_total 25569
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 692
telemt_me_reconnect_attempts_total 21989
telemt_me_reconnect_success_total 20798
telemt_me_reader_eof_total 22290
telemt_me_idle_close_by_peer_total 22290
telemt_me_route_drop_no_conn_total 78609
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194295
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 21026
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20778
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 194217
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 8802159104 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 81115075836 (75.54 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 94535.1 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295289
telemt_connections_bad_total 13665
telemt_handshake_timeouts_total 2152
telemt_upstream_connect_attempt_total 38536
telemt_upstream_connect_success_total 28523
telemt_upstream_connect_fail_total 10013
telemt_upstream_connect_attempts_per_request{bucket="1"} 38536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10013
telemt_me_keepalive_timeout_total 3426
telemt_me_reconnect_attempts_total 78871
telemt_me_reconnect_success_total 20955
telemt_me_reader_eof_total 23407
telemt_me_idle_close_by_peer_total 23400
telemt_me_route_drop_no_conn_total 106917
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252853
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 941
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23029
telemt_me_refill_failed_total 1805
telemt_me_writer_restored_same_endpoint_total 20945
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2074
telemt_user_connections_total{user="hello"} 255577
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 5599270698 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 95865391621 (89.28 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 44706.7 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59175
telemt_connections_bad_total 8977
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 15382
telemt_upstream_connect_success_total 15233
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 15381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 376
telemt_me_reconnect_attempts_total 15223
telemt_me_reconnect_success_total 12994
telemt_me_reader_eof_total 13854
telemt_me_idle_close_by_peer_total 13854
telemt_me_route_drop_no_conn_total 18229
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47934
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13181
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12976
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 47929
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 367262744 (350.25 MB)
telemt_user_octets_to_client{user="hello"} 13074495400 (12.18 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 94491.7 (26h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513940
telemt_connections_bad_total 14493
telemt_handshake_timeouts_total 6228
telemt_upstream_connect_attempt_total 20082
telemt_upstream_connect_success_total 19976
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 20082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1551
telemt_me_reconnect_attempts_total 18946
telemt_me_reconnect_success_total 15294
telemt_me_reader_eof_total 16413
telemt_me_idle_close_by_peer_total 16410
telemt_me_route_drop_no_conn_total 266326
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 248
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15606
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15287
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 475076
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 8572124576 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 267404004140 (249.04 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 64
```