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

# Server Metrics 2026-03-17 15:50:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 75941.1 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 846407
telemt_connections_bad_total 6340
telemt_handshake_timeouts_total 24425
telemt_upstream_connect_attempt_total 18119
telemt_upstream_connect_success_total 17648
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 18119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 26237
telemt_me_reconnect_success_total 11525
telemt_me_reader_eof_total 12537
telemt_me_idle_close_by_peer_total 12536
telemt_me_route_drop_no_conn_total 355214
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769478
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5342
telemt_desync_full_logged_total 1484
telemt_desync_suppressed_total 3858
telemt_desync_frames_bucket_total{bucket="1_2"} 1538
telemt_desync_frames_bucket_total{bucket="3_10"} 2095
telemt_desync_frames_bucket_total{bucket="gt_10"} 1709
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12141
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11503
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 771296
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 12271731007 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 253892934875 (236.46 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 76192.2 (21h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563528
telemt_connections_bad_total 31889
telemt_handshake_timeouts_total 28447
telemt_upstream_connect_attempt_total 122881
telemt_upstream_connect_success_total 122323
telemt_upstream_connect_fail_total 557
telemt_upstream_connect_attempts_per_request{bucket="1"} 122880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8986
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 557
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 41507
telemt_me_reconnect_success_total 13496
telemt_me_reader_eof_total 14926
telemt_me_idle_close_by_peer_total 14926
telemt_me_route_drop_no_conn_total 194865
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372799
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1485
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14534
telemt_me_refill_failed_total 871
telemt_me_writer_restored_same_endpoint_total 13480
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1038
telemt_user_connections_total{user="hello"} 477705
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 5306640260 (4.94 GB)
telemt_user_octets_to_client{user="hello"} 135497114122 (126.19 GB)
telemt_user_msgs_from_client{user="hello"} 1550002
telemt_user_msgs_to_client{user="hello"} 5746843
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 75968.1 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284882
telemt_connections_bad_total 7852
telemt_handshake_timeouts_total 18683
telemt_upstream_connect_attempt_total 19703
telemt_upstream_connect_success_total 19599
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 32238
telemt_me_reconnect_success_total 15728
telemt_me_reader_eof_total 17107
telemt_me_idle_close_by_peer_total 17104
telemt_me_route_drop_no_conn_total 134698
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243912
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16453
telemt_me_refill_failed_total 513
telemt_me_writer_restored_same_endpoint_total 15717
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 243763
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 19113992680 (17.80 GB)
telemt_user_octets_to_client{user="hello"} 59070281680 (55.01 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 76027.5 (21h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672831
telemt_connections_bad_total 8838
telemt_handshake_timeouts_total 14237
telemt_upstream_connect_attempt_total 53466
telemt_upstream_connect_success_total 53178
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 53466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 30879
telemt_me_reconnect_success_total 11968
telemt_me_reader_eof_total 13207
telemt_me_idle_close_by_peer_total 13206
telemt_me_route_drop_no_conn_total 255920
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544602
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1867
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12767
telemt_me_refill_failed_total 586
telemt_me_writer_restored_same_endpoint_total 11959
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 581761
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 6931752688 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 175068104491 (163.04 GB)
telemt_user_msgs_from_client{user="hello"} 356501
telemt_user_msgs_to_client{user="hello"} 2549394
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 75999.4 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303269
telemt_connections_bad_total 57811
telemt_handshake_timeouts_total 3745
telemt_upstream_connect_attempt_total 21657
telemt_upstream_connect_success_total 21182
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 21657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 293
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 45554
telemt_me_reconnect_success_total 16954
telemt_me_reader_eof_total 18436
telemt_me_idle_close_by_peer_total 18434
telemt_me_route_drop_no_conn_total 86475
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228956
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1143
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 897
telemt_desync_frames_bucket_total{bucket="1_2"} 572
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18127
telemt_me_refill_failed_total 889
telemt_me_writer_restored_same_endpoint_total 16946
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1173
telemt_user_connections_total{user="hello"} 229487
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 2821119443 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 84514719931 (78.71 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 76161.2 (21h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741855
telemt_connections_bad_total 59834
telemt_handshake_timeouts_total 7116
telemt_upstream_connect_attempt_total 15354
telemt_upstream_connect_success_total 15272
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21742
telemt_me_reconnect_success_total 11442
telemt_me_reader_eof_total 12447
telemt_me_idle_close_by_peer_total 12447
telemt_me_route_drop_no_conn_total 547746
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 757611
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1109
telemt_desync_full_logged_total 395
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11945
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11428
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 637768
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 9319779492 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 285245529372 (265.66 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 23927.5 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18581
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 12885
telemt_upstream_connect_success_total 12776
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 12885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 22957
telemt_me_reconnect_success_total 11388
telemt_me_reader_eof_total 12037
telemt_me_idle_close_by_peer_total 12037
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 6975
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17697
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 11874
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11372
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 17793
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 552437009 (526.84 MB)
telemt_user_octets_to_client{user="hello"} 24172995150 (22.51 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```