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

# Server Metrics 2026-03-17 22:33:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 100118.8 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211650
telemt_connections_bad_total 8770
telemt_handshake_timeouts_total 31714
telemt_upstream_connect_attempt_total 22650
telemt_upstream_connect_success_total 22156
telemt_upstream_connect_fail_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 22650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31977
telemt_me_reconnect_success_total 14844
telemt_me_reader_eof_total 16132
telemt_me_idle_close_by_peer_total 16131
telemt_me_route_drop_no_conn_total 539371
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1112220
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7319
telemt_desync_full_logged_total 2121
telemt_desync_suppressed_total 5198
telemt_desync_frames_bucket_total{bucket="1_2"} 1955
telemt_desync_frames_bucket_total{bucket="3_10"} 2765
telemt_desync_frames_bucket_total{bucket="gt_10"} 2599
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 15597
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14822
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 753
telemt_user_connections_total{user="hello"} 1106445
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 20350270931 (18.95 GB)
telemt_user_octets_to_client{user="hello"} 397951892751 (370.62 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 100370.1 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280267
telemt_connections_bad_total 60311
telemt_handshake_timeouts_total 44976
telemt_upstream_connect_attempt_total 458086
telemt_upstream_connect_success_total 457184
telemt_upstream_connect_fail_total 902
telemt_upstream_connect_attempts_per_request{bucket="1"} 458086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 902
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58323
telemt_me_reconnect_success_total 15167
telemt_me_reader_eof_total 17171
telemt_me_idle_close_by_peer_total 17171
telemt_me_route_drop_no_conn_total 331948
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 673100
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2990
telemt_desync_full_logged_total 978
telemt_desync_suppressed_total 2012
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 1228
telemt_desync_frames_bucket_total{bucket="gt_10"} 1194
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16702
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15151
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1109532
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 15235235810 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 377166562254 (351.26 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 100145.9 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741245
telemt_connections_bad_total 45788
telemt_handshake_timeouts_total 23488
telemt_upstream_connect_attempt_total 23730
telemt_upstream_connect_success_total 23591
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39206
telemt_me_reconnect_success_total 18526
telemt_me_reader_eof_total 20205
telemt_me_idle_close_by_peer_total 20198
telemt_me_route_drop_no_conn_total 307129
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634430
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2089
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 583
telemt_desync_frames_bucket_total{bucket="3_10"} 811
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19425
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18514
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 632691
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 30975991968 (28.85 GB)
telemt_user_octets_to_client{user="hello"} 274852837380 (255.98 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 100205.6 (27h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1235133
telemt_connections_bad_total 43555
telemt_handshake_timeouts_total 21582
telemt_upstream_connect_attempt_total 83355
telemt_upstream_connect_success_total 82923
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 83355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34853
telemt_me_reconnect_success_total 14531
telemt_me_reader_eof_total 16020
telemt_me_idle_close_by_peer_total 16018
telemt_me_route_drop_no_conn_total 509615
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1009586
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3742
telemt_desync_full_logged_total 1225
telemt_desync_suppressed_total 2517
telemt_desync_frames_bucket_total{bucket="1_2"} 916
telemt_desync_frames_bucket_total{bucket="3_10"} 1574
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15434
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14522
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 903
telemt_user_connections_total{user="hello"} 1072078
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 16797926299 (15.64 GB)
telemt_user_octets_to_client{user="hello"} 473388588649 (440.88 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 100177.6 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793378
telemt_connections_bad_total 94889
telemt_handshake_timeouts_total 6424
telemt_upstream_connect_attempt_total 42283
telemt_upstream_connect_success_total 41712
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 42283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 402
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55159
telemt_me_reconnect_success_total 20207
telemt_me_reader_eof_total 22034
telemt_me_idle_close_by_peer_total 22032
telemt_me_route_drop_no_conn_total 250975
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634919
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2897
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 2041
telemt_desync_frames_bucket_total{bucket="1_2"} 933
telemt_desync_frames_bucket_total{bucket="3_10"} 1159
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21640
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20199
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1433
telemt_user_connections_total{user="hello"} 651529
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 12507318364 (11.65 GB)
telemt_user_octets_to_client{user="hello"} 322942217196 (300.76 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 100338.4 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024187
telemt_connections_bad_total 84055
telemt_handshake_timeouts_total 9513
telemt_upstream_connect_attempt_total 19844
telemt_upstream_connect_success_total 19731
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 19844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25995
telemt_me_reconnect_success_total 14716
telemt_me_reader_eof_total 15983
telemt_me_idle_close_by_peer_total 15981
telemt_me_route_drop_no_conn_total 692949
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003390
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2081
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1357
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 834
telemt_pool_swap_total 86
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15312
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14702
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 866419
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 13388648224 (12.47 GB)
telemt_user_octets_to_client{user="hello"} 368521922236 (343.21 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 48105.8 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358514
telemt_connections_bad_total 44419
telemt_handshake_timeouts_total 10555
telemt_upstream_connect_attempt_total 18647
telemt_upstream_connect_success_total 18472
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 18647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27489
telemt_me_reconnect_success_total 15894
telemt_me_reader_eof_total 16801
telemt_me_idle_close_by_peer_total 16801
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 89467
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271536
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 932
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 647
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 379
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 27
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16441
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15865
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 271474
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 21324021733 (19.86 GB)
telemt_user_octets_to_client{user="hello"} 223113069194 (207.79 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 30
```