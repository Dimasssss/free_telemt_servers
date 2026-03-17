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

# Server Metrics 2026-03-17 20:10:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 91542.2 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1134743
telemt_connections_bad_total 8361
telemt_handshake_timeouts_total 30298
telemt_upstream_connect_attempt_total 21021
telemt_upstream_connect_success_total 20533
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 21021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30784
telemt_me_reconnect_success_total 13656
telemt_me_reader_eof_total 14849
telemt_me_idle_close_by_peer_total 14848
telemt_me_route_drop_no_conn_total 508795
telemt_me_route_drop_channel_closed_total 152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1039507
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6919
telemt_desync_full_logged_total 1980
telemt_desync_suppressed_total 4939
telemt_desync_frames_bucket_total{bucket="1_2"} 1859
telemt_desync_frames_bucket_total{bucket="3_10"} 2628
telemt_desync_frames_bucket_total{bucket="gt_10"} 2432
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14390
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13634
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 1033744
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 15694531999 (14.62 GB)
telemt_user_octets_to_client{user="hello"} 361399064987 (336.58 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 91793.3 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1141574
telemt_connections_bad_total 58670
telemt_handshake_timeouts_total 40740
telemt_upstream_connect_attempt_total 456544
telemt_upstream_connect_success_total 455668
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 456544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57240
telemt_me_reconnect_success_total 14088
telemt_me_reader_eof_total 16023
telemt_me_idle_close_by_peer_total 16023
telemt_me_route_drop_no_conn_total 284791
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544316
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2321
telemt_desync_full_logged_total 745
telemt_desync_suppressed_total 1576
telemt_desync_frames_bucket_total{bucket="1_2"} 455
telemt_desync_frames_bucket_total{bucket="3_10"} 979
telemt_desync_frames_bucket_total{bucket="gt_10"} 887
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 15611
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14072
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1523
telemt_user_connections_total{user="hello"} 980749
telemt_user_connections_current{user="hello"} 1467
telemt_user_octets_from_client{user="hello"} 13631889278 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 311011690946 (289.65 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 91569.8 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619916
telemt_connections_bad_total 32260
telemt_handshake_timeouts_total 22181
telemt_upstream_connect_attempt_total 22197
telemt_upstream_connect_success_total 22068
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38114
telemt_me_reconnect_success_total 17441
telemt_me_reader_eof_total 19047
telemt_me_idle_close_by_peer_total 19040
telemt_me_route_drop_no_conn_total 269896
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536075
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1607
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 1128
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 18326
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17429
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 534352
telemt_user_connections_current{user="hello"} 1189
telemt_user_octets_from_client{user="hello"} 28006869464 (26.08 GB)
telemt_user_octets_to_client{user="hello"} 215123940848 (200.35 GB)
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 91629.0 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120110
telemt_connections_bad_total 31791
telemt_handshake_timeouts_total 20750
telemt_upstream_connect_attempt_total 81761
telemt_upstream_connect_success_total 81354
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 81761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33709
telemt_me_reconnect_success_total 13401
telemt_me_reader_eof_total 14781
telemt_me_idle_close_by_peer_total 14780
telemt_me_route_drop_no_conn_total 467645
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910559
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3088
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 2103
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 1330
telemt_desync_frames_bucket_total{bucket="gt_10"} 1008
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 14285
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13392
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 884
telemt_user_connections_total{user="hello"} 973141
telemt_user_connections_current{user="hello"} 1394
telemt_user_octets_from_client{user="hello"} 14184868367 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 384403428465 (358.00 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 91600.9 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673341
telemt_connections_bad_total 81763
telemt_handshake_timeouts_total 5626
telemt_upstream_connect_attempt_total 40438
telemt_upstream_connect_success_total 39901
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 40437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 389
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51316
telemt_me_reconnect_success_total 18830
telemt_me_reader_eof_total 20533
telemt_me_idle_close_by_peer_total 20531
telemt_me_route_drop_no_conn_total 210633
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532565
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2406
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 1733
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 959
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20169
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18822
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1339
telemt_user_connections_total{user="hello"} 549193
telemt_user_connections_current{user="hello"} 1136
telemt_user_octets_from_client{user="hello"} 10957958576 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 253859036656 (236.42 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 91762.1 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946844
telemt_connections_bad_total 68114
telemt_handshake_timeouts_total 9054
telemt_upstream_connect_attempt_total 18150
telemt_upstream_connect_success_total 18047
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 18150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24741
telemt_me_reconnect_success_total 13466
telemt_me_reader_eof_total 14633
telemt_me_idle_close_by_peer_total 14631
telemt_me_route_drop_no_conn_total 668280
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 951676
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1896
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 726
telemt_pool_swap_total 76
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14043
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13452
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 814712
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 12562350116 (11.70 GB)
telemt_user_octets_to_client{user="hello"} 352506495628 (328.30 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 39529.0 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272234
telemt_connections_bad_total 36636
telemt_handshake_timeouts_total 6958
telemt_upstream_connect_attempt_total 16775
telemt_upstream_connect_success_total 16622
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 16775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26070
telemt_me_reconnect_success_total 14481
telemt_me_reader_eof_total 15295
telemt_me_idle_close_by_peer_total 15295
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 66153
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209212
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15016
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14454
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 209159
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 19888208289 (18.52 GB)
telemt_user_octets_to_client{user="hello"} 173227390654 (161.33 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 83
```