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

# Server Metrics 2026-03-17 23:09:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 102261.4 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1226445
telemt_connections_bad_total 8962
telemt_handshake_timeouts_total 32248
telemt_upstream_connect_attempt_total 23051
telemt_upstream_connect_success_total 22556
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32291
telemt_me_reconnect_success_total 15159
telemt_me_reader_eof_total 16467
telemt_me_idle_close_by_peer_total 16466
telemt_me_route_drop_no_conn_total 544702
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125939
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7413
telemt_desync_full_logged_total 2156
telemt_desync_suppressed_total 5257
telemt_desync_frames_bucket_total{bucket="1_2"} 1983
telemt_desync_frames_bucket_total{bucket="3_10"} 2803
telemt_desync_frames_bucket_total{bucket="gt_10"} 2627
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15914
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15137
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 755
telemt_user_connections_total{user="hello"} 1120162
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 21134066215 (19.68 GB)
telemt_user_octets_to_client{user="hello"} 404050417643 (376.30 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 102512.9 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1298013
telemt_connections_bad_total 60678
telemt_handshake_timeouts_total 45180
telemt_upstream_connect_attempt_total 458517
telemt_upstream_connect_success_total 457610
telemt_upstream_connect_fail_total 907
telemt_upstream_connect_attempts_per_request{bucket="1"} 458517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 907
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58663
telemt_me_reconnect_success_total 15506
telemt_me_reader_eof_total 17532
telemt_me_idle_close_by_peer_total 17532
telemt_me_route_drop_no_conn_total 337309
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690061
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3170
telemt_desync_full_logged_total 1036
telemt_desync_suppressed_total 2134
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1299
telemt_desync_frames_bucket_total{bucket="gt_10"} 1250
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 17047
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15490
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 1126490
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 15506136226 (14.44 GB)
telemt_user_octets_to_client{user="hello"} 386714053310 (360.16 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 102288.9 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760814
telemt_connections_bad_total 47671
telemt_handshake_timeouts_total 23597
telemt_upstream_connect_attempt_total 24148
telemt_upstream_connect_success_total 24009
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39536
telemt_me_reconnect_success_total 18855
telemt_me_reader_eof_total 20556
telemt_me_idle_close_by_peer_total 20549
telemt_me_route_drop_no_conn_total 312035
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 647810
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2111
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1431
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19760
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18843
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 646071
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 31490895848 (29.33 GB)
telemt_user_octets_to_client{user="hello"} 284426732348 (264.89 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 102348.5 (28h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1250561
telemt_connections_bad_total 45632
telemt_handshake_timeouts_total 21637
telemt_upstream_connect_attempt_total 83747
telemt_upstream_connect_success_total 83311
telemt_upstream_connect_fail_total 436
telemt_upstream_connect_attempts_per_request{bucket="1"} 83747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 436
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35158
telemt_me_reconnect_success_total 14832
telemt_me_reader_eof_total 16340
telemt_me_idle_close_by_peer_total 16338
telemt_me_route_drop_no_conn_total 515442
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1022296
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3835
telemt_desync_full_logged_total 1259
telemt_desync_suppressed_total 2576
telemt_desync_frames_bucket_total{bucket="1_2"} 942
telemt_desync_frames_bucket_total{bucket="3_10"} 1611
telemt_desync_frames_bucket_total{bucket="gt_10"} 1282
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15742
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14823
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 910
telemt_user_connections_total{user="hello"} 1084782
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 17045035231 (15.87 GB)
telemt_user_octets_to_client{user="hello"} 488133294293 (454.61 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 102320.3 (28h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808272
telemt_connections_bad_total 95890
telemt_handshake_timeouts_total 6460
telemt_upstream_connect_attempt_total 42906
telemt_upstream_connect_success_total 42320
telemt_upstream_connect_fail_total 586
telemt_upstream_connect_attempts_per_request{bucket="1"} 42906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 404
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 586
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55681
telemt_me_reconnect_success_total 20728
telemt_me_reader_eof_total 22563
telemt_me_idle_close_by_peer_total 22561
telemt_me_route_drop_no_conn_total 256707
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648419
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3021
telemt_desync_full_logged_total 889
telemt_desync_suppressed_total 2132
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 1205
telemt_desync_frames_bucket_total{bucket="gt_10"} 846
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22169
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20720
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1441
telemt_user_connections_total{user="hello"} 665029
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 12689599664 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 330087782272 (307.42 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 102481.5 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1039762
telemt_connections_bad_total 89781
telemt_handshake_timeouts_total 9534
telemt_upstream_connect_attempt_total 20263
telemt_upstream_connect_success_total 20149
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 20263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26327
telemt_me_reconnect_success_total 15047
telemt_me_reader_eof_total 16333
telemt_me_idle_close_by_peer_total 16331
telemt_me_route_drop_no_conn_total 698239
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011881
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 88
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15646
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15033
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 874907
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 13969861712 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 370643119316 (345.19 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 50248.5 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369110
telemt_connections_bad_total 44567
telemt_handshake_timeouts_total 10652
telemt_upstream_connect_attempt_total 19209
telemt_upstream_connect_success_total 19032
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 19209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27963
telemt_me_reconnect_success_total 16367
telemt_me_reader_eof_total 17305
telemt_me_idle_close_by_peer_total 17305
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 92651
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278016
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1003
telemt_desync_full_logged_total 315
telemt_desync_suppressed_total 688
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 416
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16922
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16338
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 277954
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 21411594717 (19.94 GB)
telemt_user_octets_to_client{user="hello"} 228210848662 (212.54 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 23
```