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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 12:31:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 63981.0 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602962
telemt_connections_bad_total 4857
telemt_handshake_timeouts_total 19402
telemt_upstream_connect_attempt_total 15818
telemt_upstream_connect_success_total 15371
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 15818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 12635
telemt_me_reconnect_success_total 9881
telemt_me_reader_eof_total 10513
telemt_me_idle_close_by_peer_total 10512
telemt_me_route_drop_no_conn_total 195528
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543672
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1101
telemt_desync_suppressed_total 3016
telemt_desync_frames_bucket_total{bucket="1_2"} 1195
telemt_desync_frames_bucket_total{bucket="3_10"} 1712
telemt_desync_frames_bucket_total{bucket="gt_10"} 1210
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10107
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 9859
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 545571
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 7400652007 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 195963485183 (182.51 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 64233.0 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345734
telemt_connections_bad_total 18755
telemt_handshake_timeouts_total 19574
telemt_upstream_connect_attempt_total 16234
telemt_upstream_connect_success_total 16009
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 16234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 25147
telemt_me_reconnect_success_total 12811
telemt_me_reader_eof_total 13812
telemt_me_idle_close_by_peer_total 13812
telemt_me_route_drop_no_conn_total 126081
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289381
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1022
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 670
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13340
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12795
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 289360
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 3338606688 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 105840376304 (98.57 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 64008.1 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197802
telemt_connections_bad_total 7733
telemt_handshake_timeouts_total 16452
telemt_upstream_connect_attempt_total 16731
telemt_upstream_connect_success_total 16644
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15276
telemt_me_reconnect_success_total 13402
telemt_me_reader_eof_total 14315
telemt_me_idle_close_by_peer_total 14315
telemt_me_route_drop_no_conn_total 61492
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162847
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 616
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13653
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13391
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 162743
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 15129179812 (14.09 GB)
telemt_user_octets_to_client{user="hello"} 45182427780 (42.08 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 64067.4 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451864
telemt_connections_bad_total 7542
telemt_handshake_timeouts_total 12360
telemt_upstream_connect_attempt_total 15457
telemt_upstream_connect_success_total 15319
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 15457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 14443
telemt_me_reconnect_success_total 11070
telemt_me_reader_eof_total 11819
telemt_me_idle_close_by_peer_total 11819
telemt_me_route_drop_no_conn_total 127458
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378821
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1273
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 821
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 569
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11358
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 11061
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 379695
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 5010145070 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 134376197647 (125.15 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 64039.3 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229422
telemt_connections_bad_total 52630
telemt_handshake_timeouts_total 3114
telemt_upstream_connect_attempt_total 18744
telemt_upstream_connect_success_total 18500
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 18744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28817
telemt_me_reconnect_success_total 15156
telemt_me_reader_eof_total 16211
telemt_me_idle_close_by_peer_total 16211
telemt_me_route_drop_no_conn_total 60867
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165914
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 968
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15776
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 15148
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 165927
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 2227736135 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 67127043330 (62.52 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 64200.7 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545992
telemt_connections_bad_total 52081
telemt_handshake_timeouts_total 5022
telemt_upstream_connect_attempt_total 12909
telemt_upstream_connect_success_total 12840
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 13524
telemt_me_reconnect_success_total 9629
telemt_me_reader_eof_total 10382
telemt_me_idle_close_by_peer_total 10382
telemt_me_route_drop_no_conn_total 353790
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 295
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 9898
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9615
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 459270
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 6835982896 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 221378075612 (206.17 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 11967.4 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9274
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 6511
telemt_upstream_connect_success_total 6450
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 6511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8916
telemt_me_reconnect_success_total 5672
telemt_me_reader_eof_total 5953
telemt_me_idle_close_by_peer_total 5953
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 3435
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8896
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5827
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5661
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 9001
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 222272033 (211.98 MB)
telemt_user_octets_to_client{user="hello"} 19827175958 (18.47 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```