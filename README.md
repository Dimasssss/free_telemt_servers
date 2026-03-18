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

# Server Metrics 2026-03-18 05:11:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 123948.9 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1437864
telemt_connections_bad_total 10570
telemt_handshake_timeouts_total 34911
telemt_upstream_connect_attempt_total 27089
telemt_upstream_connect_success_total 26575
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 27089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35274
telemt_me_reconnect_success_total 18126
telemt_me_reader_eof_total 19660
telemt_me_idle_close_by_peer_total 19659
telemt_me_route_drop_no_conn_total 604502
telemt_me_route_drop_channel_closed_total 165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1308029
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8080
telemt_desync_full_logged_total 2422
telemt_desync_suppressed_total 5658
telemt_desync_frames_bucket_total{bucket="1_2"} 2130
telemt_desync_frames_bucket_total{bucket="3_10"} 3093
telemt_desync_frames_bucket_total{bucket="gt_10"} 2857
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18932
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18104
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 806
telemt_user_connections_total{user="hello"} 1302258
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 30117651735 (28.05 GB)
telemt_user_octets_to_client{user="hello"} 461367090931 (429.68 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 124201.1 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1550774
telemt_connections_bad_total 74191
telemt_handshake_timeouts_total 51406
telemt_upstream_connect_attempt_total 470511
telemt_upstream_connect_success_total 468886
telemt_upstream_connect_fail_total 1625
telemt_upstream_connect_attempts_per_request{bucket="1"} 470511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1625
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126532
telemt_me_reconnect_success_total 19804
telemt_me_reader_eof_total 22085
telemt_me_idle_close_by_peer_total 22072
telemt_me_route_drop_no_conn_total 405464
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908116
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4052
telemt_desync_full_logged_total 1411
telemt_desync_suppressed_total 2641
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 1659
telemt_desync_frames_bucket_total{bucket="gt_10"} 1602
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 21429
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19786
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1625
telemt_user_connections_total{user="hello"} 1350430
telemt_user_connections_current{user="hello"} 1447
telemt_user_octets_from_client{user="hello"} 18421622433 (17.16 GB)
telemt_user_octets_to_client{user="hello"} 509334434042 (474.35 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 123977.3 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995862
telemt_connections_bad_total 69785
telemt_handshake_timeouts_total 27998
telemt_upstream_connect_attempt_total 28463
telemt_upstream_connect_success_total 28302
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42798
telemt_me_reconnect_success_total 22097
telemt_me_reader_eof_total 24015
telemt_me_idle_close_by_peer_total 24008
telemt_me_route_drop_no_conn_total 368168
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811095
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2675
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 1801
telemt_desync_frames_bucket_total{bucket="1_2"} 737
telemt_desync_frames_bucket_total{bucket="3_10"} 1028
telemt_desync_frames_bucket_total{bucket="gt_10"} 910
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 23038
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22085
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 809203
telemt_user_connections_current{user="hello"} 1189
telemt_user_octets_from_client{user="hello"} 45582125388 (42.45 GB)
telemt_user_octets_to_client{user="hello"} 381671284256 (355.46 GB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 124036.5 (34h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1443518
telemt_connections_bad_total 71278
telemt_handshake_timeouts_total 24598
telemt_upstream_connect_attempt_total 91467
telemt_upstream_connect_success_total 89025
telemt_upstream_connect_fail_total 2442
telemt_upstream_connect_attempts_per_request{bucket="1"} 91467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2442
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38513
telemt_me_reconnect_success_total 18098
telemt_me_reader_eof_total 19859
telemt_me_idle_close_by_peer_total 19856
telemt_me_route_drop_no_conn_total 583122
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1176095
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4486
telemt_desync_full_logged_total 1464
telemt_desync_suppressed_total 3022
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 1874
telemt_desync_frames_bucket_total{bucket="gt_10"} 1534
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 19070
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18078
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 972
telemt_user_connections_total{user="hello"} 1239397
telemt_user_connections_current{user="hello"} 1407
telemt_user_octets_from_client{user="hello"} 19452195066 (18.12 GB)
telemt_user_octets_to_client{user="hello"} 604391640890 (562.88 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 124008.4 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1005960
telemt_connections_bad_total 103110
telemt_handshake_timeouts_total 9656
telemt_upstream_connect_attempt_total 48455
telemt_upstream_connect_success_total 47787
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 48455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60114
telemt_me_reconnect_success_total 25148
telemt_me_reader_eof_total 27203
telemt_me_idle_close_by_peer_total 27200
telemt_me_route_drop_no_conn_total 322598
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822276
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3681
telemt_desync_full_logged_total 1123
telemt_desync_suppressed_total 2558
telemt_desync_frames_bucket_total{bucket="1_2"} 1080
telemt_desync_frames_bucket_total{bucket="3_10"} 1434
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26627
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25140
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1479
telemt_user_connections_total{user="hello"} 838757
telemt_user_connections_current{user="hello"} 1365
telemt_user_octets_from_client{user="hello"} 15936290308 (14.84 GB)
telemt_user_octets_to_client{user="hello"} 425366110324 (396.15 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 124169.8 (34h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193444
telemt_connections_bad_total 127304
telemt_handshake_timeouts_total 10436
telemt_upstream_connect_attempt_total 24686
telemt_upstream_connect_success_total 24542
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 24686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29685
telemt_me_reconnect_success_total 18391
telemt_me_reader_eof_total 19930
telemt_me_idle_close_by_peer_total 19928
telemt_me_route_drop_no_conn_total 819702
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1173467
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2237
telemt_desync_full_logged_total 779
telemt_desync_suppressed_total 1458
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 112
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19028
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18377
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 982149
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 15585198904 (14.51 GB)
telemt_user_octets_to_client{user="hello"} 437674204616 (407.62 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 71936.6 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538982
telemt_connections_bad_total 53871
telemt_handshake_timeouts_total 13217
telemt_upstream_connect_attempt_total 25305
telemt_upstream_connect_success_total 25044
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 25305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32945
telemt_me_reconnect_success_total 21331
telemt_me_reader_eof_total 22541
telemt_me_idle_close_by_peer_total 22541
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 131712
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388934
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1681
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1128
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21920
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21288
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 388688
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 24389969789 (22.71 GB)
telemt_user_octets_to_client{user="hello"} 307999301642 (286.85 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 114
```