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

# Server Metrics 2026-03-18 04:10:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 120284.4 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1372793
telemt_connections_bad_total 10517
telemt_handshake_timeouts_total 33738
telemt_upstream_connect_attempt_total 26507
telemt_upstream_connect_success_total 25995
telemt_upstream_connect_fail_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 26507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 512
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34866
telemt_me_reconnect_success_total 17720
telemt_me_reader_eof_total 19225
telemt_me_idle_close_by_peer_total 19224
telemt_me_route_drop_no_conn_total 588308
telemt_me_route_drop_channel_closed_total 161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1264449
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7939
telemt_desync_full_logged_total 2370
telemt_desync_suppressed_total 5569
telemt_desync_frames_bucket_total{bucket="1_2"} 2097
telemt_desync_frames_bucket_total{bucket="3_10"} 3041
telemt_desync_frames_bucket_total{bucket="gt_10"} 2801
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18519
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17698
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 1258659
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 25429198611 (23.68 GB)
telemt_user_octets_to_client{user="hello"} 445287864483 (414.71 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 120536.0 (33h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1473380
telemt_connections_bad_total 70385
telemt_handshake_timeouts_total 48247
telemt_upstream_connect_attempt_total 469809
telemt_upstream_connect_success_total 468197
telemt_upstream_connect_fail_total 1612
telemt_upstream_connect_attempts_per_request{bucket="1"} 469809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1612
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126015
telemt_me_reconnect_success_total 19290
telemt_me_reader_eof_total 21532
telemt_me_idle_close_by_peer_total 21519
telemt_me_route_drop_no_conn_total 381893
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839380
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3789
telemt_desync_full_logged_total 1309
telemt_desync_suppressed_total 2480
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1492
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20908
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19272
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1618
telemt_user_connections_total{user="hello"} 1281697
telemt_user_connections_current{user="hello"} 1165
telemt_user_octets_from_client{user="hello"} 17351830909 (16.16 GB)
telemt_user_octets_to_client{user="hello"} 466003816198 (434.00 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 120312.1 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907503
telemt_connections_bad_total 63717
telemt_handshake_timeouts_total 25966
telemt_upstream_connect_attempt_total 27853
telemt_upstream_connect_success_total 27693
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 27853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42363
telemt_me_reconnect_success_total 21666
telemt_me_reader_eof_total 23558
telemt_me_idle_close_by_peer_total 23551
telemt_me_route_drop_no_conn_total 349453
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758481
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2399
telemt_desync_full_logged_total 784
telemt_desync_suppressed_total 1615
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 784
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 22601
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21654
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 756594
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 44762261788 (41.69 GB)
telemt_user_octets_to_client{user="hello"} 345318091960 (321.60 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 120371.3 (33h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1375194
telemt_connections_bad_total 65809
telemt_handshake_timeouts_total 24118
telemt_upstream_connect_attempt_total 90856
telemt_upstream_connect_success_total 88421
telemt_upstream_connect_fail_total 2435
telemt_upstream_connect_attempts_per_request{bucket="1"} 90856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2435
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38077
telemt_me_reconnect_success_total 17669
telemt_me_reader_eof_total 19397
telemt_me_idle_close_by_peer_total 19394
telemt_me_route_drop_no_conn_total 560284
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1117467
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4164
telemt_desync_full_logged_total 1373
telemt_desync_suppressed_total 2791
telemt_desync_frames_bucket_total{bucket="1_2"} 1028
telemt_desync_frames_bucket_total{bucket="3_10"} 1739
telemt_desync_frames_bucket_total{bucket="gt_10"} 1397
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18631
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17649
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 962
telemt_user_connections_total{user="hello"} 1180829
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 18421533434 (17.16 GB)
telemt_user_octets_to_client{user="hello"} 569511030598 (530.40 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 120343.2 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937831
telemt_connections_bad_total 102005
telemt_handshake_timeouts_total 7789
telemt_upstream_connect_attempt_total 47640
telemt_upstream_connect_success_total 46987
telemt_upstream_connect_fail_total 653
telemt_upstream_connect_attempts_per_request{bucket="1"} 47640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 419
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 653
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59486
telemt_me_reconnect_success_total 24521
telemt_me_reader_eof_total 26544
telemt_me_idle_close_by_peer_total 26541
telemt_me_route_drop_no_conn_total 299504
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763023
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3409
telemt_desync_full_logged_total 1032
telemt_desync_suppressed_total 2377
telemt_desync_frames_bucket_total{bucket="1_2"} 1039
telemt_desync_frames_bucket_total{bucket="3_10"} 1345
telemt_desync_frames_bucket_total{bucket="gt_10"} 1025
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25993
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24513
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 779536
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 14863057212 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 391657322928 (364.76 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 120504.1 (33h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164839
telemt_connections_bad_total 126866
telemt_handshake_timeouts_total 10313
telemt_upstream_connect_attempt_total 23983
telemt_upstream_connect_success_total 23844
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29159
telemt_me_reconnect_success_total 17865
telemt_me_reader_eof_total 19366
telemt_me_idle_close_by_peer_total 19364
telemt_me_route_drop_no_conn_total 804301
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1143750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2143
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1391
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 108
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18495
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17851
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 955737
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 15244231964 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 420890417128 (391.98 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 68271.4 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485338
telemt_connections_bad_total 51266
telemt_handshake_timeouts_total 12478
telemt_upstream_connect_attempt_total 24525
telemt_upstream_connect_success_total 24277
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 24525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32350
telemt_me_reconnect_success_total 20739
telemt_me_reader_eof_total 21925
telemt_me_idle_close_by_peer_total 21925
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 116574
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347516
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1525
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21324
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20696
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 347308
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 23331535457 (21.73 GB)
telemt_user_octets_to_client{user="hello"} 284293493830 (264.77 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 64
```