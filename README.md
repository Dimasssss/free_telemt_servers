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

# Server Metrics 2026-03-18 03:54:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 119366.9 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1362698
telemt_connections_bad_total 10407
telemt_handshake_timeouts_total 33536
telemt_upstream_connect_attempt_total 26345
telemt_upstream_connect_success_total 25835
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 26345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34749
telemt_me_reconnect_success_total 17605
telemt_me_reader_eof_total 19103
telemt_me_idle_close_by_peer_total 19102
telemt_me_route_drop_no_conn_total 584481
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1255292
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7903
telemt_desync_full_logged_total 2354
telemt_desync_suppressed_total 5549
telemt_desync_frames_bucket_total{bucket="1_2"} 2088
telemt_desync_frames_bucket_total{bucket="3_10"} 3023
telemt_desync_frames_bucket_total{bucket="gt_10"} 2792
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 18403
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17583
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 798
telemt_user_connections_total{user="hello"} 1249502
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 25327076167 (23.59 GB)
telemt_user_octets_to_client{user="hello"} 442660995687 (412.26 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 119618.3 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1456374
telemt_connections_bad_total 70274
telemt_handshake_timeouts_total 48049
telemt_upstream_connect_attempt_total 469518
telemt_upstream_connect_success_total 467912
telemt_upstream_connect_fail_total 1606
telemt_upstream_connect_attempts_per_request{bucket="1"} 469518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1606
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125773
telemt_me_reconnect_success_total 19048
telemt_me_reader_eof_total 21289
telemt_me_idle_close_by_peer_total 21276
telemt_me_route_drop_no_conn_total 376703
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 823247
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3770
telemt_desync_full_logged_total 1297
telemt_desync_suppressed_total 2473
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 1554
telemt_desync_frames_bucket_total{bucket="gt_10"} 1482
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20665
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19030
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1617
telemt_user_connections_total{user="hello"} 1265576
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 17077824101 (15.90 GB)
telemt_user_octets_to_client{user="hello"} 456530341266 (425.18 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 119394.4 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 887899
telemt_connections_bad_total 61939
telemt_handshake_timeouts_total 25436
telemt_upstream_connect_attempt_total 27688
telemt_upstream_connect_success_total 27529
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42242
telemt_me_reconnect_success_total 21546
telemt_me_reader_eof_total 23428
telemt_me_idle_close_by_peer_total 23421
telemt_me_route_drop_no_conn_total 345438
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747812
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2353
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1587
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 905
telemt_desync_frames_bucket_total{bucket="gt_10"} 773
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 22479
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21534
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 933
telemt_user_connections_total{user="hello"} 745927
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 44611344456 (41.55 GB)
telemt_user_octets_to_client{user="hello"} 339467509080 (316.15 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 119453.6 (33h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1363785
telemt_connections_bad_total 64900
telemt_handshake_timeouts_total 23925
telemt_upstream_connect_attempt_total 90632
telemt_upstream_connect_success_total 88200
telemt_upstream_connect_fail_total 2432
telemt_upstream_connect_attempts_per_request{bucket="1"} 90632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2432
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37899
telemt_me_reconnect_success_total 17491
telemt_me_reader_eof_total 19219
telemt_me_idle_close_by_peer_total 19216
telemt_me_route_drop_no_conn_total 556059
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1107513
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4134
telemt_desync_full_logged_total 1362
telemt_desync_suppressed_total 2772
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1728
telemt_desync_frames_bucket_total{bucket="gt_10"} 1388
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18453
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17471
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 962
telemt_user_connections_total{user="hello"} 1170878
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 18301098458 (17.04 GB)
telemt_user_octets_to_client{user="hello"} 562872496794 (524.22 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 119425.7 (33h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924933
telemt_connections_bad_total 101836
telemt_handshake_timeouts_total 7610
telemt_upstream_connect_attempt_total 47400
telemt_upstream_connect_success_total 46753
telemt_upstream_connect_fail_total 647
telemt_upstream_connect_attempts_per_request{bucket="1"} 47400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 647
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59295
telemt_me_reconnect_success_total 24331
telemt_me_reader_eof_total 26354
telemt_me_idle_close_by_peer_total 26351
telemt_me_route_drop_no_conn_total 295279
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750961
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3369
telemt_desync_full_logged_total 1018
telemt_desync_suppressed_total 2351
telemt_desync_frames_bucket_total{bucket="1_2"} 1036
telemt_desync_frames_bucket_total{bucket="3_10"} 1338
telemt_desync_frames_bucket_total{bucket="gt_10"} 995
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25803
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24323
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 767476
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 14675245420 (13.67 GB)
telemt_user_octets_to_client{user="hello"} 383498210656 (357.16 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 119586.5 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158616
telemt_connections_bad_total 126861
telemt_handshake_timeouts_total 10263
telemt_upstream_connect_attempt_total 23807
telemt_upstream_connect_success_total 23669
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 23807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29027
telemt_me_reconnect_success_total 17734
telemt_me_reader_eof_total 19223
telemt_me_idle_close_by_peer_total 19221
telemt_me_route_drop_no_conn_total 799028
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1135446
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 107
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18361
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17720
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 949697
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 15161234152 (14.12 GB)
telemt_user_octets_to_client{user="hello"} 416909885404 (388.28 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 67353.8 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469815
telemt_connections_bad_total 46965
telemt_handshake_timeouts_total 12055
telemt_upstream_connect_attempt_total 24322
telemt_upstream_connect_success_total 24078
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 24322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32194
telemt_me_reconnect_success_total 20583
telemt_me_reader_eof_total 21757
telemt_me_idle_close_by_peer_total 21757
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 114269
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339401
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 1007
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 673
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21166
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20541
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 339194
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 23224249449 (21.63 GB)
telemt_user_octets_to_client{user="hello"} 279503032490 (260.31 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 44
```