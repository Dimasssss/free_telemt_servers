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

# Server Metrics 2026-03-17 17:53:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 83289.4 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007314
telemt_connections_bad_total 6676
telemt_handshake_timeouts_total 27946
telemt_upstream_connect_attempt_total 19635
telemt_upstream_connect_success_total 19155
telemt_upstream_connect_fail_total 480
telemt_upstream_connect_attempts_per_request{bucket="1"} 19635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 480
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29795
telemt_me_reconnect_success_total 12678
telemt_me_reader_eof_total 13811
telemt_me_idle_close_by_peer_total 13810
telemt_me_route_drop_no_conn_total 460174
telemt_me_route_drop_channel_closed_total 125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 921919
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6142
telemt_desync_full_logged_total 1736
telemt_desync_suppressed_total 4406
telemt_desync_frames_bucket_total{bucket="1_2"} 1687
telemt_desync_frames_bucket_total{bucket="3_10"} 2367
telemt_desync_frames_bucket_total{bucket="gt_10"} 2088
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13391
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12656
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 713
telemt_user_connections_total{user="hello"} 916173
telemt_user_connections_current{user="hello"} 1095
telemt_user_octets_from_client{user="hello"} 14017311731 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 314814343603 (293.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 83540.9 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891124
telemt_connections_bad_total 51944
telemt_handshake_timeouts_total 32233
telemt_upstream_connect_attempt_total 365307
telemt_upstream_connect_success_total 364523
telemt_upstream_connect_fail_total 782
telemt_upstream_connect_attempts_per_request{bucket="1"} 365305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 303464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34824
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 782
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 52586
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15337
telemt_me_idle_close_by_peer_total 15337
telemt_me_route_drop_no_conn_total 236820
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417225
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1561
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 1065
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14947
telemt_me_refill_failed_total 1215
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1382
telemt_user_connections_total{user="hello"} 763898
telemt_user_connections_current{user="hello"} 1875
telemt_user_octets_from_client{user="hello"} 10263611388 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 205794276307 (191.66 GB)
telemt_user_msgs_from_client{user="hello"} 5901380
telemt_user_msgs_to_client{user="hello"} 24895731
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 83316.9 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458763
telemt_connections_bad_total 15485
telemt_handshake_timeouts_total 20778
telemt_upstream_connect_attempt_total 20781
telemt_upstream_connect_success_total 20663
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37099
telemt_me_reconnect_success_total 16431
telemt_me_reader_eof_total 17973
telemt_me_idle_close_by_peer_total 17966
telemt_me_route_drop_no_conn_total 215777
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399976
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1134
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 792
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17297
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16419
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 398168
telemt_user_connections_current{user="hello"} 1358
telemt_user_octets_from_client{user="hello"} 25726792668 (23.96 GB)
telemt_user_octets_to_client{user="hello"} 143180126868 (133.35 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 83376.4 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931608
telemt_connections_bad_total 21760
telemt_handshake_timeouts_total 18160
telemt_upstream_connect_attempt_total 80529
telemt_upstream_connect_success_total 80132
telemt_upstream_connect_fail_total 397
telemt_upstream_connect_attempts_per_request{bucket="1"} 80529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 397
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32874
telemt_me_reconnect_success_total 12574
telemt_me_reader_eof_total 13886
telemt_me_idle_close_by_peer_total 13885
telemt_me_route_drop_no_conn_total 394006
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 746912
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2391
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1625
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1064
telemt_desync_frames_bucket_total{bucket="gt_10"} 749
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13435
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12565
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 861
telemt_user_connections_total{user="hello"} 810014
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 9879322243 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 272687052477 (253.96 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 83348.0 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508398
telemt_connections_bad_total 72435
telemt_handshake_timeouts_total 4553
telemt_upstream_connect_attempt_total 38924
telemt_upstream_connect_success_total 38419
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 38924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50221
telemt_me_reconnect_success_total 17742
telemt_me_reader_eof_total 19372
telemt_me_idle_close_by_peer_total 19370
telemt_me_route_drop_no_conn_total 149026
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384641
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1733
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 693
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19053
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17734
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1311
telemt_user_connections_total{user="hello"} 401332
telemt_user_connections_current{user="hello"} 1566
telemt_user_octets_from_client{user="hello"} 7110551088 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 183035663524 (170.47 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 83510.3 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849217
telemt_connections_bad_total 60824
telemt_handshake_timeouts_total 8100
telemt_upstream_connect_attempt_total 16739
telemt_upstream_connect_success_total 16647
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 23730
telemt_me_reconnect_success_total 12460
telemt_me_reader_eof_total 13560
telemt_me_idle_close_by_peer_total 13558
telemt_me_route_drop_no_conn_total 628622
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871878
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1575
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 1034
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 13024
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12446
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 734940
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 11177481268 (10.41 GB)
telemt_user_octets_to_client{user="hello"} 321369770392 (299.30 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 31276.3 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150707
telemt_connections_bad_total 17995
telemt_handshake_timeouts_total 4869
telemt_upstream_connect_attempt_total 14603
telemt_upstream_connect_success_total 14477
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 14603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24313
telemt_me_reconnect_success_total 12736
telemt_me_reader_eof_total 13480
telemt_me_idle_close_by_peer_total 13480
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 36006
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119396
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 215
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 13249
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12713
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 119353
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 9145696881 (8.52 GB)
telemt_user_octets_to_client{user="hello"} 115883128390 (107.92 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 99
```