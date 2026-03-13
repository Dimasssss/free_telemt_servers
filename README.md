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

# Server Metrics 2026-03-13 16:16:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 117796.2 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490212
telemt_connections_bad_total 3623
telemt_handshake_timeouts_total 8897
telemt_upstream_connect_attempt_total 29320
telemt_upstream_connect_success_total 29178
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 29320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2550
telemt_me_reconnect_attempts_total 26838
telemt_me_reconnect_success_total 23300
telemt_me_reader_eof_total 24892
telemt_me_idle_close_by_peer_total 24891
telemt_me_route_drop_no_conn_total 160731
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430777
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1392
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 904
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 500
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 23657
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23284
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 430349
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 7638011548 (7.11 GB)
telemt_user_octets_to_client{user="hello"} 200872092156 (187.08 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 117688.9 (32h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237974
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1732
telemt_upstream_connect_attempt_total 94244
telemt_upstream_connect_success_total 93449
telemt_upstream_connect_fail_total 795
telemt_upstream_connect_attempts_per_request{bucket="1"} 94244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 795
telemt_me_keepalive_timeout_total 1418
telemt_me_reconnect_attempts_total 117685
telemt_me_reconnect_success_total 26024
telemt_me_reader_eof_total 29644
telemt_me_idle_close_by_peer_total 29644
telemt_me_route_drop_no_conn_total 81792
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163834
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 28
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
telemt_me_writer_removed_unexpected_total 29112
telemt_me_refill_failed_total 2860
telemt_me_writer_restored_same_endpoint_total 26007
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3088
telemt_user_connections_total{user="hello"} 225176
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2355923519 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 70233747814 (65.41 GB)
telemt_user_msgs_from_client{user="hello"} 955634
telemt_user_msgs_to_client{user="hello"} 5717293
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 117652.6 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285094
telemt_connections_bad_total 2445
telemt_handshake_timeouts_total 14011
telemt_upstream_connect_attempt_total 31443
telemt_upstream_connect_success_total 31439
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2418
telemt_me_reconnect_attempts_total 26744
telemt_me_reconnect_success_total 25522
telemt_me_reader_eof_total 27357
telemt_me_idle_close_by_peer_total 27357
telemt_me_route_drop_no_conn_total 102734
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258527
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 25808
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25502
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 258439
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 9694356416 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 109070543760 (101.58 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 117628.2 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386541
telemt_connections_bad_total 15068
telemt_handshake_timeouts_total 3808
telemt_upstream_connect_attempt_total 43288
telemt_upstream_connect_success_total 33098
telemt_upstream_connect_fail_total 10190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10190
telemt_me_keepalive_timeout_total 4177
telemt_me_reconnect_attempts_total 107004
telemt_me_reconnect_success_total 24178
telemt_me_reader_eof_total 27474
telemt_me_idle_close_by_peer_total 27467
telemt_me_route_drop_no_conn_total 138466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335779
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27073
telemt_me_refill_failed_total 2583
telemt_me_writer_restored_same_endpoint_total 24168
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2895
telemt_user_connections_total{user="hello"} 338693
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 7315870398 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 125296068741 (116.69 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 67799.6 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107694
telemt_connections_bad_total 14090
telemt_handshake_timeouts_total 1348
telemt_upstream_connect_attempt_total 27272
telemt_upstream_connect_success_total 27031
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 27272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_timeout_total 1064
telemt_me_reconnect_attempts_total 29897
telemt_me_reconnect_success_total 18724
telemt_me_reader_eof_total 20079
telemt_me_idle_close_by_peer_total 20079
telemt_me_route_drop_no_conn_total 32924
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 19234
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18706
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 88773
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 1020911093 (973.62 MB)
telemt_user_octets_to_client{user="hello"} 27411896887 (25.53 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 117585.2 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714991
telemt_connections_bad_total 24634
telemt_handshake_timeouts_total 23967
telemt_upstream_connect_attempt_total 24587
telemt_upstream_connect_success_total 24464
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 24587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2566
telemt_me_reconnect_attempts_total 23255
telemt_me_reconnect_success_total 18625
telemt_me_reader_eof_total 19987
telemt_me_idle_close_by_peer_total 19984
telemt_me_route_drop_no_conn_total 337560
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670038
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 19007
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18618
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 642932
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 11195030992 (10.43 GB)
telemt_user_octets_to_client{user="hello"} 329671229060 (307.03 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 76
```