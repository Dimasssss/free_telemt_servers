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

# Server Metrics 2026-03-18 02:58:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 116007.4 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1332318
telemt_connections_bad_total 10365
telemt_handshake_timeouts_total 33252
telemt_upstream_connect_attempt_total 25702
telemt_upstream_connect_success_total 25193
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 25702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34279
telemt_me_reconnect_success_total 17138
telemt_me_reader_eof_total 18596
telemt_me_idle_close_by_peer_total 18595
telemt_me_route_drop_no_conn_total 574087
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1226561
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7796
telemt_desync_full_logged_total 2317
telemt_desync_suppressed_total 5479
telemt_desync_frames_bucket_total{bucket="1_2"} 2075
telemt_desync_frames_bucket_total{bucket="3_10"} 2976
telemt_desync_frames_bucket_total{bucket="gt_10"} 2745
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17928
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17116
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 790
telemt_user_connections_total{user="hello"} 1220773
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 24744964135 (23.05 GB)
telemt_user_octets_to_client{user="hello"} 432361872839 (402.67 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 116258.9 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1407774
telemt_connections_bad_total 64568
telemt_handshake_timeouts_total 47422
telemt_upstream_connect_attempt_total 468872
telemt_upstream_connect_success_total 467282
telemt_upstream_connect_fail_total 1590
telemt_upstream_connect_attempts_per_request{bucket="1"} 468872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1590
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 124472
telemt_me_reconnect_success_total 18551
telemt_me_reader_eof_total 20742
telemt_me_idle_close_by_peer_total 20729
telemt_me_route_drop_no_conn_total 362814
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 782706
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3653
telemt_desync_full_logged_total 1257
telemt_desync_suppressed_total 2396
telemt_desync_frames_bucket_total{bucket="1_2"} 718
telemt_desync_frames_bucket_total{bucket="3_10"} 1527
telemt_desync_frames_bucket_total{bucket="gt_10"} 1408
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 20135
telemt_me_refill_failed_total 3304
telemt_me_writer_restored_same_endpoint_total 18533
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1584
telemt_user_connections_total{user="hello"} 1225051
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 16468984809 (15.34 GB)
telemt_user_octets_to_client{user="hello"} 431996256046 (402.33 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 116034.9 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 855735
telemt_connections_bad_total 60421
telemt_handshake_timeouts_total 24765
telemt_upstream_connect_attempt_total 27017
telemt_upstream_connect_success_total 26861
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 27017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 41746
telemt_me_reconnect_success_total 21051
telemt_me_reader_eof_total 22899
telemt_me_idle_close_by_peer_total 22892
telemt_me_route_drop_no_conn_total 335735
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 719155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2247
telemt_desync_full_logged_total 730
telemt_desync_suppressed_total 1517
telemt_desync_frames_bucket_total{bucket="1_2"} 645
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 21980
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21039
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 929
telemt_user_connections_total{user="hello"} 717271
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 44169287740 (41.14 GB)
telemt_user_octets_to_client{user="hello"} 320655638584 (298.63 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 116094.5 (32h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1332577
telemt_connections_bad_total 61193
telemt_handshake_timeouts_total 22677
telemt_upstream_connect_attempt_total 89866
telemt_upstream_connect_success_total 87444
telemt_upstream_connect_fail_total 2422
telemt_upstream_connect_attempts_per_request{bucket="1"} 89866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2422
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37316
telemt_me_reconnect_success_total 16913
telemt_me_reader_eof_total 18600
telemt_me_idle_close_by_peer_total 18597
telemt_me_route_drop_no_conn_total 546018
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1082190
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4012
telemt_desync_full_logged_total 1327
telemt_desync_suppressed_total 2685
telemt_desync_frames_bucket_total{bucket="1_2"} 982
telemt_desync_frames_bucket_total{bucket="3_10"} 1677
telemt_desync_frames_bucket_total{bucket="gt_10"} 1353
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17866
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16893
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 953
telemt_user_connections_total{user="hello"} 1145558
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 17891421110 (16.66 GB)
telemt_user_octets_to_client{user="hello"} 543376006922 (506.06 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 116066.3 (32h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891658
telemt_connections_bad_total 101195
telemt_handshake_timeouts_total 6990
telemt_upstream_connect_attempt_total 46691
telemt_upstream_connect_success_total 46053
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 46691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 58767
telemt_me_reconnect_success_total 23804
telemt_me_reader_eof_total 25783
telemt_me_idle_close_by_peer_total 25780
telemt_me_route_drop_no_conn_total 284794
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721399
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3304
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 2310
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 956
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25272
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23796
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1468
telemt_user_connections_total{user="hello"} 737917
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 14048166112 (13.08 GB)
telemt_user_octets_to_client{user="hello"} 364522696396 (339.49 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 116227.3 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1139785
telemt_connections_bad_total 126504
telemt_handshake_timeouts_total 10120
telemt_upstream_connect_attempt_total 23143
telemt_upstream_connect_success_total 23009
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 23143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28496
telemt_me_reconnect_success_total 17206
telemt_me_reader_eof_total 18651
telemt_me_idle_close_by_peer_total 18649
telemt_me_route_drop_no_conn_total 785115
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1113178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 104
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17828
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17192
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 931941
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 14986311484 (13.96 GB)
telemt_user_octets_to_client{user="hello"} 408413345720 (380.36 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 63994.6 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439973
telemt_connections_bad_total 44801
telemt_handshake_timeouts_total 11737
telemt_upstream_connect_attempt_total 23399
telemt_upstream_connect_success_total 23167
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 23399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31416
telemt_me_reconnect_success_total 19807
telemt_me_reader_eof_total 20942
telemt_me_idle_close_by_peer_total 20942
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 108229
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318691
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1389
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 941
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 529
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20388
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19768
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 318627
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 22719772081 (21.16 GB)
telemt_user_octets_to_client{user="hello"} 268089433666 (249.68 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 43
```