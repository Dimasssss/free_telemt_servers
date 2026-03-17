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

# Server Metrics 2026-03-17 18:49:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 86651.4 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059958
telemt_connections_bad_total 7521
telemt_handshake_timeouts_total 29233
telemt_upstream_connect_attempt_total 20190
telemt_upstream_connect_success_total 19704
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 20189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 30172
telemt_me_reconnect_success_total 13049
telemt_me_reader_eof_total 14204
telemt_me_idle_close_by_peer_total 14203
telemt_me_route_drop_no_conn_total 481188
telemt_me_route_drop_channel_closed_total 139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 970059
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6383
telemt_desync_full_logged_total 1820
telemt_desync_suppressed_total 4563
telemt_desync_frames_bucket_total{bucket="1_2"} 1753
telemt_desync_frames_bucket_total{bucket="3_10"} 2448
telemt_desync_frames_bucket_total{bucket="gt_10"} 2182
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13773
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13027
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 724
telemt_user_connections_total{user="hello"} 964298
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 14712836995 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 336498174191 (313.39 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 86902.6 (24h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1023920
telemt_connections_bad_total 55845
telemt_handshake_timeouts_total 34634
telemt_upstream_connect_attempt_total 455850
telemt_upstream_connect_success_total 454981
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 455850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29673
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56769
telemt_me_reconnect_success_total 13620
telemt_me_reader_eof_total 15519
telemt_me_idle_close_by_peer_total 15519
telemt_me_route_drop_no_conn_total 247132
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442076
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1639
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 1115
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 15131
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13604
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1511
telemt_user_connections_total{user="hello"} 878679
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 11925368478 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 233170221650 (217.16 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 86678.7 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527230
telemt_connections_bad_total 19038
telemt_handshake_timeouts_total 21490
telemt_upstream_connect_attempt_total 21356
telemt_upstream_connect_success_total 21238
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37500
telemt_me_reconnect_success_total 16831
telemt_me_reader_eof_total 18405
telemt_me_idle_close_by_peer_total 18398
telemt_me_route_drop_no_conn_total 239031
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460799
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1278
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 896
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 17703
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16819
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 872
telemt_user_connections_total{user="hello"} 458998
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 26738553512 (24.90 GB)
telemt_user_octets_to_client{user="hello"} 172453444552 (160.61 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 86737.9 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014745
telemt_connections_bad_total 24673
telemt_handshake_timeouts_total 19572
telemt_upstream_connect_attempt_total 81038
telemt_upstream_connect_success_total 80636
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 81038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33205
telemt_me_reconnect_success_total 12903
telemt_me_reader_eof_total 14243
telemt_me_idle_close_by_peer_total 14242
telemt_me_route_drop_no_conn_total 423642
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 818775
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2633
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 1783
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 1155
telemt_desync_frames_bucket_total{bucket="gt_10"} 846
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13773
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12894
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 870
telemt_user_connections_total{user="hello"} 881845
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 12376843691 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 321614144517 (299.53 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 86709.7 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582269
telemt_connections_bad_total 75581
telemt_handshake_timeouts_total 5083
telemt_upstream_connect_attempt_total 39640
telemt_upstream_connect_success_total 39117
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 39640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50746
telemt_me_reconnect_success_total 18265
telemt_me_reader_eof_total 19921
telemt_me_idle_close_by_peer_total 19919
telemt_me_route_drop_no_conn_total 176426
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451775
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2011
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1488
telemt_desync_frames_bucket_total{bucket="1_2"} 742
telemt_desync_frames_bucket_total{bucket="3_10"} 785
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19590
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18257
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 468444
telemt_user_connections_current{user="hello"} 1331
telemt_user_octets_from_client{user="hello"} 8436625192 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 217102967144 (202.19 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 86871.2 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 888552
telemt_connections_bad_total 61440
telemt_handshake_timeouts_total 8682
telemt_upstream_connect_attempt_total 17347
telemt_upstream_connect_success_total 17250
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24160
telemt_me_reconnect_success_total 12887
telemt_me_reader_eof_total 14019
telemt_me_idle_close_by_peer_total 14017
telemt_me_route_drop_no_conn_total 645756
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 905831
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1743
telemt_desync_full_logged_total 597
telemt_desync_suppressed_total 1146
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 71
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13459
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12873
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 768879
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 11723389064 (10.92 GB)
telemt_user_octets_to_client{user="hello"} 332491987424 (309.66 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 34638.0 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203717
telemt_connections_bad_total 21217
telemt_handshake_timeouts_total 5828
telemt_upstream_connect_attempt_total 15381
telemt_upstream_connect_success_total 15246
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 15381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24910
telemt_me_reconnect_success_total 13329
telemt_me_reader_eof_total 14110
telemt_me_idle_close_by_peer_total 14110
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 49202
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161851
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 433
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13847
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13305
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 161798
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 13252461233 (12.34 GB)
telemt_user_octets_to_client{user="hello"} 143427724650 (133.58 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 107
```