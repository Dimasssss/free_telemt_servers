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

# Server Metrics 2026-03-18 01:37:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 111118.7 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1291651
telemt_connections_bad_total 9622
telemt_handshake_timeouts_total 32530
telemt_upstream_connect_attempt_total 24806
telemt_upstream_connect_success_total 24304
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 24806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33608
telemt_me_reconnect_success_total 16470
telemt_me_reader_eof_total 17883
telemt_me_idle_close_by_peer_total 17882
telemt_me_route_drop_no_conn_total 563852
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1188653
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7608
telemt_desync_full_logged_total 2239
telemt_desync_suppressed_total 5369
telemt_desync_frames_bucket_total{bucket="1_2"} 2037
telemt_desync_frames_bucket_total{bucket="3_10"} 2885
telemt_desync_frames_bucket_total{bucket="gt_10"} 2686
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17248
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16448
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 778
telemt_user_connections_total{user="hello"} 1182865
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 22923249927 (21.35 GB)
telemt_user_octets_to_client{user="hello"} 421325099807 (392.39 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 111370.1 (30h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1368093
telemt_connections_bad_total 64105
telemt_handshake_timeouts_total 46675
telemt_upstream_connect_attempt_total 467455
telemt_upstream_connect_success_total 465896
telemt_upstream_connect_fail_total 1559
telemt_upstream_connect_attempts_per_request{bucket="1"} 467455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1559
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122863
telemt_me_reconnect_success_total 17430
telemt_me_reader_eof_total 19573
telemt_me_idle_close_by_peer_total 19563
telemt_me_route_drop_no_conn_total 352682
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 745372
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3456
telemt_desync_full_logged_total 1167
telemt_desync_suppressed_total 2289
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1432
telemt_desync_frames_bucket_total{bucket="gt_10"} 1349
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 18983
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17412
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1553
telemt_user_connections_total{user="hello"} 1187722
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 16128494109 (15.02 GB)
telemt_user_octets_to_client{user="hello"} 413440978730 (385.05 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 111146.0 (30h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816667
telemt_connections_bad_total 55083
telemt_handshake_timeouts_total 24318
telemt_upstream_connect_attempt_total 26040
telemt_upstream_connect_success_total 25891
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 26040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40988
telemt_me_reconnect_success_total 20302
telemt_me_reader_eof_total 22103
telemt_me_idle_close_by_peer_total 22096
telemt_me_route_drop_no_conn_total 327487
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692024
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2192
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 622
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 21221
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20290
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 690144
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 40998697140 (38.18 GB)
telemt_user_octets_to_client{user="hello"} 305126867288 (284.17 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 111205.4 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1299509
telemt_connections_bad_total 56289
telemt_handshake_timeouts_total 21976
telemt_upstream_connect_attempt_total 88850
telemt_upstream_connect_success_total 86441
telemt_upstream_connect_fail_total 2409
telemt_upstream_connect_attempts_per_request{bucket="1"} 88850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2409
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36521
telemt_me_reconnect_success_total 16128
telemt_me_reader_eof_total 17780
telemt_me_idle_close_by_peer_total 17778
telemt_me_route_drop_no_conn_total 533421
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1056009
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
telemt_me_writer_removed_unexpected_total 17069
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16117
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 1119557
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 17562043030 (16.36 GB)
telemt_user_octets_to_client{user="hello"} 528593921610 (492.29 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 111177.4 (30h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857988
telemt_connections_bad_total 99899
telemt_handshake_timeouts_total 6845
telemt_upstream_connect_attempt_total 45618
telemt_upstream_connect_success_total 44992
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 45618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57921
telemt_me_reconnect_success_total 22960
telemt_me_reader_eof_total 24903
telemt_me_idle_close_by_peer_total 24901
telemt_me_route_drop_no_conn_total 272914
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3196
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 2245
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1278
telemt_desync_frames_bucket_total{bucket="gt_10"} 911
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24418
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22952
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1458
telemt_user_connections_total{user="hello"} 708824
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 13742501716 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 352276780620 (328.08 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 111338.4 (30h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104468
telemt_connections_bad_total 113428
telemt_handshake_timeouts_total 9684
telemt_upstream_connect_attempt_total 22139
telemt_upstream_connect_success_total 22015
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27759
telemt_me_reconnect_success_total 16474
telemt_me_reader_eof_total 17881
telemt_me_idle_close_by_peer_total 17879
telemt_me_route_drop_no_conn_total 753998
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075975
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
telemt_me_writer_removed_unexpected_total 17091
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16460
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 910947
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 14815929488 (13.80 GB)
telemt_user_octets_to_client{user="hello"} 393028535468 (366.04 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 59105.6 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412488
telemt_connections_bad_total 44709
telemt_handshake_timeouts_total 10952
telemt_upstream_connect_attempt_total 22024
telemt_upstream_connect_success_total 21822
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 22024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30323
telemt_me_reconnect_success_total 18721
telemt_me_reader_eof_total 19804
telemt_me_idle_close_by_peer_total 19804
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 102124
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299519
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1260
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 872
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 555
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19291
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18687
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 299455
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 22482285765 (20.94 GB)
telemt_user_octets_to_client{user="hello"} 251279381978 (234.02 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 34
```