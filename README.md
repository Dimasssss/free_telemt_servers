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

# Server Metrics 2026-03-18 03:08:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 116618.3 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1337536
telemt_connections_bad_total 10366
telemt_handshake_timeouts_total 33297
telemt_upstream_connect_attempt_total 25832
telemt_upstream_connect_success_total 25323
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 25832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34366
telemt_me_reconnect_success_total 17223
telemt_me_reader_eof_total 18693
telemt_me_idle_close_by_peer_total 18692
telemt_me_route_drop_no_conn_total 576061
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1231408
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7828
telemt_desync_full_logged_total 2326
telemt_desync_suppressed_total 5502
telemt_desync_frames_bucket_total{bucket="1_2"} 2078
telemt_desync_frames_bucket_total{bucket="3_10"} 2990
telemt_desync_frames_bucket_total{bucket="gt_10"} 2760
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 18016
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17201
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 793
telemt_user_connections_total{user="hello"} 1225622
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 24784376027 (23.08 GB)
telemt_user_octets_to_client{user="hello"} 435179899043 (405.29 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 116869.7 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1414108
telemt_connections_bad_total 64572
telemt_handshake_timeouts_total 47534
telemt_upstream_connect_attempt_total 468967
telemt_upstream_connect_success_total 467377
telemt_upstream_connect_fail_total 1590
telemt_upstream_connect_attempts_per_request{bucket="1"} 468967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1590
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125367
telemt_me_reconnect_success_total 18646
telemt_me_reader_eof_total 20864
telemt_me_idle_close_by_peer_total 20851
telemt_me_route_drop_no_conn_total 364690
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788637
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3676
telemt_desync_full_logged_total 1265
telemt_desync_suppressed_total 2411
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1421
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 20257
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18628
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1611
telemt_user_connections_total{user="hello"} 1230982
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 16531060621 (15.40 GB)
telemt_user_octets_to_client{user="hello"} 434716926690 (404.86 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 116645.4 (32h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 861348
telemt_connections_bad_total 60891
telemt_handshake_timeouts_total 24823
telemt_upstream_connect_attempt_total 27153
telemt_upstream_connect_success_total 26997
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 27153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 41839
telemt_me_reconnect_success_total 21144
telemt_me_reader_eof_total 22998
telemt_me_idle_close_by_peer_total 22991
telemt_me_route_drop_no_conn_total 337337
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724027
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2282
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1542
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 884
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 22073
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21132
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 929
telemt_user_connections_total{user="hello"} 722142
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 44239985172 (41.20 GB)
telemt_user_octets_to_client{user="hello"} 323196940368 (301.00 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 116704.9 (32h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1338316
telemt_connections_bad_total 61770
telemt_handshake_timeouts_total 23207
telemt_upstream_connect_attempt_total 90022
telemt_upstream_connect_success_total 87598
telemt_upstream_connect_fail_total 2424
telemt_upstream_connect_attempts_per_request{bucket="1"} 90022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2424
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37428
telemt_me_reconnect_success_total 17023
telemt_me_reader_eof_total 18726
telemt_me_idle_close_by_peer_total 18723
telemt_me_route_drop_no_conn_total 547365
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1086675
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4024
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 2692
telemt_desync_frames_bucket_total{bucket="1_2"} 991
telemt_desync_frames_bucket_total{bucket="3_10"} 1679
telemt_desync_frames_bucket_total{bucket="gt_10"} 1354
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17979
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17003
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 956
telemt_user_connections_total{user="hello"} 1150041
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 17930265130 (16.70 GB)
telemt_user_octets_to_client{user="hello"} 546573462598 (509.04 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 116676.9 (32h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 896749
telemt_connections_bad_total 101305
telemt_handshake_timeouts_total 7058
telemt_upstream_connect_attempt_total 46856
telemt_upstream_connect_success_total 46218
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 46856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 58889
telemt_me_reconnect_success_total 23925
telemt_me_reader_eof_total 25922
telemt_me_idle_close_by_peer_total 25919
telemt_me_route_drop_no_conn_total 286601
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726143
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3312
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 2313
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1322
telemt_desync_frames_bucket_total{bucket="gt_10"} 961
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25394
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23917
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1469
telemt_user_connections_total{user="hello"} 742661
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 14230101892 (13.25 GB)
telemt_user_octets_to_client{user="hello"} 366053691816 (340.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 116837.9 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143637
telemt_connections_bad_total 126836
telemt_handshake_timeouts_total 10127
telemt_upstream_connect_attempt_total 23255
telemt_upstream_connect_success_total 23121
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 23255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28608
telemt_me_reconnect_success_total 17317
telemt_me_reader_eof_total 18774
telemt_me_idle_close_by_peer_total 18772
telemt_me_route_drop_no_conn_total 789804
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1118900
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2122
telemt_desync_full_logged_total 741
telemt_desync_suppressed_total 1381
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 805
telemt_desync_frames_bucket_total{bucket="gt_10"} 849
telemt_pool_swap_total 104
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17940
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17303
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 935371
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 15008074112 (13.98 GB)
telemt_user_octets_to_client{user="hello"} 410631639932 (382.43 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 64605.1 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444426
telemt_connections_bad_total 44848
telemt_handshake_timeouts_total 11793
telemt_upstream_connect_attempt_total 23538
telemt_upstream_connect_success_total 23306
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 23538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31551
telemt_me_reconnect_success_total 19942
telemt_me_reader_eof_total 21084
telemt_me_idle_close_by_peer_total 21084
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 109604
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322335
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1398
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 944
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 634
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20522
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19902
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 322129
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 22757831777 (21.19 GB)
telemt_user_octets_to_client{user="hello"} 270448678394 (251.87 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 57
```