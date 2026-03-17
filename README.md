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

# Server Metrics 2026-03-17 18:24:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 85123.3 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035791
telemt_connections_bad_total 7254
telemt_handshake_timeouts_total 28129
telemt_upstream_connect_attempt_total 19904
telemt_upstream_connect_success_total 19423
telemt_upstream_connect_fail_total 481
telemt_upstream_connect_attempts_per_request{bucket="1"} 19904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29977
telemt_me_reconnect_success_total 12858
telemt_me_reader_eof_total 14003
telemt_me_idle_close_by_peer_total 14002
telemt_me_route_drop_no_conn_total 472281
telemt_me_route_drop_channel_closed_total 135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 948401
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6253
telemt_desync_full_logged_total 1782
telemt_desync_suppressed_total 4471
telemt_desync_frames_bucket_total{bucket="1_2"} 1719
telemt_desync_frames_bucket_total{bucket="3_10"} 2410
telemt_desync_frames_bucket_total{bucket="gt_10"} 2124
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13576
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12836
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 942642
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 14347450579 (13.36 GB)
telemt_user_octets_to_client{user="hello"} 328867028875 (306.28 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 85375.6 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 969685
telemt_connections_bad_total 54973
telemt_handshake_timeouts_total 33547
telemt_upstream_connect_attempt_total 421339
telemt_upstream_connect_success_total 420490
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 421333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 350930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 55338
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15422
telemt_me_idle_close_by_peer_total 15422
telemt_me_route_drop_no_conn_total 241080
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425802
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1580
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 15033
telemt_me_refill_failed_total 1301
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1468
telemt_user_connections_total{user="hello"} 828354
telemt_user_connections_current{user="hello"} 1913
telemt_user_octets_from_client{user="hello"} 11118739412 (10.36 GB)
telemt_user_octets_to_client{user="hello"} 219279038917 (204.22 GB)
telemt_user_msgs_from_client{user="hello"} 6818146
telemt_user_msgs_to_client{user="hello"} 28649245
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 85150.5 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498729
telemt_connections_bad_total 19007
telemt_handshake_timeouts_total 21108
telemt_upstream_connect_attempt_total 21077
telemt_upstream_connect_success_total 20959
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37307
telemt_me_reconnect_success_total 16639
telemt_me_reader_eof_total 18196
telemt_me_idle_close_by_peer_total 18189
telemt_me_route_drop_no_conn_total 229152
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433977
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1209
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 846
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 512
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 17509
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16627
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 870
telemt_user_connections_total{user="hello"} 432191
telemt_user_connections_current{user="hello"} 1138
telemt_user_octets_from_client{user="hello"} 26317955352 (24.51 GB)
telemt_user_octets_to_client{user="hello"} 159089980808 (148.16 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 85209.8 (23h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979426
telemt_connections_bad_total 23628
telemt_handshake_timeouts_total 19182
telemt_upstream_connect_attempt_total 80794
telemt_upstream_connect_success_total 80393
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 80794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33049
telemt_me_reconnect_success_total 12747
telemt_me_reader_eof_total 14073
telemt_me_idle_close_by_peer_total 14072
telemt_me_route_drop_no_conn_total 410541
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 787745
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2527
telemt_desync_full_logged_total 816
telemt_desync_suppressed_total 1711
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 1111
telemt_desync_frames_bucket_total{bucket="gt_10"} 802
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13612
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12738
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 865
telemt_user_connections_total{user="hello"} 850820
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 10681935423 (9.95 GB)
telemt_user_octets_to_client{user="hello"} 301575258177 (280.86 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 85181.6 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553053
telemt_connections_bad_total 75230
telemt_handshake_timeouts_total 5018
telemt_upstream_connect_attempt_total 39339
telemt_upstream_connect_success_total 38820
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 39339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50535
telemt_me_reconnect_success_total 18054
telemt_me_reader_eof_total 19692
telemt_me_idle_close_by_peer_total 19690
telemt_me_route_drop_no_conn_total 165140
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424173
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1898
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 1414
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 431
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19377
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18046
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1323
telemt_user_connections_total{user="hello"} 440849
telemt_user_connections_current{user="hello"} 1369
telemt_user_octets_from_client{user="hello"} 7940763060 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 201324810120 (187.50 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 85343.7 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872106
telemt_connections_bad_total 60939
telemt_handshake_timeouts_total 8463
telemt_upstream_connect_attempt_total 17052
telemt_upstream_connect_success_total 16957
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 23955
telemt_me_reconnect_success_total 12684
telemt_me_reader_eof_total 13800
telemt_me_idle_close_by_peer_total 13798
telemt_me_route_drop_no_conn_total 638970
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 891653
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1661
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 1096
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13252
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12670
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 754707
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 11435412916 (10.65 GB)
telemt_user_octets_to_client{user="hello"} 327808580236 (305.30 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 33109.8 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180119
telemt_connections_bad_total 19779
telemt_handshake_timeouts_total 5435
telemt_upstream_connect_attempt_total 15027
telemt_upstream_connect_success_total 14898
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 15027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24648
telemt_me_reconnect_success_total 13069
telemt_me_reader_eof_total 13827
telemt_me_idle_close_by_peer_total 13827
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 43588
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143428
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 232
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 13583
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13045
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 143381
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 11595674793 (10.80 GB)
telemt_user_octets_to_client{user="hello"} 130998775298 (122.00 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 94
```