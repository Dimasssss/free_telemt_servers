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

# Server Metrics 2026-03-14 11:42:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 187752.4 (52h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739226
telemt_connections_bad_total 34553
telemt_handshake_timeouts_total 14370
telemt_upstream_connect_attempt_total 47763
telemt_upstream_connect_success_total 47527
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 47763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6157
telemt_me_reconnect_attempts_total 43558
telemt_me_reconnect_success_total 37792
telemt_me_reader_eof_total 40409
telemt_me_idle_close_by_peer_total 40408
telemt_me_route_drop_no_conn_total 243993
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2661
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1775
telemt_desync_frames_bucket_total{bucket="1_2"} 556
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 1107
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 38377
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37772
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 634088
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 17665396106 (16.45 GB)
telemt_user_octets_to_client{user="hello"} 305154323492 (284.20 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 187645.9 (52h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367165
telemt_connections_bad_total 2837
telemt_handshake_timeouts_total 3307
telemt_upstream_connect_attempt_total 155723
telemt_upstream_connect_success_total 154339
telemt_upstream_connect_fail_total 1384
telemt_upstream_connect_attempts_per_request{bucket="1"} 155723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2478
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1384
telemt_me_keepalive_timeout_total 5563
telemt_me_reconnect_attempts_total 194923
telemt_me_reconnect_success_total 41671
telemt_me_reader_eof_total 47538
telemt_me_idle_close_by_peer_total 47538
telemt_me_route_drop_no_conn_total 126977
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243563
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46857
telemt_me_refill_failed_total 4781
telemt_me_writer_restored_same_endpoint_total 41653
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5186
telemt_user_connections_total{user="hello"} 346661
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 3530059651 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 111953394743 (104.26 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 187609.6 (52h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424412
telemt_connections_bad_total 3310
telemt_handshake_timeouts_total 36448
telemt_upstream_connect_attempt_total 50091
telemt_upstream_connect_success_total 50082
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4113
telemt_me_reconnect_attempts_total 41945
telemt_me_reconnect_success_total 40624
telemt_me_reader_eof_total 43647
telemt_me_idle_close_by_peer_total 43647
telemt_me_route_drop_no_conn_total 154900
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369468
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 41113
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40603
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 369228
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 15163618274 (14.12 GB)
telemt_user_octets_to_client{user="hello"} 162129938043 (151.00 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 187585.4 (52h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537552
telemt_connections_bad_total 16770
telemt_handshake_timeouts_total 5290
telemt_upstream_connect_attempt_total 80378
telemt_upstream_connect_success_total 69677
telemt_upstream_connect_fail_total 10701
telemt_upstream_connect_attempts_per_request{bucket="1"} 80378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10701
telemt_me_keepalive_timeout_total 5735
telemt_me_reconnect_attempts_total 155927
telemt_me_reconnect_success_total 41285
telemt_me_reader_eof_total 46190
telemt_me_idle_close_by_peer_total 46182
telemt_me_route_drop_no_conn_total 194983
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461217
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2105
telemt_desync_full_logged_total 618
telemt_desync_suppressed_total 1487
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 797
telemt_desync_frames_bucket_total{bucket="gt_10"} 815
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45339
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41275
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4054
telemt_user_connections_total{user="hello"} 480083
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 10153822191 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 195706855596 (182.27 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 137756.7 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233076
telemt_connections_bad_total 37051
telemt_handshake_timeouts_total 2142
telemt_upstream_connect_attempt_total 48281
telemt_upstream_connect_success_total 47799
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 48281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 2954
telemt_me_reconnect_attempts_total 51945
telemt_me_reconnect_success_total 36058
telemt_me_reader_eof_total 38567
telemt_me_idle_close_by_peer_total 38567
telemt_me_route_drop_no_conn_total 70602
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182764
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 36892
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 36040
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 834
telemt_user_connections_total{user="hello"} 187520
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2742331761 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 86263164387 (80.34 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 187541.4 (52h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1092910
telemt_connections_bad_total 37511
telemt_handshake_timeouts_total 27139
telemt_upstream_connect_attempt_total 39156
telemt_upstream_connect_success_total 38951
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 39156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 4969
telemt_me_reconnect_attempts_total 34358
telemt_me_reconnect_success_total 29665
telemt_me_reader_eof_total 31809
telemt_me_idle_close_by_peer_total 31806
telemt_me_route_drop_no_conn_total 512936
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1013548
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 30186
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29658
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 986133
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 21143010572 (19.69 GB)
telemt_user_octets_to_client{user="hello"} 494286031900 (460.34 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 70
```