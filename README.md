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

# Server Metrics 2026-03-13 17:12:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 121157.8 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509335
telemt_connections_bad_total 6394
telemt_handshake_timeouts_total 11336
telemt_upstream_connect_attempt_total 30096
telemt_upstream_connect_success_total 29947
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 30096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3361
telemt_me_reconnect_attempts_total 27435
telemt_me_reconnect_success_total 23886
telemt_me_reader_eof_total 25511
telemt_me_idle_close_by_peer_total 25510
telemt_me_route_drop_no_conn_total 165685
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443966
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1432
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 932
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24257
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23870
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 443535
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 8116810808 (7.56 GB)
telemt_user_octets_to_client{user="hello"} 206373180428 (192.20 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 121051.9 (33h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249897
telemt_connections_bad_total 1899
telemt_handshake_timeouts_total 1804
telemt_upstream_connect_attempt_total 104527
telemt_upstream_connect_success_total 103702
telemt_upstream_connect_fail_total 825
telemt_upstream_connect_attempts_per_request{bucket="1"} 104527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1440
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 825
telemt_me_keepalive_timeout_total 1490
telemt_me_reconnect_attempts_total 123200
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29823
telemt_me_idle_close_by_peer_total 29823
telemt_me_route_drop_no_conn_total 82292
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165170
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 29
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
telemt_me_writer_removed_unexpected_total 29293
telemt_me_refill_failed_total 3032
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3260
telemt_user_connections_total{user="hello"} 236576
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 2462943798 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 73182351176 (68.16 GB)
telemt_user_msgs_from_client{user="hello"} 1122078
telemt_user_msgs_to_client{user="hello"} 6568609
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 121015.6 (33h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295894
telemt_connections_bad_total 2450
telemt_handshake_timeouts_total 15859
telemt_upstream_connect_attempt_total 32358
telemt_upstream_connect_success_total 32354
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2531
telemt_me_reconnect_attempts_total 27484
telemt_me_reconnect_success_total 26259
telemt_me_reader_eof_total 28149
telemt_me_idle_close_by_peer_total 28149
telemt_me_route_drop_no_conn_total 106063
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267130
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 26551
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26239
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 267039
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 10129609976 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 111464375784 (103.81 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 120990.8 (33h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401567
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3843
telemt_upstream_connect_attempt_total 54900
telemt_upstream_connect_success_total 44680
telemt_upstream_connect_fail_total 10220
telemt_upstream_connect_attempts_per_request{bucket="1"} 54900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10220
telemt_me_keepalive_timeout_total 4319
telemt_me_reconnect_attempts_total 112726
telemt_me_reconnect_success_total 24454
telemt_me_reader_eof_total 27914
telemt_me_idle_close_by_peer_total 27907
telemt_me_route_drop_no_conn_total 140002
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338938
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
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
telemt_me_writer_removed_unexpected_total 27521
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 24444
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3067
telemt_user_connections_total{user="hello"} 352976
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 8299732303 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 128191287270 (119.39 GB)
telemt_user_msgs_from_client{user="hello"} 401947
telemt_user_msgs_to_client{user="hello"} 696708
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 71162.4 (19h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115162
telemt_connections_bad_total 14746
telemt_handshake_timeouts_total 1385
telemt_upstream_connect_attempt_total 28426
telemt_upstream_connect_success_total 28172
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 28426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 1135
telemt_me_reconnect_attempts_total 31747
telemt_me_reconnect_success_total 19705
telemt_me_reader_eof_total 21104
telemt_me_idle_close_by_peer_total 21104
telemt_me_route_drop_no_conn_total 35759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90415
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
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
telemt_me_writer_removed_unexpected_total 20260
telemt_me_refill_failed_total 374
telemt_me_writer_restored_same_endpoint_total 19687
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 95313
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1138351549 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 29226780935 (27.22 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 120949.3 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738363
telemt_connections_bad_total 24645
telemt_handshake_timeouts_total 24372
telemt_upstream_connect_attempt_total 25304
telemt_upstream_connect_success_total 25176
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 25304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 2739
telemt_me_reconnect_attempts_total 23794
telemt_me_reconnect_success_total 19156
telemt_me_reader_eof_total 20553
telemt_me_idle_close_by_peer_total 20550
telemt_me_route_drop_no_conn_total 348612
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692352
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
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19548
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19149
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 665238
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 11520740468 (10.73 GB)
telemt_user_octets_to_client{user="hello"} 336047564708 (312.97 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 54
```