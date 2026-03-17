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

# Server Metrics 2026-03-17 21:53:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 97667.9 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194381
telemt_connections_bad_total 8646
telemt_handshake_timeouts_total 31568
telemt_upstream_connect_attempt_total 22161
telemt_upstream_connect_success_total 21670
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 22161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31620
telemt_me_reconnect_success_total 14490
telemt_me_reader_eof_total 15749
telemt_me_idle_close_by_peer_total 15748
telemt_me_route_drop_no_conn_total 532329
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1095543
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7250
telemt_desync_full_logged_total 2091
telemt_desync_suppressed_total 5159
telemt_desync_frames_bucket_total{bucket="1_2"} 1937
telemt_desync_frames_bucket_total{bucket="3_10"} 2743
telemt_desync_frames_bucket_total{bucket="gt_10"} 2570
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15239
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14468
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 749
telemt_user_connections_total{user="hello"} 1089775
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 19553885063 (18.21 GB)
telemt_user_octets_to_client{user="hello"} 388416139299 (361.74 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 97919.0 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254481
telemt_connections_bad_total 59709
telemt_handshake_timeouts_total 44616
telemt_upstream_connect_attempt_total 457597
telemt_upstream_connect_success_total 456702
telemt_upstream_connect_fail_total 895
telemt_upstream_connect_attempts_per_request{bucket="1"} 457597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 895
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57971
telemt_me_reconnect_success_total 14817
telemt_me_reader_eof_total 16799
telemt_me_idle_close_by_peer_total 16799
telemt_me_route_drop_no_conn_total 321149
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648766
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2898
telemt_desync_full_logged_total 929
telemt_desync_suppressed_total 1969
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1154
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16349
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14801
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1532
telemt_user_connections_total{user="hello"} 1085196
telemt_user_connections_current{user="hello"} 1050
telemt_user_octets_from_client{user="hello"} 14964394198 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 364326165166 (339.31 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 97695.1 (27h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 713576
telemt_connections_bad_total 42944
telemt_handshake_timeouts_total 22715
telemt_upstream_connect_attempt_total 23245
telemt_upstream_connect_success_total 23108
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38852
telemt_me_reconnect_success_total 18175
telemt_me_reader_eof_total 19828
telemt_me_idle_close_by_peer_total 19821
telemt_me_route_drop_no_conn_total 299227
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614098
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1999
telemt_desync_full_logged_total 609
telemt_desync_suppressed_total 1390
telemt_desync_frames_bucket_total{bucket="1_2"} 559
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 19069
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18163
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 612368
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 30564634780 (28.47 GB)
telemt_user_octets_to_client{user="hello"} 267110555096 (248.77 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 97754.6 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1212729
telemt_connections_bad_total 39529
telemt_handshake_timeouts_total 21536
telemt_upstream_connect_attempt_total 82865
telemt_upstream_connect_success_total 82438
telemt_upstream_connect_fail_total 427
telemt_upstream_connect_attempts_per_request{bucket="1"} 82865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 427
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34498
telemt_me_reconnect_success_total 14177
telemt_me_reader_eof_total 15639
telemt_me_idle_close_by_peer_total 15637
telemt_me_route_drop_no_conn_total 502542
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991693
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3540
telemt_desync_full_logged_total 1142
telemt_desync_suppressed_total 2398
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1490
telemt_desync_frames_bucket_total{bucket="gt_10"} 1182
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 15076
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14168
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 1054191
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 16542399695 (15.41 GB)
telemt_user_octets_to_client{user="hello"} 456009434409 (424.69 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 97726.3 (27h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 767836
telemt_connections_bad_total 91578
telemt_handshake_timeouts_total 6386
telemt_upstream_connect_attempt_total 41824
telemt_upstream_connect_success_total 41265
telemt_upstream_connect_fail_total 559
telemt_upstream_connect_attempts_per_request{bucket="1"} 41824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 559
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 53592
telemt_me_reconnect_success_total 19890
telemt_me_reader_eof_total 21659
telemt_me_idle_close_by_peer_total 21657
telemt_me_route_drop_no_conn_total 241282
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613266
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2804
telemt_desync_full_logged_total 825
telemt_desync_suppressed_total 1979
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1125
telemt_desync_frames_bucket_total{bucket="gt_10"} 784
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21277
telemt_me_refill_failed_total 1048
telemt_me_writer_restored_same_endpoint_total 19882
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1387
telemt_user_connections_total{user="hello"} 629880
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 12113588844 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 309394004476 (288.15 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 97887.2 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004932
telemt_connections_bad_total 77452
telemt_handshake_timeouts_total 9420
telemt_upstream_connect_attempt_total 19319
telemt_upstream_connect_success_total 19207
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9910
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25600
telemt_me_reconnect_success_total 14322
telemt_me_reader_eof_total 15557
telemt_me_idle_close_by_peer_total 15555
telemt_me_route_drop_no_conn_total 687739
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 992482
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2056
telemt_desync_full_logged_total 716
telemt_desync_suppressed_total 1340
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 83
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 14912
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14308
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 855511
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 13318931128 (12.40 GB)
telemt_user_octets_to_client{user="hello"} 364894847852 (339.83 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 45654.5 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342740
telemt_connections_bad_total 43928
telemt_handshake_timeouts_total 10531
telemt_upstream_connect_attempt_total 18073
telemt_upstream_connect_success_total 17906
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 18073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27052
telemt_me_reconnect_success_total 15459
telemt_me_reader_eof_total 16339
telemt_me_idle_close_by_peer_total 16339
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 84229
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260700
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 871
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 617
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16001
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15431
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 260640
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 21181410881 (19.73 GB)
telemt_user_octets_to_client{user="hello"} 216553897926 (201.68 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 51
```