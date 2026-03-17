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

# Server Metrics 2026-03-17 18:29:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 85429.0 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040165
telemt_connections_bad_total 7412
telemt_handshake_timeouts_total 28177
telemt_upstream_connect_attempt_total 19927
telemt_upstream_connect_success_total 19446
telemt_upstream_connect_fail_total 481
telemt_upstream_connect_attempts_per_request{bucket="1"} 19927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 30000
telemt_me_reconnect_success_total 12880
telemt_me_reader_eof_total 14027
telemt_me_idle_close_by_peer_total 14026
telemt_me_route_drop_no_conn_total 474045
telemt_me_route_drop_channel_closed_total 135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 952227
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6291
telemt_desync_full_logged_total 1789
telemt_desync_suppressed_total 4502
telemt_desync_frames_bucket_total{bucket="1_2"} 1735
telemt_desync_frames_bucket_total{bucket="3_10"} 2419
telemt_desync_frames_bucket_total{bucket="gt_10"} 2137
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13600
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12858
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 720
telemt_user_connections_total{user="hello"} 946468
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 14397473223 (13.41 GB)
telemt_user_octets_to_client{user="hello"} 330083768863 (307.41 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 85680.6 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 984698
telemt_connections_bad_total 55492
telemt_handshake_timeouts_total 33736
telemt_upstream_connect_attempt_total 431708
telemt_upstream_connect_success_total 430849
telemt_upstream_connect_fail_total 854
telemt_upstream_connect_attempts_per_request{bucket="1"} 431703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 359792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 854
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56298
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15450
telemt_me_idle_close_by_peer_total 15450
telemt_me_route_drop_no_conn_total 242720
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429277
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1582
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1077
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 15063
telemt_me_refill_failed_total 1331
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1498
telemt_user_connections_total{user="hello"} 842145
telemt_user_connections_current{user="hello"} 1563
telemt_user_octets_from_client{user="hello"} 11283251480 (10.51 GB)
telemt_user_octets_to_client{user="hello"} 221495791883 (206.28 GB)
telemt_user_msgs_from_client{user="hello"} 6966581
telemt_user_msgs_to_client{user="hello"} 29280072
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 85456.6 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504123
telemt_connections_bad_total 19008
telemt_handshake_timeouts_total 21174
telemt_upstream_connect_attempt_total 21102
telemt_upstream_connect_success_total 20984
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37332
telemt_me_reconnect_success_total 16663
telemt_me_reader_eof_total 18222
telemt_me_idle_close_by_peer_total 18215
telemt_me_route_drop_no_conn_total 231278
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439134
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1222
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 855
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 519
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 17534
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16651
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 437348
telemt_user_connections_current{user="hello"} 1231
telemt_user_octets_from_client{user="hello"} 26359477788 (24.55 GB)
telemt_user_octets_to_client{user="hello"} 161159894916 (150.09 GB)
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 85515.7 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985629
telemt_connections_bad_total 23640
telemt_handshake_timeouts_total 19370
telemt_upstream_connect_attempt_total 80811
telemt_upstream_connect_success_total 80410
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 80811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33066
telemt_me_reconnect_success_total 12764
telemt_me_reader_eof_total 14092
telemt_me_idle_close_by_peer_total 14091
telemt_me_route_drop_no_conn_total 412641
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 793562
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2532
telemt_desync_full_logged_total 818
telemt_desync_suppressed_total 1714
telemt_desync_frames_bucket_total{bucket="1_2"} 615
telemt_desync_frames_bucket_total{bucket="3_10"} 1112
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13631
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12755
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 867
telemt_user_connections_total{user="hello"} 856639
telemt_user_connections_current{user="hello"} 1566
telemt_user_octets_from_client{user="hello"} 10827130851 (10.08 GB)
telemt_user_octets_to_client{user="hello"} 305368803969 (284.40 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 85487.5 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559130
telemt_connections_bad_total 75290
telemt_handshake_timeouts_total 5034
telemt_upstream_connect_attempt_total 39387
telemt_upstream_connect_success_total 38868
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 39387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50583
telemt_me_reconnect_success_total 18102
telemt_me_reader_eof_total 19740
telemt_me_idle_close_by_peer_total 19738
telemt_me_route_drop_no_conn_total 167536
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429906
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1930
telemt_desync_full_logged_total 494
telemt_desync_suppressed_total 1436
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19425
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18094
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1323
telemt_user_connections_total{user="hello"} 446580
telemt_user_connections_current{user="hello"} 1457
telemt_user_octets_from_client{user="hello"} 8028879016 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 204506134188 (190.46 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 85649.7 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875636
telemt_connections_bad_total 61117
telemt_handshake_timeouts_total 8554
telemt_upstream_connect_attempt_total 17134
telemt_upstream_connect_success_total 17039
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 23994
telemt_me_reconnect_success_total 12723
telemt_me_reader_eof_total 13842
telemt_me_idle_close_by_peer_total 13840
telemt_me_route_drop_no_conn_total 640395
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1677
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 624
telemt_pool_swap_total 70
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13291
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12709
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 757656
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 11460602580 (10.67 GB)
telemt_user_octets_to_client{user="hello"} 328752055420 (306.17 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 33415.9 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184666
telemt_connections_bad_total 20059
telemt_handshake_timeouts_total 5510
telemt_upstream_connect_attempt_total 15123
telemt_upstream_connect_success_total 14991
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 15123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24698
telemt_me_reconnect_success_total 13118
telemt_me_reader_eof_total 13876
telemt_me_idle_close_by_peer_total 13876
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 44619
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147137
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 328
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 13633
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13094
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 147088
telemt_user_connections_current{user="hello"} 963
telemt_user_octets_from_client{user="hello"} 11999923105 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 133949411330 (124.75 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 95
```