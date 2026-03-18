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

# Server Metrics 2026-03-18 07:28:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 132196.0 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1790540
telemt_connections_bad_total 11643
telemt_handshake_timeouts_total 37503
telemt_upstream_connect_attempt_total 28598
telemt_upstream_connect_success_total 28074
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 28598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36380
telemt_me_reconnect_success_total 19218
telemt_me_reader_eof_total 20814
telemt_me_idle_close_by_peer_total 20813
telemt_me_route_drop_no_conn_total 658186
telemt_me_route_drop_channel_closed_total 191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1447005
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8688
telemt_desync_full_logged_total 2632
telemt_desync_suppressed_total 6056
telemt_desync_frames_bucket_total{bucket="1_2"} 2233
telemt_desync_frames_bucket_total{bucket="3_10"} 3362
telemt_desync_frames_bucket_total{bucket="gt_10"} 3093
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20040
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19196
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 1441277
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 33209167647 (30.93 GB)
telemt_user_octets_to_client{user="hello"} 512659496239 (477.45 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 132447.4 (36h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1881131
telemt_connections_bad_total 98288
telemt_handshake_timeouts_total 59269
telemt_upstream_connect_attempt_total 472205
telemt_upstream_connect_success_total 470555
telemt_upstream_connect_fail_total 1650
telemt_upstream_connect_attempts_per_request{bucket="1"} 472205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1650
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 130770
telemt_me_reconnect_success_total 21027
telemt_me_reader_eof_total 23438
telemt_me_idle_close_by_peer_total 23425
telemt_me_route_drop_no_conn_total 529068
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1193394
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5500
telemt_desync_full_logged_total 1909
telemt_desync_suppressed_total 3591
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 2238
telemt_desync_frames_bucket_total{bucket="gt_10"} 2230
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22761
telemt_me_refill_failed_total 3423
telemt_me_writer_restored_same_endpoint_total 21009
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1734
telemt_user_connections_total{user="hello"} 1635782
telemt_user_connections_current{user="hello"} 2646
telemt_user_octets_from_client{user="hello"} 26548776457 (24.73 GB)
telemt_user_octets_to_client{user="hello"} 642344956590 (598.23 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 812
telemt_user_unique_ips_recent_window{user="hello"} 354
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 132223.5 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395239
telemt_connections_bad_total 86490
telemt_handshake_timeouts_total 32846
telemt_upstream_connect_attempt_total 29823
telemt_upstream_connect_success_total 29656
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 29823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 43758
telemt_me_reconnect_success_total 23039
telemt_me_reader_eof_total 25026
telemt_me_idle_close_by_peer_total 25018
telemt_me_route_drop_no_conn_total 513389
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1022572
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3614
telemt_desync_full_logged_total 1213
telemt_desync_suppressed_total 2401
telemt_desync_frames_bucket_total{bucket="1_2"} 979
telemt_desync_frames_bucket_total{bucket="3_10"} 1389
telemt_desync_frames_bucket_total{bucket="gt_10"} 1246
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24011
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 23027
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 972
telemt_user_connections_total{user="hello"} 1020586
telemt_user_connections_current{user="hello"} 1757
telemt_user_octets_from_client{user="hello"} 49334476276 (45.95 GB)
telemt_user_octets_to_client{user="hello"} 492987569436 (459.13 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 132282.7 (36h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1769385
telemt_connections_bad_total 85590
telemt_handshake_timeouts_total 31688
telemt_upstream_connect_attempt_total 92989
telemt_upstream_connect_success_total 90532
telemt_upstream_connect_fail_total 2457
telemt_upstream_connect_attempts_per_request{bucket="1"} 92989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2457
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 40717
telemt_me_reconnect_success_total 19197
telemt_me_reader_eof_total 21037
telemt_me_idle_close_by_peer_total 21034
telemt_me_route_drop_no_conn_total 725698
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1462740
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5695
telemt_desync_full_logged_total 1798
telemt_desync_suppressed_total 3897
telemt_desync_frames_bucket_total{bucket="1_2"} 1324
telemt_desync_frames_bucket_total{bucket="3_10"} 2316
telemt_desync_frames_bucket_total{bucket="gt_10"} 2055
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 20226
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19177
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1029
telemt_user_connections_total{user="hello"} 1525901
telemt_user_connections_current{user="hello"} 2588
telemt_user_octets_from_client{user="hello"} 25246467042 (23.51 GB)
telemt_user_octets_to_client{user="hello"} 714603316714 (665.53 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 132254.6 (36h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1289493
telemt_connections_bad_total 116415
telemt_handshake_timeouts_total 13918
telemt_upstream_connect_attempt_total 49855
telemt_upstream_connect_success_total 49164
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 49855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 64906
telemt_me_reconnect_success_total 26124
telemt_me_reader_eof_total 28329
telemt_me_idle_close_by_peer_total 28326
telemt_me_route_drop_no_conn_total 428842
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1063477
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4587
telemt_desync_full_logged_total 1419
telemt_desync_suppressed_total 3168
telemt_desync_frames_bucket_total{bucket="1_2"} 1196
telemt_desync_frames_bucket_total{bucket="3_10"} 1774
telemt_desync_frames_bucket_total{bucket="gt_10"} 1617
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27740
telemt_me_refill_failed_total 1206
telemt_me_writer_restored_same_endpoint_total 26116
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1616
telemt_user_connections_total{user="hello"} 1079824
telemt_user_connections_current{user="hello"} 2058
telemt_user_octets_from_client{user="hello"} 21415579132 (19.94 GB)
telemt_user_octets_to_client{user="hello"} 541245327588 (504.07 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 132416.0 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1297584
telemt_connections_bad_total 134209
telemt_handshake_timeouts_total 10983
telemt_upstream_connect_attempt_total 26375
telemt_upstream_connect_success_total 26217
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30925
telemt_me_reconnect_success_total 19622
telemt_me_reader_eof_total 21234
telemt_me_idle_close_by_peer_total 21231
telemt_me_route_drop_no_conn_total 858084
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1264766
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2509
telemt_desync_full_logged_total 882
telemt_desync_suppressed_total 1627
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 990
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20275
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19608
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 1073429
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 16711393832 (15.56 GB)
telemt_user_octets_to_client{user="hello"} 470614358360 (438.29 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 80182.9 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 730755
telemt_connections_bad_total 64270
telemt_handshake_timeouts_total 15586
telemt_upstream_connect_attempt_total 26883
telemt_upstream_connect_success_total 26595
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 26882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 34081
telemt_me_reconnect_success_total 22459
telemt_me_reader_eof_total 23724
telemt_me_idle_close_by_peer_total 23724
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 210472
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553178
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2296
telemt_desync_full_logged_total 788
telemt_desync_suppressed_total 1508
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 979
telemt_desync_frames_bucket_total{bucket="gt_10"} 934
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23066
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22412
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 607
telemt_user_connections_total{user="hello"} 552861
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 28809606205 (26.83 GB)
telemt_user_octets_to_client{user="hello"} 402845973774 (375.18 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 208
```