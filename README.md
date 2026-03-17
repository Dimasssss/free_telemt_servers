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

# Server Metrics 2026-03-17 20:31:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 92765.0 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148713
telemt_connections_bad_total 8471
telemt_handshake_timeouts_total 30418
telemt_upstream_connect_attempt_total 21203
telemt_upstream_connect_success_total 20713
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30895
telemt_me_reconnect_success_total 13766
telemt_me_reader_eof_total 14969
telemt_me_idle_close_by_peer_total 14968
telemt_me_route_drop_no_conn_total 514497
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1052836
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7007
telemt_desync_full_logged_total 2010
telemt_desync_suppressed_total 4997
telemt_desync_frames_bucket_total{bucket="1_2"} 1882
telemt_desync_frames_bucket_total{bucket="3_10"} 2664
telemt_desync_frames_bucket_total{bucket="gt_10"} 2461
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14505
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13744
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 739
telemt_user_connections_total{user="hello"} 1047071
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 17365212031 (16.17 GB)
telemt_user_octets_to_client{user="hello"} 366793824443 (341.60 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 93016.3 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1169560
telemt_connections_bad_total 59022
telemt_handshake_timeouts_total 41774
telemt_upstream_connect_attempt_total 456776
telemt_upstream_connect_success_total 455896
telemt_upstream_connect_fail_total 880
telemt_upstream_connect_attempts_per_request{bucket="1"} 456776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 880
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57380
telemt_me_reconnect_success_total 14228
telemt_me_reader_eof_total 16175
telemt_me_idle_close_by_peer_total 16175
telemt_me_route_drop_no_conn_total 293847
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570040
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2461
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1674
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 949
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15753
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14212
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1525
telemt_user_connections_total{user="hello"} 1006468
telemt_user_connections_current{user="hello"} 1437
telemt_user_octets_from_client{user="hello"} 13967153854 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 325921208738 (303.54 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 92792.4 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641489
telemt_connections_bad_total 35627
telemt_handshake_timeouts_total 22262
telemt_upstream_connect_attempt_total 22394
telemt_upstream_connect_success_total 22265
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38227
telemt_me_reconnect_success_total 17553
telemt_me_reader_eof_total 19163
telemt_me_idle_close_by_peer_total 19156
telemt_me_route_drop_no_conn_total 276758
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553595
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1719
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 18438
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17541
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 551870
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 28236274320 (26.30 GB)
telemt_user_octets_to_client{user="hello"} 226466943408 (210.91 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 92851.9 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1144170
telemt_connections_bad_total 33294
telemt_handshake_timeouts_total 21101
telemt_upstream_connect_attempt_total 81970
telemt_upstream_connect_success_total 81559
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 81970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33828
telemt_me_reconnect_success_total 13518
telemt_me_reader_eof_total 14905
telemt_me_idle_close_by_peer_total 14904
telemt_me_route_drop_no_conn_total 478397
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931729
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3159
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 762
telemt_desync_frames_bucket_total{bucket="3_10"} 1351
telemt_desync_frames_bucket_total{bucket="gt_10"} 1046
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14403
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13509
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 994249
telemt_user_connections_current{user="hello"} 1275
telemt_user_octets_from_client{user="hello"} 14785913207 (13.77 GB)
telemt_user_octets_to_client{user="hello"} 402134586021 (374.52 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 92823.7 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698643
telemt_connections_bad_total 86798
telemt_handshake_timeouts_total 6000
telemt_upstream_connect_attempt_total 40706
telemt_upstream_connect_success_total 40159
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 40706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51487
telemt_me_reconnect_success_total 19002
telemt_me_reader_eof_total 20706
telemt_me_idle_close_by_peer_total 20704
telemt_me_route_drop_no_conn_total 217674
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551612
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2507
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1796
telemt_desync_frames_bucket_total{bucket="1_2"} 854
telemt_desync_frames_bucket_total{bucket="3_10"} 1001
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20345
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18994
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1343
telemt_user_connections_total{user="hello"} 568238
telemt_user_connections_current{user="hello"} 1245
telemt_user_octets_from_client{user="hello"} 11191486728 (10.42 GB)
telemt_user_octets_to_client{user="hello"} 270857225100 (252.26 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 92984.7 (25h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958121
telemt_connections_bad_total 68387
telemt_handshake_timeouts_total 9127
telemt_upstream_connect_attempt_total 18419
telemt_upstream_connect_success_total 18315
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 18419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24923
telemt_me_reconnect_success_total 13648
telemt_me_reader_eof_total 14833
telemt_me_idle_close_by_peer_total 14831
telemt_me_route_drop_no_conn_total 672786
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 961095
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1916
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1246
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 78
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14229
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13634
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 824130
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 12701402996 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 355568670776 (331.15 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 40751.9 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287730
telemt_connections_bad_total 38081
telemt_handshake_timeouts_total 8045
telemt_upstream_connect_attempt_total 17063
telemt_upstream_connect_success_total 16903
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 17063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26265
telemt_me_reconnect_success_total 14675
telemt_me_reader_eof_total 15511
telemt_me_idle_close_by_peer_total 15511
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 70295
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221744
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 662
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 481
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 19
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15212
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14647
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 221691
telemt_user_connections_current{user="hello"} 772
telemt_user_octets_from_client{user="hello"} 20308881493 (18.91 GB)
telemt_user_octets_to_client{user="hello"} 181354643890 (168.90 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 82
```