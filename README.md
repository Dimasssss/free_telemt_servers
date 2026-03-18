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

# Server Metrics 2026-03-18 07:33:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 132501.4 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1805355
telemt_connections_bad_total 11643
telemt_handshake_timeouts_total 37584
telemt_upstream_connect_attempt_total 28706
telemt_upstream_connect_success_total 28182
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 28706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 36444
telemt_me_reconnect_success_total 19282
telemt_me_reader_eof_total 20879
telemt_me_idle_close_by_peer_total 20878
telemt_me_route_drop_no_conn_total 660903
telemt_me_route_drop_channel_closed_total 193
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1453488
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8722
telemt_desync_full_logged_total 2646
telemt_desync_suppressed_total 6076
telemt_desync_frames_bucket_total{bucket="1_2"} 2241
telemt_desync_frames_bucket_total{bucket="3_10"} 3377
telemt_desync_frames_bucket_total{bucket="gt_10"} 3104
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20105
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19260
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 823
telemt_user_connections_total{user="hello"} 1447757
telemt_user_connections_current{user="hello"} 1281
telemt_user_octets_from_client{user="hello"} 33428732431 (31.13 GB)
telemt_user_octets_to_client{user="hello"} 514135651323 (478.83 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 132752.9 (36h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1897599
telemt_connections_bad_total 99195
telemt_handshake_timeouts_total 59633
telemt_upstream_connect_attempt_total 472244
telemt_upstream_connect_success_total 470594
telemt_upstream_connect_fail_total 1650
telemt_upstream_connect_attempts_per_request{bucket="1"} 472244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1650
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 131705
telemt_me_reconnect_success_total 21066
telemt_me_reader_eof_total 23503
telemt_me_idle_close_by_peer_total 23490
telemt_me_route_drop_no_conn_total 537597
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1207969
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5590
telemt_desync_full_logged_total 1933
telemt_desync_suppressed_total 3657
telemt_desync_frames_bucket_total{bucket="1_2"} 1051
telemt_desync_frames_bucket_total{bucket="3_10"} 2262
telemt_desync_frames_bucket_total{bucket="gt_10"} 2277
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22828
telemt_me_refill_failed_total 3451
telemt_me_writer_restored_same_endpoint_total 21048
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1762
telemt_user_connections_total{user="hello"} 1650378
telemt_user_connections_current{user="hello"} 2691
telemt_user_octets_from_client{user="hello"} 27124250885 (25.26 GB)
telemt_user_octets_to_client{user="hello"} 648443078886 (603.91 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 815
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 132528.9 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1412726
telemt_connections_bad_total 87099
telemt_handshake_timeouts_total 33023
telemt_upstream_connect_attempt_total 29928
telemt_upstream_connect_success_total 29761
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 29928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 43819
telemt_me_reconnect_success_total 23097
telemt_me_reader_eof_total 25086
telemt_me_idle_close_by_peer_total 25078
telemt_me_route_drop_no_conn_total 518597
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032743
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3631
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2410
telemt_desync_frames_bucket_total{bucket="1_2"} 987
telemt_desync_frames_bucket_total{bucket="3_10"} 1394
telemt_desync_frames_bucket_total{bucket="gt_10"} 1250
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24072
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 23085
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 975
telemt_user_connections_total{user="hello"} 1030748
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 49450084464 (46.05 GB)
telemt_user_octets_to_client{user="hello"} 497549104368 (463.38 GB)
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 132588.4 (36h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795470
telemt_connections_bad_total 85789
telemt_handshake_timeouts_total 32343
telemt_upstream_connect_attempt_total 93084
telemt_upstream_connect_success_total 90626
telemt_upstream_connect_fail_total 2458
telemt_upstream_connect_attempts_per_request{bucket="1"} 93084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2458
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 40769
telemt_me_reconnect_success_total 19246
telemt_me_reader_eof_total 21095
telemt_me_idle_close_by_peer_total 21092
telemt_me_route_drop_no_conn_total 749274
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1486293
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5831
telemt_desync_full_logged_total 1827
telemt_desync_suppressed_total 4004
telemt_desync_frames_bucket_total{bucket="1_2"} 1337
telemt_desync_frames_bucket_total{bucket="3_10"} 2384
telemt_desync_frames_bucket_total{bucket="gt_10"} 2110
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20275
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19226
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1029
telemt_user_connections_total{user="hello"} 1549443
telemt_user_connections_current{user="hello"} 2739
telemt_user_octets_from_client{user="hello"} 26053373282 (24.26 GB)
telemt_user_octets_to_client{user="hello"} 718465592578 (669.12 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 378
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 132560.1 (36h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304167
telemt_connections_bad_total 117086
telemt_handshake_timeouts_total 14275
telemt_upstream_connect_attempt_total 49917
telemt_upstream_connect_success_total 49224
telemt_upstream_connect_fail_total 693
telemt_upstream_connect_attempts_per_request{bucket="1"} 49917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 693
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 66266
telemt_me_reconnect_success_total 26139
telemt_me_reader_eof_total 28386
telemt_me_idle_close_by_peer_total 28383
telemt_me_route_drop_no_conn_total 436265
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1076319
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4619
telemt_desync_full_logged_total 1429
telemt_desync_suppressed_total 3190
telemt_desync_frames_bucket_total{bucket="1_2"} 1197
telemt_desync_frames_bucket_total{bucket="3_10"} 1783
telemt_desync_frames_bucket_total{bucket="gt_10"} 1639
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27799
telemt_me_refill_failed_total 1248
telemt_me_writer_restored_same_endpoint_total 26131
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1660
telemt_user_connections_total{user="hello"} 1092660
telemt_user_connections_current{user="hello"} 2303
telemt_user_octets_from_client{user="hello"} 21859844820 (20.36 GB)
telemt_user_octets_to_client{user="hello"} 546206481908 (508.69 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 682
telemt_user_unique_ips_recent_window{user="hello"} 356
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 132721.2 (36h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1301666
telemt_connections_bad_total 134253
telemt_handshake_timeouts_total 11002
telemt_upstream_connect_attempt_total 26427
telemt_upstream_connect_success_total 26269
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 30977
telemt_me_reconnect_success_total 19673
telemt_me_reader_eof_total 21290
telemt_me_idle_close_by_peer_total 21287
telemt_me_route_drop_no_conn_total 860038
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1268619
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2520
telemt_desync_full_logged_total 888
telemt_desync_suppressed_total 1632
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20327
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19659
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 654
telemt_user_connections_total{user="hello"} 1077278
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 16743497028 (15.59 GB)
telemt_user_octets_to_client{user="hello"} 471452880624 (439.07 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 80488.4 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744618
telemt_connections_bad_total 69848
telemt_handshake_timeouts_total 15794
telemt_upstream_connect_attempt_total 27012
telemt_upstream_connect_success_total 26723
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 27012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 34189
telemt_me_reconnect_success_total 22566
telemt_me_reader_eof_total 23830
telemt_me_idle_close_by_peer_total 23830
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 213766
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560653
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2310
telemt_desync_full_logged_total 794
telemt_desync_suppressed_total 1516
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 943
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23173
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22519
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 607
telemt_user_connections_total{user="hello"} 560333
telemt_user_connections_current{user="hello"} 1650
telemt_user_octets_from_client{user="hello"} 29015063253 (27.02 GB)
telemt_user_octets_to_client{user="hello"} 407774346210 (379.77 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 250
```