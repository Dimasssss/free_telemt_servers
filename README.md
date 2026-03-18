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

# Server Metrics 2026-03-18 01:32:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 110813.3 (30h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1289504
telemt_connections_bad_total 9620
telemt_handshake_timeouts_total 32519
telemt_upstream_connect_attempt_total 24744
telemt_upstream_connect_success_total 24242
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 24744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33546
telemt_me_reconnect_success_total 16408
telemt_me_reader_eof_total 17812
telemt_me_idle_close_by_peer_total 17811
telemt_me_route_drop_no_conn_total 563400
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1186645
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7603
telemt_desync_full_logged_total 2237
telemt_desync_suppressed_total 5366
telemt_desync_frames_bucket_total{bucket="1_2"} 2036
telemt_desync_frames_bucket_total{bucket="3_10"} 2883
telemt_desync_frames_bucket_total{bucket="gt_10"} 2684
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17186
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16386
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 778
telemt_user_connections_total{user="hello"} 1180857
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 22893827999 (21.32 GB)
telemt_user_octets_to_client{user="hello"} 420783825535 (391.89 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 111064.6 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1365991
telemt_connections_bad_total 64105
telemt_handshake_timeouts_total 46635
telemt_upstream_connect_attempt_total 467390
telemt_upstream_connect_success_total 465831
telemt_upstream_connect_fail_total 1559
telemt_upstream_connect_attempts_per_request{bucket="1"} 467390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1559
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122798
telemt_me_reconnect_success_total 17365
telemt_me_reader_eof_total 19509
telemt_me_idle_close_by_peer_total 19499
telemt_me_route_drop_no_conn_total 352150
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743428
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3452
telemt_desync_full_logged_total 1163
telemt_desync_suppressed_total 2289
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1429
telemt_desync_frames_bucket_total{bucket="gt_10"} 1348
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 18918
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17347
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1553
telemt_user_connections_total{user="hello"} 1185778
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 16115088669 (15.01 GB)
telemt_user_octets_to_client{user="hello"} 412753677690 (384.41 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 110840.7 (30h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814866
telemt_connections_bad_total 54795
telemt_handshake_timeouts_total 24296
telemt_upstream_connect_attempt_total 25975
telemt_upstream_connect_success_total 25826
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 25975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40923
telemt_me_reconnect_success_total 20237
telemt_me_reader_eof_total 22033
telemt_me_idle_close_by_peer_total 22026
telemt_me_route_drop_no_conn_total 326650
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690566
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2191
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 21156
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20225
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 688686
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 40873048240 (38.07 GB)
telemt_user_octets_to_client{user="hello"} 304470558964 (283.56 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 110900.0 (30h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1298048
telemt_connections_bad_total 55999
telemt_handshake_timeouts_total 21963
telemt_upstream_connect_attempt_total 88801
telemt_upstream_connect_success_total 86393
telemt_upstream_connect_fail_total 2408
telemt_upstream_connect_attempts_per_request{bucket="1"} 88801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2408
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36472
telemt_me_reconnect_success_total 16080
telemt_me_reader_eof_total 17732
telemt_me_idle_close_by_peer_total 17730
telemt_me_route_drop_no_conn_total 532911
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1054878
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3955
telemt_desync_full_logged_total 1308
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 17021
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16069
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 1118426
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 17541170882 (16.34 GB)
telemt_user_octets_to_client{user="hello"} 527920576342 (491.66 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 110872.1 (30h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856316
telemt_connections_bad_total 99845
telemt_handshake_timeouts_total 6843
telemt_upstream_connect_attempt_total 45556
telemt_upstream_connect_success_total 44930
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 45556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57859
telemt_me_reconnect_success_total 22898
telemt_me_reader_eof_total 24841
telemt_me_idle_close_by_peer_total 24839
telemt_me_route_drop_no_conn_total 272417
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690639
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3194
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 2245
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 910
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24356
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22890
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1458
telemt_user_connections_total{user="hello"} 707245
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 13677972788 (12.74 GB)
telemt_user_octets_to_client{user="hello"} 351880545384 (327.71 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 111032.9 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102660
telemt_connections_bad_total 112613
telemt_handshake_timeouts_total 9683
telemt_upstream_connect_attempt_total 22097
telemt_upstream_connect_success_total 21973
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27717
telemt_me_reconnect_success_total 16432
telemt_me_reader_eof_total 17837
telemt_me_idle_close_by_peer_total 17835
telemt_me_route_drop_no_conn_total 753480
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1074992
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
telemt_pool_swap_total 98
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17047
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16418
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 909964
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 14788910796 (13.77 GB)
telemt_user_octets_to_client{user="hello"} 392445540560 (365.49 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 58800.2 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410926
telemt_connections_bad_total 44705
telemt_handshake_timeouts_total 10943
telemt_upstream_connect_attempt_total 21950
telemt_upstream_connect_success_total 21748
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 21950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30249
telemt_me_reconnect_success_total 18647
telemt_me_reader_eof_total 19730
telemt_me_idle_close_by_peer_total 19730
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 101743
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298556
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1252
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 551
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19217
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18613
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 298492
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 22469815389 (20.93 GB)
telemt_user_octets_to_client{user="hello"} 250196942498 (233.01 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 37
```